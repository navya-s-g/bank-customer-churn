
# Bank customer churn prediction

This project aims to predict customer churn in a bank using machine learning techniques. Customer churn, also known as customer attrition, refers to the phenomenon where customers stop doing business with a company. In the context of a bank, churn occurs when customers close their accounts or stop using the bank's services.


## Dataset
The dataset used for this project is obtained from Kaggle and is titled "Bank Customer Churn Prediction." It contains various features related to bank customers, including demographics, account information, and transaction history. The target variable is 'Exited,' which indicates whether a customer has churned (1) or not (0).
## Data Preprocessing and Feature Engineering
◉ The dataset is loaded and inspected for missing values (there were none).

◉ Some features are transformed or grouped, such as creating tenure groups and dropping unnecessary columns.

◉ Visualizations are created to explore the relationship between independent variables and customer churn.

◉ One-hot encoding is applied to categorical variables.
## Model Building
Several machine learning models are built and evaluated for their ability to predict customer churn. The models include:

◉ Decision Tree Classifier

◉ Decision Tree Classifier with SMOTE for handling class imbalance

◉ Decision Tree Classifier with hyperparameter tuning

◉ Random Forest Classifier

◉ Artificial Neural Network

◉ XGBoost Classifier

## Dependencies
Python 3.x

Libraries: NumPy, Pandas, Seaborn, Matplotlib, Scikit-Learn, Imbalanced-Learn, TensorFlow, Keras, XGBoost
