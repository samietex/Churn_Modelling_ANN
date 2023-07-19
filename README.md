## Churn Modeling ANN

### Project Overview

The goal of this project is to develop a prediction model using Artificial Neural Networks (ANN) to determine whether a customer will leave a bank or not. The objective is to assist in the decision-making process regarding granting loans to customers.

The rationale behind this project is that if a customer is likely to leave the bank, it may not be advisable to grant them a loan, and vice versa.

### Dataset Overview

For this project, I utilized a bank customer dataset obtained from Kaggle. The dataset includes various details such as credit scores, location, gender, age, duration of customer relationship with the bank, and account balance.

### Tasks

To achieve the project objective, I implemented an Artificial Neural Network using Python and several Python libraries, including:

* ScikitLearn
* Pandas
* Numpy
* Matplotlib.pyplot
* Keras

The Pandas library was utilized for reading and handling the dataset in CSV format, as well as for data wrangling and cleaning operations.

ScikitLearn was employed for tasks such as dataset splitting, feature scaling, and performance evaluation. However, since the focus of this project is on utilizing Artificial Intelligence, ScikitLearn was not used for building other machine learning models.

Numpy was utilized for array operations, while Matplotlib.pyplot was employed for plotting correlations and results.

Keras was used for constructing the layers of the Artificial Neural Network and building the classification model, utilizing the `Relu` and `Sigmoid` activation functions, as well as the `Adam` optimizer.
