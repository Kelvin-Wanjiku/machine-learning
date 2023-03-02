
                                          #churn modelling
  Introduction
This set of data is about bank customers and whether or not they have closed their accounts. The dataset has information about 10,000 customers' demographics, accounts, and transactions. The goal of this analysis is to look at the data, figure out what might make a customer decide to close their account, and build a model that can predict whether a customer will close their account or not.


 dataset description
There are 14 columns in the dataset:

RowNumber is the row's index.
CustomerId: Each customer's unique ID number.
Last name: The last name of the customer.

Data Analysis Steps
Load the dataset and look at what it has to offer.
Look for missing values and outliers.
Show how each variable is distributed.
Find statistics that describe each variable.
Using correlation analysis, you can find out how different things are related to each other.
Make visualizations of the data to find patterns and trends.
Use algorithms for machine learning to build a model that can make predictions.
Use the right metrics to judge how well the model works.
Read the results and figure out what they mean.

Conclusion
This data set tells us important things about bank customers and how they act. By looking at the data and building a predictive model, banks can figure out what causes customers to leave and take steps to keep them.
             
                  #insurance
 An Overview of the Cost Analysis of Medical Insurance
The medical insurance cost dataset has information about patients, like their age, gender, body mass index, number of children, whether or not they smoke, where they live, and how much they pay for their insurance. The goal of this analysis is to find out how the different factors affect the cost of health insurance and how they relate to each other.

Data Exploration
First, I loaded the dataset and used the data.head() and data.tail() functions to look through it.This showed a  few rows from the beginning and end of the dataset to get a general idea of what it was about.I  also used data.describe() to get a statistical summary of the dataset's numeric variables.

Next,  data.isnull().sum() is used to see if there were any missing values. There are no missing values in the dataset.

Then,Ie used the sns.heatmap() function to make a heatmap to see how the different variables were related. This made it easy to see at a glance how the different variables were linked. We can see  e saw that there was a strong link between smoking and higher insurance costs.

Data Visualization
We use different ways to show data to figure out how different factors affect insurance costs and how they relate to each other.

First, I used a boxplot to see how age and sex related to each other. This lets us see how the ages of the men and women were spread out.

Next, we use a histogram to see how the ages of the patients in the dataset were spread out. This can help us figure out what age group had the most patients.

I also used a scatter plot to see how the number of children affected the cost of insurance. This gives us a chance to see if the two things have anything in common.

Linear Regression
Finally I used linear regression to figure out how much insurance would cost for each age. I  split the dataset into a training set and a testing set, and  trained the linear regression model with the training set. Then, used the testing set to check how well the model worked.

Conclusion
The medical insurance cost dataset tells us a lot about the things that affect how much medical insurance costs. By using different ways to display data and linear regression to look at the dataset, we were able to learn more about the relationships between the different variables and how they affect insurance costs. Insurance companies and policymakers can use this analysis to make smart decisions about how much health insurance costs.
