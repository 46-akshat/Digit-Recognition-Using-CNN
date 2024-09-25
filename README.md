# Digit Recognition using MNIST Dataset

This project implements a digit recognition system using a neural network trained on the MNIST dataset, which contains images of handwritten digits (0-9).

## Dataset

The MNIST dataset consists of 60,000 training images and 10,000 testing images, each a 28x28 pixel grayscale image.

## Model Architecture

The model includes:
- **Flatten Layer**: Converts 28x28 images to 1D arrays (784 pixels).
- **Dense Layer**: 128 neurons with ReLU activation.
- **Output Layer**: 10 neurons (for digits 0-9) with softmax activation.

## Installation

Install the required libraries:

```bash
pip install tensorflow numpy matplotlib
git clone <repository-url>
cd <repository-folder>
python digit_recognition.py


### Notes
- Ensure to replace `<repository-url>` and `<repository-folder>` with your actual repository details.
- Feel free to adjust any phrasing to better fit your style or specifics of your project!
