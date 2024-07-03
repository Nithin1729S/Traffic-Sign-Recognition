# Traffic Sign Classification

This project aims to classify traffic signs using a Convolutional Neural Network (CNN) model implemented with TensorFlow and Keras.

## Dataset

The dataset used for this project consists of traffic sign images categorized into 43 classes. The dataset is split into training and testing sets.

## Model Architecture

The CNN model consists of the following layers:

- Convolutional layers with ReLU activation
- MaxPooling layers
- Dropout layers for regularization
- Fully connected (Dense) layers with ReLU and Softmax activation

## Training
- The model is trained for 10 epochs with a batch size of 128.

## Evaluation
- The model's performance is evaluated on both the training and validation sets.

## Testing
- The model is tested on a separate test set to evaluate its final performance.

## Results
## Training and Validation Accuracy
- Epoch 1: Training Accuracy: 31.72%, Validation Accuracy: 69.13%
- Epoch 10: Training Accuracy: 90.45%, Validation Accuracy: 98.60%
