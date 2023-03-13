# "Predicting Food Sales"


This project aims to predict food sales for a restaurant based on historical sales data. The project uses machine learning algorithms to analyze sales patterns and forecast future sales.

**Data Source**


The data used in this project was obtained from the restaurant's point of sale system. It includes information such as the Item_Fat_Content, the Outlet_Location_Type, the Outlet_Type, the Item_Outlet_Sales and the Outlet_Establishment_Year.

**Methodology**


The project uses of regression analysis to predict future sales. Specifically, we used the following techniques:

Linear regression, to model the relationship between sales and various factors such as Item_Fat_Content, Outlet_Location_Type, and Outlet_Type.

**Results**


Our model was able to accurately predict food sales with an accuracy of 69.49%. We also identified several key factors that influence sales, such as the Item_Fat_Content and the Outlet_Location_Type and Outlet_Type


![image](https://user-images.githubusercontent.com/124377057/224627744-80e0aba3-bb2b-4339-8b6e-7787d27a7d62.png)
There are more sales received from the sale of regular items compared to the low fat items.


![image](https://user-images.githubusercontent.com/124377057/224628598-7b5389c8-4148-4b38-8c25-f132123cbd04.png)
Performance of each outlet type of the restaurant


**Model**
The linear regression model is a statistical method used to model the relationship between a dependent variable and one or more independent variables. Its purpose is to predict the value of the dependent variable based on the values of the independent variables.
To create a linear regression model, we first collect data on the dependent variable and one or more independent variables. We then fit a line to the data using a method called least squares regression. This line represents the relationship between the dependent variable and the independent variables, and can be used to make predictions about the dependent variable.

The R2 evaluation metric, also known as the coefficient of determination, is a measure of how well the linear regression model fits the data. It represents the proportion of variance in the dependent variable that can be explained by the independent variables. A higher R2 value indicates a better fit between the model and the data.
In this case an R2 value of 0.069 means that 80% of the variation in the dependent variable can be explained by the independent variables. This indicates a strong relationship between the variables and suggests that the model is a good fit for the data.
