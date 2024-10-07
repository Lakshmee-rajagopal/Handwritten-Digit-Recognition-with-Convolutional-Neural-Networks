# Handwritten-Digit-Recognition-with-Convolutional-Neural-Networks
The goal of this project is to build a Convolutional Neural Network (CNN) to recognize handwritten digits from the MNIST dataset. The MNIST dataset contains 70,000 grayscale images of digits (0-9), each 28x28 pixels in size. Using TensorFlow and Keras, a deep learning model is created and trained  to classify these digits accurately. The project involves data preprocessing, model building, training, and evaluation to understand CNNs.

The following steps have been performed:
Load the MNIST dataset.
Normalize the pixel values between 0 and 1.
Build a CNN with Convolutional layers.
Include MaxPooling layers.
Add Dense layers and the correct output layer with 10 neurons and softmax activation.
Use the 'adam' optimizer.
Set the loss function to 'categorical_crossentropy'.
Track accuracy as the metric.
Train the model.
Track both training and validation accuracy/loss.
Evaluate the model on test data.
Plot accuracy and loss graphs.
