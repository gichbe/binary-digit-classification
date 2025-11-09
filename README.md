# Binary Digit Classification (0 vs 1) using TensorFlow/Keras

A simple neural network trained to distinguish between handwritten digits 0 and 1.

## Model
- Input: 20x20 grayscale image
- Hidden layer: Dense(25, relu), Dense(15, relu)
- Output: Dense(1, sigmoid)
- Loss: binary_crossentropy
- Optimizer: Adam

## How to run
```bash
pip install -r requirements.txt
jupyter notebook binary_digit_classifier.ipynb
