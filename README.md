# Tmnist-Dataset-94Characters--Prediction

## Overview
This project focuses on classifying characters from the TMNIST dataset, which includes 94 unique character classes. The dataset consists of:

1. Font Name: Represents the font style (e.g., Chivo-Italic, Sen-Bold).
2. Label: A number between 0-9 representing the class.
3. Pixel Values: 784 grayscale pixel values (ranging from 0-255) for a 28x28 pixel image.

## Project Structure
The project is organized into the following main steps:

1. Dataset Linking
- Using the Kaggle API to download and set up the TMNIST dataset.

2. Importing Required Libraries
- Loading essential libraries for data handling, visualization, and building the model.
3. Data Preparation
- Reading the dataset into a Pandas DataFrame.
- Displaying statistics: number of rows, columns, classes, and unique fonts.
- Visualizing sample images with their class labels for better understanding.
4. Data Splitting
- Dividing the data into training and test sets for model evaluation.
5. Normalization
- Scaling pixel values to a range of 0 to 1 for improved neural network performance.
6. One-Hot Encoding
- Encoding class labels to a binary format suitable for deep learning models.
7. Reshaping
- Converting image data to a standardized 28x28 pixel format.
8. Model Building
- Constructing a neural network using the Keras Sequential API.
- The model includes dense layers with ReLU activations and a softmax output layer.
9. Model Training
Training the model with:
- a. Epochs: 20
- b. Batch Size: 1024
- c. Optimizer: Adam
- d. Loss Function: Categorical cross-entropy
10. Model Evaluation
- Calculating test accuracy and loss to assess model performance.
11. Visualization
- Plotting training and validation accuracy and loss to monitor the model's learning.
12. Conclusion
- Summarizing key findings and potential areas for future work.

## Key Results
- Final Test Accuracy: ~91.33%
- Final Test Loss: ~0.362
  
## Technologies Used
- Python: Primary language for the project.
- Pandas: Data manipulation and analysis.
- NumPy: Efficient numerical computations.
- Matplotlib: Data visualization.
- Scikit-Learn: Data preprocessing (train-test split, one-hot encoding).
- TensorFlow/Keras: Model development and training.


