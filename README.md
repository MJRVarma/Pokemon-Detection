# Image-Based Pokemon Recognition

This project is an implementation of image-based Pokemon recognition using Convolutional Neural Networks (CNNs) with TensorFlow and Keras. The project can classify an input image of a Pokemon as either Pikachu or Raichu with high accuracy.

## Dependencies
To run this project, you will need to have the following dependencies installed:

TensorFlow
Keras
matplotlib
NumPy
You can install these dependencies using the following pip commands:
  pip install tensorflow
  pip install keras
  pip install matplotlib
  pip install numpy

## Dataset
The dataset used for this project consists of images of Pikachu and Raichu. The images were obtained from various sources and were manually curated to ensure high quality. The dataset contains 800 images of Pikachu and 800 images of Raichu, which are split into training and testing sets.

## Training
The model was trained using the training set with various data preprocessing techniques such as rescaling, shearing, zooming, and flipping. The CNN model consists of two convolutional layers with ReLU activation and max-pooling layers, followed by a dense layer with ReLU activation and a final dense layer with sigmoid activation. The model was trained for 25 epochs with the binary cross-entropy loss function and the Adam optimizer.

## Testing
The trained model was evaluated on the testing set, and achieved an accuracy of 90% on the testing set. The model was also tested on a single input image of a Pokemon, which was classified as either Pikachu or Raichu with high accuracy.

