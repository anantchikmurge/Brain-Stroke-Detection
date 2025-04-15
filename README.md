Early Brain Stroke Detection Using Deep Learning

This project focuses on the early detection of brain strokes using deep learning techniques applied to CT scan images. Stroke is a major cause of disability and death globally, and early diagnosis is critical for effective treatment. Traditional diagnosis methods are time-consuming and may be prone to human error. This project aims to provide a faster and more accurate solution using AI.

Project Objective:

 -Automate the detection of brain strokes from CT scan images
 -Improve accuracy and speed of diagnosis using deep learning
 -Assist radiologists in clinical decision-making with AI support

Models Used:
  ConvNeXt
  Swin Transformer
  ResNet-50
  DenseNet

Among these models, DenseNet delivered the highest accuracy at 99.20 percent. All models achieved high performance, with accuracies ranging from 90 percent to 99.20 percent.

Dataset:
Binary classification: Normal vs Stroke
Input: CT scan images
Preprocessing included image resizing, normalization, and data augmentation

Note: Due to privacy constraints, the dataset is not publicly included. A similar open-source dataset can be used for testing and experimentation.

Accuracy Results:
   ConvNeXt - 90.00 percent
   Swin Transformer - 94.50 percent
   ResNet-50 - 97.30 percent
   DenseNet - 99.20 percent

Technologies Used:
  Python
  TensorFlow / PyTorch
  OpenCV
  NumPy
  Matplotlib / Seaborn

Project Folder Structure:

dataset - contains CT scan images (not included here)
models - training scripts for each model
utils - utility functions for preprocessing and evaluation
results - graphs and model performance metrics
main.py - main script to run the models
README.txt - project overview and documentation
requirements.txt - list of required Python libraries

Future Scope:
-Use larger and more diverse datasets for better generalization.
-Improve real-time processing capabilities.
-Develop a clinical application for hospital use.


Author Details:

Author: Anant Chikmurge
Email: anantchikmurge2003@gmail.com
Institution: Presidency University, Bengaluru, India