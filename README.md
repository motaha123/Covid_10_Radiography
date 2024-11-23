# Covid_10_Radiography
COVID-19 Chest X-Ray Classification with MobileNetV2
This repository contains a complete pipeline for classifying chest X-ray images into four categories: COVID-19, Lung Opacity, Viral Pneumonia, and Normal, using MobileNetV2 with transfer learning. The project includes dataset preprocessing, model training, evaluation, and 


visualization of results.
Features

Data Preprocessing:
 Resizes X-ray images to 150x150 pixels.
 Normalizes image pixel values for improved model performance.
 One-hot encodes class labels for multi-class classification.
 Splits the dataset into training and testing sets.

Data Augmentation:
 Dynamically applies transformations like rotation, zoom, and horizontal flipping to improve generalization.


Transfer Learning:
  Utilizes the pre-trained MobileNetV2 model with frozen base layers to extract meaningful features.
  Fine-tunes the model for COVID-19 X-ray classification.

Visualization:
  Displays random images and their labels from the dataset.
  Plots training and validation accuracy/loss over epochs.
  Displays a confusion matrix for evaluating per-class performance.
  
Evaluation Metrics:
  Computes overall accuracy, per-class accuracy, and classification report.
  Provides detailed insights into the model’s performance across all classes.
