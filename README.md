MNIST Handwriting Recognition with TensorFlow

This project implements a Convolutional Neural Network (CNN) in TensorFlow/Keras to classify handwritten digits (0–9) from the MNIST dataset. The goal is to explore deep learning techniques in Python for image classification and evaluate performance using different training strategies.

🔧 Technologies & Libraries

Python – core programming language

TensorFlow / Keras – building and training the CNN

NumPy – numerical operations and array handling

Matplotlib – visualization of training curves and results

scikit-learn – evaluation metrics (confusion matrix, accuracy, precision)

📊 Dataset

MNIST dataset: 60,000 training images and 10,000 test images

28×28 grayscale digit images (0–9)

Normalized and reshaped for TensorFlow CNN input

🚀 Features

CNN model with Conv2D, MaxPooling, Dropout, and Dense layers

Training with both SGD and Adam optimizers

Evaluation using accuracy, loss curves, and confusion matrix

Achieves ~99% test accuracy on MNIST

📈 Results

Stable convergence with minimal overfitting

Adam optimizer outperformed SGD in accuracy and training speed

Minor misclassifications between visually similar digits (e.g., 3 & 5, 4 & 9)

▶️ How to Run

Clone the repo:

git clone https://github.com/YourUsername/MNIST-TensorFlow.git
cd MNIST-TensorFlow


Install dependencies:

pip install -r requirements.txt


Run the notebook:

jupyter notebook Digit_Recognizer.ipynb

✅ Future Work

Experiment with deeper CNNs (LeNet-5, ResNet)

Add data augmentation for better generalization

Deploy as a lightweight handwriting recognition API
