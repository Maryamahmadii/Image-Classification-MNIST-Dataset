# Image-Classification-MNIST-Dataset
Training a deep learning model to correctly classify hand-written digits.
from tensorflow.keras.datasets import mnist
# the data, split between train and validation sets
(x_train, y_train), (x_valid, y_valid) = mnist.load_data()
