## Ain Shams University - CSE485 Deep Learning

# Major Task - CNN Leaf Classification

<br>

> Before running make sure to install the required packages by the command below <br> `pip install -r requirements.txt`

## Overview

This project focuses on leaf classification using a neural network architecture, specifically a Convolutional Neural Network (CNN). The goal is to prepare the data and train a CNN model, exploring various hyperparameter settings for optimal performance.

## Part I: Data Preparation

1. **Describe the Data:**

   - Obtain the Leaf Classification dataset.
   - Provide insights into the dataset, including the number of samples, features, and target variables.

2. **Clean the Data:**

   - Address any issues related to data cleanliness, such as handling missing values or duplicates.

3. **Check for Missing Values and Duplicates:**

   - Identify and correct missing values or duplicate entries in the dataset.

4. **Visualize the Data:**

   - Utilize appropriate visualization methods to explore feature distributions and gain a deeper understanding of the dataset.

5. **Draw Images:**

   - Visualize sample images from the dataset to understand the nature of the leaf specimens.

6. **Correlation Analysis:**

   - Conduct correlation analysis to identify relationships between different features.

7. **Divide the Data:**

   - Split the dataset into training and test sets, allocating approximately 80% for training.

8. **Standardize the Data:**

   - Standardize the data by computing mean and standard deviation from the training set and applying the transformation to both training and test sets.

9. **Encode the Labels:**
   - Implement label encoding for the target variable ('species').

<br>

## Part II: Training a Neural Network (CNN)

1. **Implement a CNN Model:**

   - Develop a CNN model for leaf classification.

2. **Write Training Function:**

   - Implement the training function to train the CNN model.

3. **Explore Hyperparameter Settings:**

   Investigate the impact of various hyperparameters:

   - Batch size
   - Number of layers
   - Dropout rates
   - Optimizers (e.g., SGD, Adam, RMSProp)
   - Regularization (L2 regularization)
   - Learning rate and learning rate scheduler

4. **TensorBoard Monitoring:**

   - Utilize TensorBoard to monitor training progress and attach screenshots of training curves (accuracy) to the report.

5. **Evaluation Function:**
   - Write an evaluation function to assess the model's performance on the train/test set.

<br>
