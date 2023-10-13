# Credit_Card_default_prediction

The essence Credit Card Default prediction project is to study the data of numerous customers and build machine learning models to efficiently predict if a person is suseptible of default based on the data given. Initially, a basic understanding of the data is performed by using Exploratory Data Analysis with the help of certain visualization techniques and then any outliers or null values are handled to make the dataset well organized to perform predictions. Meanwhile VIF(Variance Inflation Factor) and a check for multicollinearity is also performed to eliminate any further dependancy of the independant variables present in the dataset. Finally, numerous machine learning models are implemented to predict the possibility of default. The main goal of this project is to study and apply classification models to better predict the outcome.


# **Problem Statement**

This project is aimed at predicting the case of customers default payments in Taiwan. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification credible or not credible clients. We can use the K-S chart to evaluate which customers will default on their credit card payments.

# **Conclusion**:
EDA Insights:



*   A majority of credit card users are non-defaulters whereas only 22% of users are defaulters.
*   According to gender, Females have defaulted more than men whereas among the non-defaulters, women are more than men.
*   Considering Marital Status, Singles have defaulted more than married people, however amongst the non-defaulters, singles are more than any of the marital categories.
*   According to payment records, for every month for which data is present there is lesser chance of default for following month if there has not been default for the previous month.
*   Higher amount of credit is given to persons having age greater than 60 Years also there are more credit card amounts taken by people lying in the age bracket of 27-40 Years.

Model Insights:


*   Of all the models implemented, Random Forest model had the highest accuracy of predictions with utmost accuracy. The accuracy of this model was 85%.
*   XG Boost model also performed well with higher accuracy. The accuracy of this model was 80%.
*   The education column was cleaned with numerical values for better predictability.
*   The marriage column was compared with a constant and then edited to enhance the prediction process.

Usefulness to Stakeholders:

*   The source of income is a mojor contributor towards ascertaining the amount of credit and the type of credit card that is being offered to an individual. Hence, these models can further be utilized to present such services to clients.
*   The credit limit can be enhanced for people aged between 41-60 as there is less possibility of default considering average income. This would push up sales of credit card.
*   The classification models can be used in the production environment to better predict the possibility of default for an individual based on the data an organization has.
*   The data and the models are a great source to apprehend the individuals who are better suited for further credit and loans which would benefit the organization.
