## "Predicting acceptance of a coupon recommendation"
This project aims to predict whether a person will accept the coupon recommended to him/her in different driving scenarios

Data Source
*   https://archive.ics.uci.edu/ml/datasets/in-vehicle+coupon+recommendation
*   Tong Wang, tong-wang '@' uiowa.edu, University of Iowa
*   Cynthia Rudin, cynthia '@' cs.duke.edu, Duke University

Methodology

The project uses of Linear regression analysis models to predict whether or not a driver will accept a coupon recommended to them. Specifically, we used the following techniques:

decision trees, bagged trees and Random forest models, to create models that predict the coupon recommendations.

Results

Our model was able to predict wether or not a driver will accept a coupon with a Root Mean Absolute Error of 57%.

Therefore my model would be useful in production, this is an algorithm that is used for both regression and classification tasks. The model works by breaking down a dataset into smaller subsets based on the features of the data, ultimately creating a tree-like structure of decisions that leads to a prediction.
it can be used as:-

Prepare the data: The first step is to prepare the data by cleaning and transforming it into a format that can be used by the model. This may involve removing missing values, scaling the data, and encoding categorical variables.

Split the data: Next, split the data into training and testing sets. The training set will be used to train the decision tree model, while the testing set will be used to evaluate the performance of the model.

Train the model: Train the decision tree model on the training set. The model will recursively split the data based on the features that are most informative, creating a tree-like structure of decisions.

Evaluate the model: Use the testing set to evaluate the performance of the model. This can be done by calculating various metrics such as accuracy, precision, recall, and F1 score.

Tune the model: If the performance of the model is not satisfactory, you may need to tune the hyperparameters of the model to improve its performance. This can be done through techniques such as cross-validation and grid search.

Make predictions: Once you are satisfied with the performance of the model, you can use it to make predictions on new data.

![image](https://user-images.githubusercontent.com/124377057/230792226-ffae9e77-653f-4aad-a95c-76a4aa330ed1.png)

![image](https://user-images.githubusercontent.com/124377057/230792250-7ac63986-e689-4797-88e7-4b49a14e9cf7.png)


The Model;

The linear regression model is a statistical method used to model the relationship between a dependent variable and one or more independent variables. Its purpose is to predict the value of the dependent variable based on the values of the independent variables. To create a linear regression model, we first collect data on the dependent variable and one or more independent variables. We then fit a line to the data using a method called least squares regression. This line represents the relationship between the dependent variable and the independent variables, and can be used to make predictions about the dependent variable.

Root Mean Squared Error (RMSE) is a commonly used evaluation metric in machine learning to measure the accuracy of a regression model. RMSE measures the difference between the predicted values of a model and the actual values of the target variable.

To calculate RMSE, the difference between the predicted values and the actual values is first squared, and then the mean of these squared differences is taken. Finally, the square root of this mean value is computed to obtain the RMSE.

Limitations;

Linear models rely on certain assumptions, such as linearity, independence, homoscedasticity, and normality of residuals. These assumptions may not hold in all cases, which can limit the applicability of the model. in this case the model was Underfitting both the training and test data, underfitting brings a high bias, leading to poor performance.


For further information;

For any additional questions, please contact email oruka.rapha01@gmail.com
