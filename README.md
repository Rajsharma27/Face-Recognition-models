# Face-Recognition-models
🧠 Face Recognition using CNN
This project implements a face recognition system using a Convolutional Neural Network (CNN) built with TensorFlow/Keras. It classifies faces into known identities using supervised deep learning — no OpenCV, no traditional ML algorithms like KNN or SVM.

📌 Features
Face recognition using a custom-trained CNN

Image preprocessing and data augmentation

Trained on labeled face images per person

Easy to scale by adding more identity folders

Prediction on test images via a simple Python script

🧱 Tech Stack
Python
TensorFlow / Keras
NumPy, Pandas
Matplotlib / Seaborn (for visualizations)

🧠 Model Architecture
A custom CNN model with the following layers:

2–3 Convolutional + MaxPooling layers
Flatten + Dense + Dropout
Output layer with Softmax activation

Implemented using TensorFlow/Keras.
