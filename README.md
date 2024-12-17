# Defect Detection in Quality Control Using CNN

This project aims to automate defect detection in part manufacturing using a Convolutional Neural Network (CNN).
The goal is to reduce human error, improve accuracy, and enhance the efficiency of the quality control process by classifying parts as defective or OK based on images.

Project Overview:
The project involves building and training a CNN model to analyze images of manufactured parts. The model is designed to detect defects automatically, providing real-time insights for quality control in manufacturing. This system helps minimize manual inspection errors and improves the overall quality assurance process.

Key Features:
Automated Defect Detection: Identifies defects in manufactured parts using deep learning.
Real-Time Classification: A Flask web app for real-time defect detection, enabling seamless deployment and inference.
Image Dataset: Includes labeled images of defective and non-defective parts for model training and testing.
Model Architecture:
The project uses a Convolutional Neural Network (CNN) for image classification. The CNN is designed to learn features from images of parts and classify them as either "defective" or "OK." The model is trained on the provided dataset and optimized for high accuracy in defect detection.

Dataset:
Images: The dataset consists of images of parts, both defective and non-defective.
Preprocessing: Images are preprocessed by resizing and normalizing for CNN training.
Technologies Used:
Python: The main programming language used for data processing and model development.
TensorFlow/Keras: Frameworks used for building and training the CNN model.
OpenCV: Used for image processing and augmentation.
Flask: Web framework for deploying the trained model for real-time defect detection.
