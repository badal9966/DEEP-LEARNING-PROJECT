# Task 2: DEEP-LEARNING-PROJECT
*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: BADAL SAHU

*INTERN ID*: CT04DF1810

*DOMAIN*: Data Science

*BATCH DURATION*: Jun 5th, 2025 to July 5th, 2025

*MENTOR NAME*: NEELA SANTHOSH

DESCRIPTION OF TASK

This task is part of the CODTECH Data Science Internship.

## 📌 Objective

Build and train a deep learning model to classify handwritten digits from the *MNIST dataset* using *TensorFlow*.

## 🧠 Model Overview

- Dataset: *MNIST* (60,000 training + 10,000 testing images)
- Each image: 28x28 grayscale digit
- Total classes: 10 (digits 0–9)

### 🔧 Model Architecture

| Layer             | Details                             |
|------------------|-------------------------------------|
| Flatten           | Converts 28x28 to 784               |
| Dense             | 128 neurons, ReLU activation        |
| Dropout           | 20% dropout to prevent overfitting  |
| Dense (Output)    | 10 neurons, Softmax activation      |

### 🧪 Training Details

- Optimizer: *Adam*
- Loss: *Sparse Categorical Crossentropy*
- Epochs: *5*
- Validation Split: *10%* from training data

## 📈 Results

Training and validation accuracy are plotted using matplotlib after training. You should see the model converging quickly with ~98% train accuracy.

## 🚀 How to Run

### 🔧 Install Requirements

bash
pip install tensorflow matplotlib

## OUTPUT
![Image](https://github.com/user-attachments/assets/03ea983d-bc8b-4a25-9d8a-76606f012243)

