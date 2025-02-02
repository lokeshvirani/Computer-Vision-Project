# Anomaly Detection with Autoencoders

## Project Overview
This project focuses on developing and applying a Convolutional Neural Network (CNN) autoencoder for image reconstruction and anomaly detection. It utilizes the MNIST dataset of handwritten digits for training and the Fashion MNIST dataset of fashion items as anomalies to evaluate the model's performance.

## Objectives
- Develop a CNN autoencoder that can effectively compress and reconstruct images.
- Utilize the autoencoder for anomaly detection by identifying deviations in reconstruction from the Fashion MNIST dataset.
- Evaluate the effectiveness of the autoencoder in terms of reconstruction accuracy and anomaly detection.

## Methodology
### Data Preparation
- **MNIST Dataset**: Used for training the autoencoder. It contains 60,000 images of handwritten digits.
- **Fashion MNIST Dataset**: Used as anomaly data to test the model's detection capabilities. It includes 60,000 images of fashion articles.

### Model Architecture
- **Encoder**: Consists of convolutional layers that compress the input image into a latent space.
- **Decoder**: Comprises convolutional layers that attempt to reconstruct the original image from the encoded representation.

### Training
- The model is trained using the Adam optimizer with a binary cross-entropy loss function over 50 epochs.

## Results
- The model achieved high accuracy in reconstructing MNIST images and effectively detected anomalies in the Fashion MNIST dataset.
- Performance metrics include mean reconstruction error and anomaly detection accuracy.

## How to Run the Project
1. Clone this repository.
2. Install required libraries:
   ```bash
   pip install -r requirements.txt

## Libraries Used
1. TensorFlow
2. Keras
3. Matplotlib
4. Numpy
5. Scipy
