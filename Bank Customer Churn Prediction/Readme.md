# Background and Context
Businesses like banks that provide service have to worry about the problem of 'Churn' i.e. customers leaving and joining another service provider. It is important to understand which aspects of the service influence a customer's decision in this regard. Management can concentrate efforts on the improvement of service, keeping in mind these priorities.

# Objective
Given a Bank customer, build a neural network-based classifier that can determine whether they will leave or not in the next 6 months.

# Data Description
The case study is from an open-source dataset from Kaggle. The dataset contains 10,000 sample points with 14 distinct features such as CustomerId, CreditScore, Geography, Gender, Age, Tenure, Balance, etc.
  - CustomerId: Unique ID which is assigned to each customer
  - Surname: Last name of the customer
  - CreditScore: It defines the credit history of the customer.
  - Geography: A customer’s location
  - Gender: It defines the Gender of the customer
  - Age: Age of the customer
  - Tenure: Number of years for which the customer has been with the bank
  - NumOfProducts: It refers to the number of products that a customer has purchased through the bank.
  - Balance: Account balance
  - HasCrCard: It is a categorical variable that decides whether the customer has a credit card or not.
  - EstimatedSalary: Estimated salary
  - isActiveMember: It is a categorical variable that decides whether the customer is an active member of the bank or not ( Active member in the sense, using bank products regularly, making transactions, etc )
  - Exited: It is a categorical variable that decides whether the customer left the bank within six months or not. It can take two values
    - 0=No ( Customer did not leave the bank )
    - 1=Yes ( Customer left the bank )

# Preprocessing
The gender information is mapped to numerical values (1 for Male, 0 for Female) to facilitate model training. Exploratory Data Analysis (EDA) is performed to visualize the distribution of data using count plots and distribution plots.

# Model Training
The dataset is split into training and testing sets, and three machine learning models are trained: Decision Tree, Random Forest, and Logistic Regression. The accuracy of each model is evaluated using the test set.

# Note
  - The models' performance metrics, including confusion matrices and classification reports, are provided in the Jupyter notebook.
  - Make sure to have the necessary datasets in the specified file path.
  - Adjustments to the dataset path or other parameters may be needed based on your local environment.

Feel free to explore and enhance the project further based on your requirements.
