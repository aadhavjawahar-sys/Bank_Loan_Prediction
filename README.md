# Bank Loan Prediction Engine

Around the globe, the economy is driven by a system of borrowing, debt, and repayment. To start new industry, new infrastructure, businesses, and ideas need to be arise and implemented. For that to happen, people ned **capital**. But, acquiring this capital isn't easy, requiring people to sell personal accessories and belongings to fund their ventures. Banks play an important role in spurring the economy, prevention economic recessions and *greasing the wheel of the economy*.

My recommendation compiles over 300 data points featuring borrowers demographics such as gender, marriage, education, employment, loan amount, total income, and so on. Using these features and the compiled data, the model uses logistic regression to predict whether or not a loans status is approved or denied. The dataset was acquired on [Kaggle](https://www.kaggle.com/datasets/vipin20/loan-application-data). 

> Logistic Regression is ML model that is a classification type algorithm that selects a categorical outcome -whether or not a loan is accepted or denied in our case. This model uses predictors, or features (think of it as inputs) that influence whether or not a given classification is appropriate. The model trains and alters its weight values for its features as it looks at its training data.
>> Look [here](https://www.ibm.com/think/topics/logistic-regression) for a video showing a more detailed description of a logistic regression model.

***

## Data Processing

The *df1_loan* csv file is a publicly avaliable dataset located on [Kaggle](https://www.kaggle.com/datasets/vipin20/loan-application-data). It consists of a sample of 500 borrowers, though not all is *usable*. The dataset includes demographics about each debtor such as total income, property area, employment, and so on. Eight of these features are incorported in the current ML model. Thankfully, since this file was already in a easily usable format, no data processing was neccessary.

***

## Model accuracy
