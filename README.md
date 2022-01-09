# ANN-customer-churn
Customer Churn prediction using Artificial Neural Network (ANN)

( To run the code in your local system:
  1. Download the entire repository in a zip file and export to a folder.
  2. Copy the file path of the dataset(.csv file).
  3. Go to the code. Find the line which is similar to the line given below,
        dataset = pd.read_csv('**drive/MyDrive/Colab Notebooks/ANN/Churn_Modelling.csv**'
  4. Replace the bold section with the file path in the code)

Churn Prediction is a common use case in Machine Learning and Deep Learning domain.
It is very important for the bank to know "why" and "when" a customer will leave the bank.
It has been a key area of business development in the banking industry.

The dataset has 14 input parameters, out of which 11 are important and 1 output parameter, i.e. "Exited" or "Not Exited"
An Artificial Neural Network with 2 hidden layers is used to predict the Churn Customers.

ReLu activation function is used, as it most suited for the hidden layers due to it's efficiency in handling Vanishing Gradient and Exploding Gradient problems.

The output layer consists of Sigmoid since it is a Binary Classification problem.
