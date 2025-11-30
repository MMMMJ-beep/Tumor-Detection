# Tumor-Detection
The project is a Brain Tumor Detection System: it takes as input an MRI image of a brain and outputs a prediction whether there is a tumor or no tumor
Software installation: Python version, required libraries (tensorflow, numpy, matplotlib)

Data download instructions: MRI dataset link https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset

How to Download :

Go to the Kaggle dataset link above.
Sign in or create a free Kaggle account if you don't have one.
Click the "Download" button to download the dataset as a ZIP file.
Extract the ZIP file to a local folder on your computer.
In the project or Colab notebook, set the path to the dataset folder.
Notebook Workflow / Project Steps
The notebook is organized in the following sections:

Imports Libraries & Tools

Importing all necessary Python libraries such as TensorFlow, NumPy, Matplotlib, OpenCV, etc.
Load Dataset

Loading the MRI dataset from the local directory or Google Drive.
Data Visualization

Visualizing sample MRI images and checking class distribution.
Image Preprocessing

Resizing, normalization, and augmentation of images for model training.
What is Transfer Learning

Explanation of transfer learning and its benefits in MRI image classification.
Model Building (Implementation)

Building the CNN or Transfer Learning model architecture.
Data Preprocessing Implementation

Applying preprocessing steps on the dataset to make it ready for training.
Train & Validation Plots

Plotting training and validation accuracy/loss graphs.
Classification Report

Evaluating model performance with precision, recall, and F1-score.
Confusion Matrix

Displaying confusion matrix to analyze classification results.
MRI Image Detection System

Using the trained model to predict tumor presence and type on new MRI images.
