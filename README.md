# Car-Image-Classification-Using-PySpark-and-TensorFlow
This contains a project that performs image classification on a dataset of car images categorized by manufacturer. The project uses PySpark for scalable data processing and TensorFlow/Keras for building a deep learning model to classify the car images.

Table of Contents
Overview
Project Structure
Methodology
Features
Installation
Usage
Technologies
Future Work
Contributing

Overview
The project focuses on classifying car images into categories based on manufacturers (e.g., Mazda, Nissan, Toyota, etc.). The images are processed and categorized using PySpark for large-scale data handling, and TensorFlow/Keras is used to build a neural network model for image classification. The dataset is split into training, validation, and test sets for model evaluation.

Methodology
Data Loading: Images are loaded from a local dataset, and the file paths are stored in a PySpark DataFrame for scalable processing.
Data Splitting: The dataset is split into three sets: 70% for training, 15% for validation, and 15% for testing.
Feature Extraction: Image features are extracted using TensorFlow’s load_img and img_to_array functions.
Model Training: A neural network model is built using TensorFlow/Keras to classify the car images into different manufacturer categories.
Evaluation: The trained model is evaluated using the validation and test sets.

Features
Scalable data handling using PySpark.
Image feature extraction using TensorFlow.
Neural network model for multi-class classification of car images.
Dataset split into training, validation, and test sets.

Technologies
Python
PySpark
TensorFlow/Keras
OpenCV
Jupyter Notebook

Future Work
Improve the model by experimenting with more advanced architectures like CNNs or ResNet.
Use a larger and more diverse dataset for better classification accuracy.
Implement a real-time classification pipeline where new images can be classified automatically.
