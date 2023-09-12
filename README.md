
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
<img width="310" alt="image" src="https://github.com/navya-s-g/bank-customer-churn/assets/133527949/bdc24f17-56fe-485c-a356-85b0cfbc2514">

◉ Decision Tree Classifier with SMOTE for handling class imbalance
<img width="317" alt="image" src="https://github.com/navya-s-g/bank-customer-churn/assets/133527949/0bc55669-d558-4e7a-96a5-31abcb601fa2">

◉ Decision Tree Classifier with hyperparameter tuning
<img width="301" alt="image" src="https://github.com/navya-s-g/bank-customer-churn/assets/133527949/cec83f79-e22b-4b84-9104-7a5c0aeba2f8">

◉ Random Forest Classifier
<img width="326" alt="image" src="https://github.com/navya-s-g/bank-customer-churn/assets/133527949/56df7048-770e-4349-9b56-75d36843dee6">

◉ Artificial Neural Network
<img width="320" alt="image" src="https://github.com/navya-s-g/bank-customer-churn/assets/133527949/f592dc14-43d4-4e3c-9f89-9d0f74bc3fb4">

◉ XGBoost Classifier
<img width="325" alt="image" src="https://github.com/navya-s-g/bank-customer-churn/assets/133527949/0fd665fb-ce0a-4342-bc8d-8ba6e0c608f3">

The Decision Tree Classifier with hyperparameter tuning yielded the best accuracy.


## Dependencies
Python 3.x

Libraries: NumPy, Pandas, Seaborn, Matplotlib, Scikit-Learn, Imbalanced-Learn, TensorFlow, Keras, XGBoost
