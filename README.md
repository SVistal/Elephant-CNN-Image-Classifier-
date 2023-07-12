# Image Classification with Convolutional Neural Networks (CNN)
This project demonstrates the process of building a Convolutional Neural Network (CNN) model for image classification using TensorFlow and Keras. The goal of the project is to train a model that can accurately classify images of African and Asian Elephants into different categories. It uses a Kaggle dataset.

## Project Overview
The project consists of the following major steps:

Data Preprocessing: The training data is loaded and preprocessed using TensorFlow's image_dataset_from_directory function. The images are scaled between 0 and 1 to normalize the data. The data is split into training and validation sets.

Model Architecture: The CNN model is defined using the Sequential API provided by Keras. It includes multiple Conv2D layers for feature extraction, MaxPooling2D layers for down-sampling, and Dense layers for classification. The final layer uses the sigmoid activation function for binary classification.

Model Training: The model is compiled with the Adam optimizer, binary cross-entropy loss, and accuracy metric. It is then trained on the training data using the fit method. The training progress is recorded and can be visualized.

Model Evaluation: After training, the model is evaluated on the test data using the evaluate method. Metrics such as test loss, test accuracy, precision, recall, and binary accuracy are calculated and displayed.

Visualization: The project includes visualizations to analyze the model's performance. The evaluation results are plotted, and the training history is visualized using line plots to track the loss and accuracy metrics over epochs.
