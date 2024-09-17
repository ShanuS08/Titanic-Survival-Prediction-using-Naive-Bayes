# Titanic-Survival-Prediction-using-Naive-Bayes
This project focuses on predicting the survival of passengers aboard the Titanic using the Naive Bayes algorithm. By utilizing the Titanic dataset, which contains information on passenger attributes such as age, class, and fare, the project aims to classify passengers into survivors and non-survivors. The model is trained using Gaussian Naive Bayes, and its performance is evaluated on a test dataset.

# Features:
- Data Loading: Load the Titanic dataset using pandas.
- Data Preprocessing:
Drop unnecessary columns such as PassengerId, Name, SibSp, Parch, Ticket, Cabin, and Embarked.
Handle missing values by replacing them with the mean (e.g., for the Age column).
Convert categorical variables like Sex into numerical values using one-hot encoding.
- Data Splitting: Split the dataset into training and test sets using an 80-20 ratio.
- Model Training: Train the model using Gaussian Naive Bayes.
- Model Evaluation:
Evaluate the model's accuracy on the training set.
Make predictions on the test set and compare them to the actual survival outcomes.
Use predict_proba to analyze the probability distribution of predictions.

# Requirements:
- Python 3.x
- Jupyter Notebook
- pandas, scikit-learn
