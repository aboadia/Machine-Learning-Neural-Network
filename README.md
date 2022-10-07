# Machine-Learning-Neural-Network

## Question 2 #1
I will use the identity activation function as my output activation function. I chose this because I want to keep my output or predicted value the same. 

## Question 2 #2
Tere should be one output neuron for regression because we are not tryoing to map inputs to a variety of class labels, but rather by predicting a single continous target value for each sample.  

## Question 2 #3

The average MSE loss for this modeel is 531.72 and its average Accuracy is 22.98.

## Question 2 #4
Plotting the loss and accuracy as a function of the number of iterations: 
![Screen Shot 2022-10-07 at 5 47 47 PM](https://user-images.githubusercontent.com/89150972/194672495-5b0f57f1-d25b-43ae-9bed-380ae5bc2c78.png)

## Question 2 # 5
Varying the learning rate from 0.2 to 0.01 results: 
When the learning rate is changed from 0.2 to 0.01, the average mse decreased from 531 to 321. The accuracy decreased as well from 22.9 to 17.1.
![Screen Shot 2022-10-07 at 5 49 15 PM](https://user-images.githubusercontent.com/89150972/194672617-67115b14-87be-4be3-b697-f6a9402ca414.png)

## Question 2 # 6
Varying the number of neurons in the hidden layer results: 
![Screen Shot 2022-10-07 at 5 52 00 PM](https://user-images.githubusercontent.com/89150972/194672833-3aff9ac1-2bdd-4110-a655-fced7846b7a6.png)
![Screen Shot 2022-10-07 at 5 53 45 PM](https://user-images.githubusercontent.com/89150972/194672936-c1176d51-1ded-4503-a0f1-f6a5b96b3212.png)


## Question 2 #7 
Trying the activation functions tanh and identity in the hidden layers in place of the signmoid function that was originally used. 
Results from using tanh activation function:
![Screen Shot 2022-10-07 at 5 56 31 PM](https://user-images.githubusercontent.com/89150972/194673160-dd5626a6-3c2b-4fe4-9209-8ebcb60a41ef.png)

Results from using identity activation function:
![Screen Shot 2022-10-07 at 5 57 39 PM](https://user-images.githubusercontent.com/89150972/194673255-a8280e28-0b64-4f66-840a-a6bdd203162e.png)

7a. I need to change the update rule.
7b. I will need to use the derivative of the new activation function chosen for the hidden layer ( ei the tanh and identity activation function chosen for this question).
7c. The final loss for using both tanh and identity activation function in hidden layer is NAN and no values were observed for their predicted values by accessing the produced graph. For identity activation function, its average MSE and average Accuracy is infinity. Tanh's average MSE and average accuracy is 880.00 and 29.468.




