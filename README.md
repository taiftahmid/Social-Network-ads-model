# Social Network ads model
A logistic Regression Model for predicting the key audiences to show ads in a social network. 

The dataset has the following features:
- User ID

- Gender
- Age

- Estimated Salary

- Purchased 

Using these features, the model predicts which audiences the ads will be relevant to. 

The feature dimensionality reduction was also done using Kernel PCA to increase the accuracy of the model

# Results and Discussion:

![alt text](https://github.com/taiftahmid/Social-Network-ads-model/blob/master/social-network-prediction.png)

The green portion represents the users who bought the product viewed in the ads and the red portion represents the users who didn't. This model has learned the optimum line that seperates users who are prone to buying the product. 

For any new user, the model will simply check the position of the new user in the graph and predict whether the user is a key customer or not. 

The following figure shows the predictions made by the model from new users. (Test Set)

![alt text](https://github.com/taiftahmid/Social-Network-ads-model/blob/master/social-network-prediction-testset.png)

The accuracy of the model was 90%
