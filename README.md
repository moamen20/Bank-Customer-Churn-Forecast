# Bank-Customer-Churn-Forecast

A prediction model that can classify if a bank customer is likely to churn or not, based on the identified factors.

The goal with this dataset of bank customers was to:

* Identify and visualize which factors contribute to customer churn
* Build a prediction model Classify if a customer is going to churn or not

## Notebook Sections
- check the dataset
- Exploratory data analysis 
- Preprocessing data
- features selection 
- building the SVM model
- Evaluating the Test Set


## Dataset

The dataset contains 10,000 records of bank customers with the following features:

- RowNumber: The index of the record.
- CustomerId: Unique identifier of a customer.
- Surname: Customer's last name.
- CreditScore: The credit score of the customer.
- Geography: The country where the customer resides.
- Gender: The customer's gender.
- Age: The age of the customer.
- Tenure: The number of years that the customer has been with the bank.
- Balance: The account balance of the customer.
- NumOfProducts: The number of bank products that the customer has.
- HasCrCard: Indicates if the customer has a credit card.
- IsActiveMember: Indicates if the customer is an active member.
- EstimatedSalary: The estimated salary of the customer.
- Exited: Indicates if the customer left the bank.

## Tools and Libraries Used

The project was implemented using Python programming language and the following libraries:
- pandas
- numpy
- matplotlib
- seaborn
- sklearn

## Analysis and Results

The project includes the following steps:
- Exploratory data analysis (EDA) to gain insights into the dataset and to identify which factors contribute to customer churn.
- Feature engineering to select the most important features for the prediction model.
- Model selection and training using several classification algorithms.
- Model evaluation using various performance metrics.

The results of the project show that the Random Forest classifier achieved the best performance in predicting customer churn.

## Conclusion

The project provides useful insights into the factors that contribute to customer churn in the banking industry and demonstrates the effectiveness of machine learning algorithms in predicting customer churn.

