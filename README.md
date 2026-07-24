# Bank Loan Prediction Engine

Around the globe, the economy is driven by a system of borrowing, debt, and repayment. To start new industry, new infrastructure, businesses, and ideas need to be arise and implemented. For that to happen, people ned **capital**. But, acquiring this capital isn't easy, requiring people to sell personal accessories and belongings to fund their ventures. Banks play an important role in spurring the economy, prevention economic recessions and *greasing the wheel of the economy*.

My recommendation compiles over 300 data points featuring borrowers demographics such as gender, marriage, education, employment, loan amount, total income, and so on. Using these features and the compiled data, the model uses logistic regression to predict whether or not a loans status is approved or denied. The dataset was acquired on [Kaggle](https://www.kaggle.com/datasets/vipin20/loan-application-data). 

> Logistic Regression is ML model that is a classification type algorithm that selects a categorical outcome -whether or not a loan is accepted or denied in our case. This model uses predictors, or features (think of it as inputs) that influence whether or not a given classification is appropriate. The model trains and alters its weight values for its features as it looks at its training data.
>> Look [here](https://www.ibm.com/think/topics/logistic-regression) for a video showing a more detailed description of a logistic regression model.

***

## Data Processing

The *df1_loan* csv file is a publicly avaliable dataset located on [Kaggle](https://www.kaggle.com/datasets/vipin20/loan-application-data). It consists of a sample of 500 borrowers, though not all is *usable*. The dataset includes demographics about each debtor such as total income, property area, employment, and so on. Eight of these features are incorported in the current ML model. Thankfully, since this file was already in a easily usable format, no data processing was neccessary.

![Pretty Cool Looking Data](https://github.com/aadhavjawahar-sys/Bank_Loan_Prediction/blob/main/images/Loan_file_display.png)

***

## Model accuracy

The model has around an 80% accuracy with both its training and testing data.

![Accuracy huh, not bad!](https://github.com/aadhavjawahar-sys/Bank_Loan_Prediction/blob/main/images/loan_accuracy.png)

> From testing, it seems to not work with test inputs on a scale different from the provided data.
 
***

## Demonstration of working model

In order to interact with my model, I built a simple graphical user interface system. Initially, the user sees this page with several input boxes, asking for both numerical and categorical inputs.

> It has default inputs for one borrower added.

![Accuracy huh, not bad!](https://github.com/aadhavjawahar-sys/Bank_Loan_Prediction/blob/main/images/ML1_1.png)

After entering and manipulating the inputs, press the submit button.

![Accuracy huh, not bad!](https://github.com/aadhavjawahar-sys/Bank_Loan_Prediction/blob/main/images/ML1_2.png)

Finally, the output on whether the loan is **accepted** or **rejected** is listed in the output box.

![Accuracy huh, not bad!](https://github.com/aadhavjawahar-sys/Bank_Loan_Prediction/blob/main/images/ML1_3.png)

***

## Future Direction

Currently, I have no plans on updating the current model until I better familiarize myself with other forms of machine learning algorithms, and potentially acquire a far larger dataset to improve my model's accuracy. Though, this would end up in a completely new project. For this models deployment, it will remain in google colab. Yet, I may continue to toy with the features for this model and find the best combination with the least inputs.
