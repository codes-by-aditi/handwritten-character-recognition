# Handwritten Character Recognition using TensorFlow

An academic deep learning project that focuses on recognizing handwritten text from images using **TensorFlow**.  
The system takes images containing handwritten words or text lines and predicts the corresponding textual output.

This project was developed for **learning and experimentation purposes** to understand how modern neural networks can be applied to handwritten text recognition tasks.

---

## 📌 Project Overview

Handwritten Character Recognition (HCR) is an important problem in computer vision and pattern recognition.  
In this project, a neural network-based approach is used to convert handwritten text images into machine-readable text.

The model is designed to work with:
- Images containing **single handwritten words**
- Images containing **multiple words in a text line**

---

## 🧠 Learning Objectives

- Understand the basics of handwritten text recognition systems  
- Learn how CNN and RNN models work together for sequence prediction  
- Explore **CTC loss and decoding** for text recognition  
- Gain hands-on experience with TensorFlow-based deep learning models  

---

## 🏗 Model Architecture (High-Level)

The recognition model is built using a combination of:

- **Convolutional Neural Networks (CNNs)** for feature extraction  
- **Recurrent Neural Networks (LSTMs)** for sequence learning  
- **CTC (Connectionist Temporal Classification)** for loss calculation and decoding  

This architecture allows the model to process variable-length text sequences efficiently.

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
in Historical Documents](https://repositum.tuwien.ac.at/obvutwhs/download/pdf/2874742) * [Scheidl - Word Beam Search: A Connectionist Temporal Classification Decoding Algorithm](https://repositum.tuwien.ac.at/obvutwoa/download/pdf/2774578)
