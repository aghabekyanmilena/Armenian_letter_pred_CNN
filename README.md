# Armenian Handwritten Letter Recognition Using CNN

This project implements a Convolutional Neural Network (CNN) to recognize handwritten Armenian letters from images.
It leverages TensorFlow/Keras for building and training the deep learning model.The dataset contains 77 classes corresponding to the Armenian alphabet.

---

## 📝 Project Overview

The goal of this project is to classify images of handwritten Armenian letters into their respective classes.
It utilizes a dataset of grayscale PNG images, where each class represents a unique Armenian letter.
The model is trained using data augmentation and fine-tuned for better accuracy and faster performance.

---

## 🚀 Features
- Classification of 77 Armenian letters.
- Data augmentation for robust performance on handwritten variations.
- GPU-accelerated training for efficiency.
- Accuracy and loss tracking during training and validation.

---

## 📂 Dataset
The dataset contains:
- **Train**: 77 folders, each containing grayscale images of a single Armenian letter.
- Each folder represents a unique Armenian letter (e.g., `0: Ա`, `1: Բ`, `2: Գ`)
- Images are preprocessed to a fixed size of `128x128`.

After traning the model it was tested on a handwritten letter. 
There migth be some issues connected with code because the code needs optimization.  
