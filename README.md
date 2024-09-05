# Bone_Layer_Classification

# Bone Layer Classification with LSTM

## Introduction
Bone layer classification is a crucial task in medical procedures involving drilling, such as orthopedic surgeries and dental implants. Accurate identification of bone layers—Periosteum, First Cortical, and Spongy—is essential to ensure precision and safety during these procedures. In this project, we explore the use of Long Short-Term Memory (LSTM) networks, a type of deep learning model particularly well-suited for sequential data, to classify bone layers based on vibration data collected during drilling operations.

## Dataset
The dataset used in this project is provided by Caesarendra et al. (2024) and is detailed in their research paper titled "Bone Drilling Vibration Signal Classification Using Convolutional Neural Network to Determine Bone Layers" (10.1007/978-981-97-1463-6_40). The dataset consists of vibration signals captured during the bone drilling process, with labels indicating the bone layer.

## Understanding the Problem
During drilling, different bone layers exhibit unique vibration signatures. By analyzing these vibrations, we aim to classify the bone layers. The dataset consists of the following features:

- **Layer**: The type of bone layer (Periosteum, First Cortical, Spongy)
- **Time**: Time of data recording
- **X-axis Vibration**: Vibration data along the X-axis
- **Y-axis Vibration**: Vibration data along the Y-axis
- **Z-axis Vibration**: Vibration data along the Z-axis

## Usage
- **Data Loading**: Load the dataset and preprocess it.
- **Model Training**: Train the LSTM network using the preprocessed data.
- **Evaluation**: Evaluate the performance of the LSTM model in classifying bone layers.

## Requirements
- Python 3
- TensorFlow
- Pandas
- NumPy
- Scikit-learn
