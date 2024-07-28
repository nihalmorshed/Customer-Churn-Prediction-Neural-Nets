# Bank Customer Churn Prediction Using Neural Networks

This project aims to predict bank customer churn using an Artificial Neural Network (ANN). The model is built to classify whether a customer will exit the bank (churn) or stay based on various customer attributes.

## Dataset Description

The dataset contains information about bank customers, including:
- `CreditScore`: Customer's credit score
- `Geography`: Customer's location
- `Gender`: Customer's gender
- `Age`: Customer's age
- `Tenure`: Number of years the customer has been with the bank
- `Balance`: Account balance
- `NumOfProducts`: Number of products held by the customer
- `HasCrCard`: Whether the customer has a credit card (1: Yes, 0: No)
- `IsActiveMember`: Whether the customer is an active member (1: Yes, 0: No)
- `EstimatedSalary`: Estimated salary of the customer
- `Exited`: Whether the customer has exited the bank (1: Yes, 0: No)

## Project Structure

### Part 1 - Data Preprocessing

1. **Importing the libraries**: Import necessary libraries for data manipulation and model building.
2. **Importing the dataset**: Load the dataset into the environment.
3. **Encoding categorical data**: Convert categorical variables into numerical format.
4. **Splitting the dataset into the Training set and Test set**: Split the data for training and testing purposes.
5. **Feature Scaling**: Normalize the data to ensure better performance of the ANN.

### Part 2 - Building the ANN

1. **Initializing the ANN**: Set up the sequence of layers for the ANN.
2. **Adding the first hidden layer**: Add the first hidden layer along with the input layer.
3. **Adding the second hidden layer**: Add the second hidden layer.
4. **Adding the output layer**: Add the output layer for binary classification.

### Part 3 - Training the ANN

1. **Compiling the ANN**: Compile the model using an appropriate loss function and optimizer.
2. **Training the ANN on the Training set**: Train the model using the training dataset.

### Part 4 - Making the predictions and evaluating the model

1. **Predicting the result of a single observation**: Predict the churn status for a single observation.
2. **Predicting the Test set results**: Use the model to predict churn status on the test set.
3. **Making the Confusion Matrix**: Evaluate the model performance using a confusion matrix.

## Model Performance

The ANN model demonstrates an accuracy of **86.4%**. This is a notable performance considering the following factors:
- **Simplicity**: The model consists of only two dense layers, making it relatively simple.
- **Complexity of Data**: Customer churn prediction is influenced by various factors, and the model effectively captures many of these with the given architecture.
- **Feature Representation**: Limited feature engineering and representation might have affected the accuracy, but the model still performs well with basic preprocessing steps.

## Conclusion

This project showcases the implementation of an Artificial Neural Network for predicting bank customer churn. With further enhancements and more complex architectures, the model's performance can potentially be improved.

## How to Run

1. Clone the repository.
2. Install the required libraries from `requirements.txt`.
3. Run the Jupyter notebook to preprocess data, build, train, and evaluate the ANN model.

---
