# Fashion-MNIST Classification with CNN
This project classifies images from the Fashion-MNIST dataset using Convolutional Neural Networks (CNNs) implemented in PyTorch.

# Overview
This project trains a CNN to classify images from the Fashion-MNIST dataset into one of 10 categories. Two CNN architectures are implemented:
- **Standard CNN**
- **CNN with Batch Normalization**

# Dataset
You can find the dataset here --> https://github.com/zalandoresearch/fashion-mnist

The Fashion-MNIST dataset consists of grayscale images (28x28 pixels) categorized into 10 classes:
1. T-shirt/top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle boot

# Model Architecture
The CNN consists of:
- Two convolutional layers (5x5 kernel, padding=2)
- Batch normalization (optional)
- Max pooling layers (2x2 kernel)
- Fully connected layer
- ReLU activation function

## Training and Evaluation
The model is trained using:
- **Loss Function:** Cross-Entropy Loss
- **Optimizer:** Stochastic Gradient Descent (SGD) with a learning rate of 0.1
- **Batch Size:** 100

The training and validation accuracy is displayed at the end of training.

## Results
The model achieves high accuracy (above 88%) in classifying Fashion-MNIST images. The notebook includes training logs and visualizations of the training loss and accuracy.
