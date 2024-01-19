# Costumer-Churn-Prediction
Customer churn, the phenomenon of customers switching from one service 
provider to another, is a critical challenge in the highly competitive 
telecommunications industry. Predicting customer churn is of paramount 
importance as it allows companies to take proactive measures to retain 
valuable customers. In this study, we employ Artificial Neural Networks 
(ANNs) as a predictive model to forecast customer churn for a telecom 
company. 

In today's fast-paced and highly competitive telecommunications industry, customer retention 
is paramount. Telecom companies invest substantial resources to acquire and maintain a 
customer base. However, the phenomenon of customer churn, where subscribers switch from 
one service provider to another, presents a significant challenge. Losing valuable customers 
can result in revenue loss and increased operational costs. 

To address this challenge, the use of advanced data analytics and predictive modeling 
techniques has become increasingly crucial. This project focuses on the application of Artificial 
Neural Networks (ANNs) to predict customer churn for a telecom company. 

The Model has 2 hidden layers, 1 input layers and 1 output later. 
The input layer has 19 neurons as we have 19 independent variables in the dataset. 
And 2 hidden layers with 12 neurons whose number is determined by repetative 
experimentation to achieve the maximum accuracy. 

And have 1 output layer with 1 neuron as we are using for this for classification 
problem that has only 2 possible outputs.

 The hidden layers works on ReLU activation function. The Rectified Linear Unit 
(ReLU) is a widely used activation function in neural networks. It introduces non-linearity by outputting the input directly if it's positive, otherwise, it outputs zero. 

And we used ADAM optimizer for the model and Binary Cross Entropy for loss 
evaluation. 

Adam optimizer is a stochastic gradient descent (SGD) optimizer that is based on 
adaptive estimation of first-order and second-order moments. It is one of the most 
popular optimizers in machine learning due to its efficiency and effectiveness.

Binary cross entropy (BCE) is a loss function used to train models for binary 
classification tasks. It measures the difference between the predicted probabilities and 
the actual labels. 

Accuracy metrics measure the performance of machine learning models by evaluating 
how well they can predict the correct output for a given input.
