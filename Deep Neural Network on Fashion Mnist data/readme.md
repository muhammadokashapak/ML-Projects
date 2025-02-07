Fashion MNIST Dataset with Deep Neural Network (DNN) Implementation
Project Overview
This project implements a Deep Neural Network (DNN) model on the Fashion MNIST dataset. The dataset consists of 60,000 training images and 10,000 testing images, divided into 10 fashion categories.

Dataset Details
- Dataset: Fashion MNIST
- Training Images: 60,000
- Testing Images: 10,000
- Categories: 10 (T-shirt, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot)

DNN Model Architecture
- Input Layer: 784 neurons (28x28 images)
- Hidden Layer 1: 512 neurons, ReLU activation
- Hidden Layer 2: 256 neurons, ReLU activation
- Output Layer: 10 neurons, Softmax activation

Training Details
- Optimizer: Adam
- Loss Function: Cross-Entropy
- Epochs: 10
- Batch Size: 128

Results
- Training Accuracy: 90.5%
- Testing Accuracy: 88.2%

Requirements
- Python 3.x
- TensorFlow 2.x
- NumPy
- Matplotlib

Usage
. Install the requirements: pip install -r requirements.txt
. Run the training script: python train.py
. Evaluate the model: python evaluate.py

Contributing
Contributions are welcome! If you'd like to improve the model or add new features, please submit a pull request.

License
This project is licensed under the MIT License.
