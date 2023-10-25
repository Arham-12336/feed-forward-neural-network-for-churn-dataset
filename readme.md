 # 📈 Churn Modeling ReadMe 📉
Introduction
Welcome to the Churn Modeling project! This Python script is designed to help you understand and predict customer churn using machine learning.

 #⚙️ Code Overview
This code performs various operations on a Churn dataset:

## 📊 Data Loading and Initial Exploration 🧐

Import necessary libraries.
Load the dataset 'Churn_Modelling.csv' using pandas.
Drop irrelevant columns ('RowNumber', 'CustomerId', 'Surname').
Display the first few rows of the data.

### 📈 Data Preprocessing 🧹

Rename the 'Age' column to 'SeniorCitizen'.
Categorize 'SeniorCitizen' as 1 if age is greater than or equal to 65, else 0.
Display unique values for each column.

### 🧩 One-Hot Encoding 🔥

Perform one-hot encoding for 'Gender' and 'Geography'.
Drop the original categorical columns.
Concatenate the one-hot encoded columns.

### 🎚️ Feature Scaling 📏

Scale selected columns ('Tenure', 'CreditScore', 'EstimatedSalary', 'Balance') using Min-Max scaling.

###  🧪 Train-Test Split 🚂🛤️

Split the data into training and testing sets for building an Artificial Neural Network (ANN).

### 💡 Artificial Neural Network (ANN) 🧠

Create a neural network model with one input layer, one hidden layer, and one output layer.
Compile the model with necessary parameters (optimizer, loss function, and metrics).
Train the model on the training data for 50 epochs.
### 📊 Model Evaluation 📋

Predict churn on the test data.
Convert probability scores to binary predictions based on a threshold of 0.5.
Calculate and print a classification report showing model performance metrics.

## 🚀 Getting Started
Prerequisites 🛠️

Make sure you have Python installed, along with the required libraries. If not, use 'pip install -r requirements.txt' to install them.
Running the Code ▶️

Execute the script 'churn_modeling.py' to run the entire process.
Results 📊

Review the classification report to evaluate the model's performance.
🤖 What's Next?
Now that you have an understanding of this Churn Modeling code, you can customize it, fine-tune the model, or integrate it into your business processes to predict and reduce customer churn.

Feel free to explore and innovate with this code! 🚀🤓

Happy coding! If you have any questions or need assistance, please don't hesitate to ask. 🙋‍♂️💬
