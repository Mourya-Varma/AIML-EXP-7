AI & ML INTERNSHIP – TASK 7
Logistic Regression – Titanic Survival Prediction

Objective:
To build a Logistic Regression model to predict passenger survival on the Titanic and evaluate its performance using classification metrics.

Dataset:
Titanic Dataset (loaded using seaborn or Kaggle Titanic dataset)

Tools Used:
- Python
- Pandas
- Scikit-learn
- Matplotlib / Seaborn

Steps Performed:
1. Loaded the Titanic dataset and analyzed important features such as Age, Sex, Fare, and Survived.
2. Handled missing values:
   - Age filled with median value
   - Embarked filled with mode value
3. Removed unnecessary columns like PassengerId, Name, and Ticket.
4. Converted categorical features (Sex, Embarked) into numeric values using One-Hot Encoding.
5. Applied StandardScaler to numerical features like Age and Fare.
6. Split the dataset into training and testing sets while maintaining class balance.
7. Trained a Logistic Regression classification model.
8. Predicted survival outcomes on test data.
9. Evaluated the model using:
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Confusion Matrix
10. Plotted ROC curve and calculated AUC score for performance evaluation.

Model Used:
Logistic Regression

Evaluation Metrics:
- Accuracy: Overall correctness of predictions
- Precision: Correctly predicted survivors out of predicted survivors
- Recall: Correctly predicted survivors out of actual survivors
- F1-score: Balance between precision and recall
- Confusion Matrix: Detailed prediction results
- ROC Curve & AUC: Measures model’s ability to distinguish between classes

Files Included:
- titanic_logistic_regression.py / notebook.ipynb
- README.txt
- Confusion matrix image
- ROC curve image

Outcome:
This task helped in understanding binary classification, data preprocessing, and proper evaluation of classification models.

Final Result:
Successfully built and evaluated a Logistic Regression model to predict Titanic passenger survival.
