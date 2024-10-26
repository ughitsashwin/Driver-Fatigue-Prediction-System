# Driver-Fatigue-Prediction-System
This project focuses on developing a machine learning system to detect driver drowsiness using facial recognition techniques. Drowsiness is a significant contributor to road accidents, particularly in the taxi industry, and this system aims to improve safety by identifying signs of fatigue in drivers.

# Detecting Drowsiness in Drivers Using Machine Learning

## Overview

This project focuses on developing a machine learning system to detect driver drowsiness using facial recognition techniques. Drowsiness is a significant contributor to road accidents, particularly in the taxi industry, and this system aims to improve safety by identifying signs of fatigue in drivers.

## Features

- **Facial Recognition:** Utilizes images of drivers' faces to detect drowsiness through specific facial actions, including open eyes, closed eyes, yawning, and no yawning.
- **Machine Learning Algorithms:** Implements various machine learning models, including Logistic Regression, Support Vector Machine (SVM), and deep learning techniques such as Convolutional Neural Networks (CNN) using TensorFlow.
- **Real-time Detection:** Aims to provide real-time detection capabilities that can be integrated into existing vehicle systems for immediate alerts.

## Technologies Used

- **Programming Language:** Python
- **Libraries:** TensorFlow, Keras, Scikit-learn, NumPy, Matplotlib
- **Development Environment:** Jupyter Notebook
- **Dataset:** Publicly sourced facial image dataset from Kaggle

## Methodology

1. **Data Collection:** Images are categorized into four groups based on facial expressions relevant to drowsiness detection.
2. **Data Preprocessing:** Images are cleaned and processed to focus on facial structures, with the background removed for enhanced model training.
3. **Model Training:** Different machine learning algorithms are trained on the processed data to classify the facial expressions accurately.
4. **Evaluation:** The models are evaluated using confusion matrices and classification reports to determine accuracy and reliability.

## Results

- Achieved an accuracy of **83.04%** using a deep learning model.
- The SVM model showed the highest accuracy of **92.38%**, indicating its effectiveness in classifying drowsiness levels based on facial features.

## Future Work

Future enhancements may include integrating real-time monitoring systems that continuously assess driver fatigue and provide timely alerts, further reducing the risk of accidents caused by drowsiness.

