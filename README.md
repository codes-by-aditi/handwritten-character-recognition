# Handwritten Character Recognition using TensorFlow

An academic deep learning project focused on recognizing handwritten text from images using **TensorFlow**.  
The system converts handwritten words or text lines into machine-readable text using neural network-based models.

This project was developed for **learning and experimentation purposes** to understand how handwritten text recognition systems work in practice.

---

## 📌 Project Overview

Handwritten Character Recognition (HCR) is a key problem in computer vision and pattern recognition.  
In this project, a deep learning-based approach is used to process images containing handwritten text and predict the corresponding textual output.

The model supports:
- Recognition of **single handwritten words**
- Recognition of **multiple words in a text line**

---

## 🎯 Learning Objectives

- Understand the fundamentals of handwritten text recognition  
- Learn how **CNN and RNN models** are combined for sequence prediction  
- Explore **CTC loss and decoding** techniques  
- Gain hands-on experience with TensorFlow-based deep learning workflows  

---

## 🏗 Model Architecture (High-Level)

The system is built using a hybrid neural network architecture consisting of:

- **Convolutional Neural Networks (CNNs)** for feature extraction from images  
- **Recurrent Neural Networks (LSTMs)** for sequence learning  
- **CTC (Connectionist Temporal Classification)** for loss computation and decoding  

This design enables the model to handle variable-length text sequences efficiently.

---

## 📂 Project Structure

handwritten-character-recognition/
│── data/
│── model/
│── src/
│── doc/
│── README.md


---

## ⚙️ Running the Demo (Inference)

1. Clone the repository:
   ```bash
   git clone https://github.com/codes-by-aditi/CodeAlpha_HandwrittenCharacterRecognition.git


Navigate to the project directory:

cd handwritten-character-recognition


Place a pretrained model inside the model directory.

Go to the source folder:

cd src


Run inference on a sample image:

python main.py


To test with a custom image:

python main.py --img_file path/to/image.png
