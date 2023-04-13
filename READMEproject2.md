## "Predicting acceptance of a coupon recommendation"
This project aims to predict whether a person will accept the coupon recommended to him/her in different driving scenarios

Data Source
*   https://archive.ics.uci.edu/ml/datasets/in-vehicle+coupon+recommendation
*   Tong Wang, tong-wang '@' uiowa.edu, University of Iowa
*   Cynthia Rudin, cynthia '@' cs.duke.edu, Duke University

Methodology

The project uses the Classification models to predict whether or not a driver will accept a coupon recommended to them. Specifically, we used the following techniques:

decision tree classifier, KNeighbors Classifier, Bagging Classifier and Random Forest Classifier, to create models that predict the coupon recommendations.

**Results**

- The F1 score is a metric that measures the balance between precision and recall for a binary classification problem such as the one we are dealing with, It is often used as a performance metric for machine learning models.

- For our binary classification problem, we achieved an F1 score of 0.72 for the negative class and an F1 score of 0.80 for the positive class.

- The F1 score ranges from 0 to 1, where a score of 1 represents perfect precision and recall, and a score of 0 represents the worst possible performance. Therefore, our model performed reasonably well for both classes, with a higher score for the positive class.

Therefore the model would be useful in production, this is an algorithm that is used for  classification tasks. 

The model can be used in the following ways:-

Prepare the data: The first step is to prepare the data by cleaning and transforming it into a format that can be used by the model. This may involve removing missing values, scaling the data, and encoding categorical variables.

Split the data: Next, split the data into training and testing sets. The training set will be used to train the classification model, while the testing set will be used to evaluate the performance of the model.

Train the model: Train the classifier models on the training set. 

Evaluate the model: Use the testing set to evaluate the performance of the model. This can be done by calculating various metrics such as accuracy, precision, recall, and F1 score.

Tune the model: If the performance of the model is not satisfactory, you may need to tune the hyperparameters of the model to improve its performance. This can be done through techniques such as cross-validation and grid search.

Make predictions: Once you are satisfied with the performance of the model, you can use it to make predictions on new data.

![image](https://user-images.githubusercontent.com/124377057/230792226-ffae9e77-653f-4aad-a95c-76a4aa330ed1.png)

![image](https://user-images.githubusercontent.com/124377057/230792250-7ac63986-e689-4797-88e7-4b49a14e9cf7.png)


The Model;

Random Forest Classifier is a popular machine learning algorithm used for classification tasks. It is an ensemble learning method that combines multiple decision trees to make predictions.

Each decision tree in a Random Forest is trained on a random subset of the training data and a random subset of the input features. This helps to reduce overfitting and increase the diversity of the individual trees. The final prediction is made by combining the predictions of all the trees in the forest.

The algorithm is suitable for both binary and multiclass classification problems and can handle both categorical and numerical data. It is also capable of handling missing values and can be used for feature selection.

Overall, Random Forest Classifier is a powerful and versatile algorithm that is widely used in machine learning for its high accuracy and robustness.

**Limitations;**

- Interpretability: Random Forest Classifier is not as interpretable as some other algorithms like decision trees. It can be difficult to understand which features are important for making predictions.

- Memory and Computation: Random Forest Classifier can require a lot of memory and computation, especially when the number of trees in the forest is high or the data has a large number of features.

For further information;

For any additional questions, please contact email oruka.rapha01@gmail.com
