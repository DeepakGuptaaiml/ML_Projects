# Customer Churn Prediction App

## Background and Context
Businesses like banks that provide services have to address the problem of customer churn, i.e., customers leaving and joining another service provider. Understanding the factors influencing customer churn helps management focus on service improvements and customer retention strategies.

## Objective
This project aims to deploy a neural network-based classifier that predicts whether a bank customer will leave within the next six months. The model is already trained, and the app is deployed as an Azure Web App for easy accessibility.

## Data Description
The dataset used is an open-source dataset from Kaggle containing 10,000 customer records with 14 distinct features:
- **CustomerId**: Unique customer ID
- **Surname**: Customer’s last name
- **CreditScore**: Credit history score
- **Geography**: Customer’s location (Germany, Spain, France)
- **Gender**: Male or Female
- **Age**: Customer’s age
- **Tenure**: Number of years the customer has been with the bank
- **NumOfProducts**: Number of products the customer has purchased from the bank
- **Balance**: Customer’s account balance
- **HasCrCard**: Whether the customer has a credit card (1 = Yes, 0 = No)
- **EstimatedSalary**: Estimated salary of the customer
- **isActiveMember**: Whether the customer actively uses bank products (1 = Yes, 0 = No)
- **Exited**: Whether the customer left the bank (1 = Yes, 0 = No)

## Preprocessing
- Gender is mapped to numerical values (1 for Male, 0 for Female) to facilitate model training.
- Exploratory Data Analysis (EDA) is performed using visualization tools like Seaborn and Matplotlib.
- Standardization and scaling are applied to numerical features.

## Model Training
- The dataset is preprocessed and split into training and test sets.
- A neural network-based classifier is trained using TensorFlow and Keras.
- The trained model is serialized using Pickle for deployment.

## Installation and Deployment
This application is deployed as an Azure Web App. Follow these steps to set up and deploy:
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repository-url.git
   cd your-repository
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Deploy the application on Azure:
   - Create an Azure Web App.
   - Upload the trained model (`model.pkl`).
   - Configure the web service and environment.

## Technologies Used
The following technologies and libraries are used in this project:

### Data Loading and Manipulation
- `pandas`
- `numpy`
- `time`

### Data Visualization
- `matplotlib`
- `seaborn`

### Model Training and Preprocessing
- `scikit-learn`
  - `train_test_split`
  - `StandardScaler`
  - `MinMaxScaler`
  - `confusion_matrix`, `classification_report`, `roc_auc_score`, etc.
- `tensorflow`
  - `keras.models.Sequential`
  - `keras.layers.Dense, Dropout`

### Handling Imbalanced Data
- `imblearn.over_sampling.SMOTE`

### Model Evaluation and Metrics
- `accuracy_score`, `recall_score`, `precision_score`, `f1_score`
- `roc_curve`, `roc_auc_score`

### Saving the Model
- `pickle`

## Usage
- The application is accessible via the Azure Web App URL:
  ```
  https://your-app-name.azurewebsites.net
  ```
- Users can enter customer details via a web form to receive a churn prediction result.

## Notes
- Ensure the necessary datasets and trained model (`model.pkl`) are correctly placed in the application directory.
- Modify the dataset path and configurations based on your local setup if running the application locally.

---

For any issues or feature requests, feel free to open an issue on GitHub. 🚀
