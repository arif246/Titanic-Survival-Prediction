# Titanic Survival Prediction
This project aims to predict passenger survival on the Titanic based on various features such as age, sex, class, and fare. Using logistic regression, a common classification algorithm, this model helps identify key factors influencing survival likelihood. The project includes data preprocessing, exploratory data analysis, model training, and evaluation steps.

### Project Overview

The Titanic Survival Prediction project employs logistic regression to classify passengers as survivors or non-survivors based on available features. The primary goal is to create a reliable model to explore which factors were critical in determining survival and to evaluate model accuracy.
### Key Components

1. Data Loading and Exploration:
- Dataset: The Titanic dataset includes passenger data with features such as Pclass (passenger class), Sex, Age, Fare, and Embarked (port of embarkation), along with the target variable, Survived.
- Data Inspection: Initial inspection reveals missing values, class imbalances, and variable distributions that guide data preprocessing.

2. Data Preprocessing:
- Handling Missing Values: Missing values in the Age column are replaced with the mean, while missing values in Embarked are filled with the most frequent value.
- Dropping Unnecessary Columns: Columns like PassengerId, Name, Ticket, and Cabin are excluded as they do not directly contribute to survival prediction.
- Encoding Categorical Variables: Converts categorical variables, such as Sex and Embarked, into numerical format for model compatibility.

3. Exploratory Data Analysis (EDA):
- Visualizing Survival Distribution: Seaborn is used to create count plots of survival based on gender, passenger class, and port of embarkation, providing insights into survival rates across different groups.
- Identifying Key Factors: EDA reveals that features such as Sex, Pclass, and Age are significant predictors of survival, highlighting critical relationships within the data.

4. Data Splitting:
- The dataset is split into training and testing sets with an 80-20 ratio, ensuring the model is trained on a diverse set of passenger profiles.

5. Model Training:
- Logistic Regression: The model uses logistic regression, an interpretable and effective classifier for binary classification tasks like survival prediction.

6. Model Evaluation:
- Accuracy Score: The model’s performance is evaluated on both training and test sets using accuracy, providing a measure of how well the model generalizes to new data.

7. Results:
- Accuracy scores for training dataset is 80% and 78% for the test dataset.
## Conclusion
This project provides an accessible and insightful approach to understanding survival patterns among Titanic passengers using logistic regression. By preprocessing the data and performing exploratory analysis, we gain a clearer picture of the key factors impacting survival, such as gender and passenger class. The logistic regression model delivers reliable accuracy, making it a valuable tool for analyzing similar datasets. Future enhancements could involve exploring additional models, such as decision trees or ensemble methods, to capture more complex interactions within the data and potentially improve predictive accuracy. This project serves as a foundation for further study in predictive modeling and survival analysis.
