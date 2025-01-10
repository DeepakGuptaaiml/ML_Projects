# Background and Context
AllLife Bank is a US bank that has a growing customer base. The majority of these customers are liability customers (depositors) with varying sizes of deposits. The number of customers who are also borrowers (asset customers) is quite small, and the bank is interested in expanding this base rapidly to bring in more loan business and in the process, earn more through the interest on loans. In particular, the management wants to explore ways of converting its liability customers to personal loan customers (while retaining them as depositors).

A campaign that the bank ran last year for liability customers showed a healthy conversion rate of over 9% success. This has encouraged the retail marketing department to devise campaigns with better target marketing to increase the success ratio.

You as a Data scientist at AllLife bank have to build a model that will help the marketing department to identify the potential customers who have a higher probability of purchasing the loan.

# Business Objective
To predict whether a liability customer will buy personal loans, to understand which customer attributes are most significant in driving purchases, and to identify which segment of customers to target more.

# Data Dictionary
  1. ID: Customer ID
  2. Age: Customer’s age in completed years
  3. Experience: #years of professional experience
  4. Income: Annual income of the customer (in thousand dollars)
  5. ZIP Code: Home Address ZIP code.
  6. Family: the Family size of the customer
  7. CCAvg: Average spending on credit cards per month (in thousand dollars)
  8. Education: Education Level. 1: Undergrad; 2: Graduate;3: Advanced/Professional
  9. Mortgage: Value of house mortgage if any. (in thousand dollars)
  10. Personal_Loan: Did this customer accept the personal loan offered in the last campaign?
  11. Securities_Account: Does the customer have securities account with the bank?
  12. CD_Account: Does the customer have a certificate of deposit (CD) account with the bank?
  13. Online: Do customers use internet banking facilities?
  14. CreditCard: Does the customer use a credit card issued by any other Bank (excluding All life Bank)?

# Preprocessing
The gender information is mapped to numerical values (1 for Male, 0 for Female) to facilitate model training. Exploratory Data Analysis (EDA) is performed to visualize the distribution of data using count plots and distribution plots.

# Model Training
The dataset is split into training and testing sets, and three machine learning models are trained: Decision Tree, Random Forest, and Logistic Regression. The accuracy of each model is evaluated using the test set.

# Note
  - The models' performance metrics, including confusion matrices and classification reports, are provided in the colab notebook.
  - Make sure to have the necessary datasets in the specified file path.
  - Adjustments to the dataset path or other parameters may be needed based on your local environment.

Feel free to explore and enhance the project further based on your requirements.
