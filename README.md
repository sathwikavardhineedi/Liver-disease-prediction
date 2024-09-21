# Liver Disease Prediction Using Autoencoders

## Overview
This project aims to predict liver diseases using autoencoders, a deep learning technique for anomaly detection and feature extraction. By leveraging medical data, the model focuses on identifying significant patterns that can distinguish between healthy and diseased liver conditions. The use of autoencoders helps in reducing the dimensionality of the data, improving both accuracy and performance in liver disease prediction.

## Key Features
- **Autoencoder-based approach**: Reduces data dimensionality and captures important features.
- **Early detection**: Enables early diagnosis of liver diseases, aiding timely medical interventions.
- **Data-driven analysis**: Uses real-world medical data for training and evaluation.

## Dataset
The dataset used includes liver-related medical parameters such as:
- Age
- Gender
- Total Bilirubin
- Direct Bilirubin
- Alkaline Phosphotase
- Alamine Aminotransferase
- Aspartate Aminotransferase
- Total Proteins
- Albumin
- A/G Ratio

This data is used to train the autoencoder for detecting abnormalities in liver function.

## Model Overview
- **Autoencoder architecture**: Consists of an encoder that compresses the input data and a decoder that reconstructs it.
- The model is trained to minimize reconstruction errors, which helps in identifying liver disease patterns.
  
## Results
The autoencoder was able to successfully highlight significant features in the data, leading to accurate predictions of liver conditions. Further refinements can improve its potential for medical applications.
