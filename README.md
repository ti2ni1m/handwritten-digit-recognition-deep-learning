# Handwritten Digit Recognition using CNN (MNIST)

This project builds a Convolutional Neural Network (CNN) to recognize handwritten digits (0–9) using the MNIST dataset. It also includes a GUI application where users can draw digits and get real-time predictions.

---

## Features

- CNN model built using TensorFlow/Keras
- Trained on MNIST dataset (60,000 training images)
- Real-time digit prediction using Tkinter GUI
- Image preprocessing and normalization
- Model saving and loading

---

## Model Performance

- Test Accuracy: ~85%  
- Loss: ~0.62  

> Note: Accuracy can be improved using better optimizers (e.g., Adam), more epochs, and hyperparameter tuning.

---

## Project Structure

handwritten-digit-recognition/
│
├── notebook/ # Jupyter Notebook (training + explanation)
├── model/ # Saved trained model
├── app/ # GUI application
├── images/ # Screenshots
├── requirements.txt
└── README.md
