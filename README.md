# MNIST Digit Classification: Perceptron vs ANN vs CNN

## Overview

This project compares three neural network approaches for handwritten digit classification using the MNIST dataset: Perceptron, Artificial Neural Network (ANN), and Convolutional Neural Network (CNN).

The objective is to understand how different model architectures perform on image classification and compare their predictive accuracy.

## Models Implemented

- **Perceptron:** A basic linear classification model used as a baseline.
- **Artificial Neural Network (ANN):** A fully connected neural network that learns patterns from flattened image pixels.
- **Convolutional Neural Network (CNN):** A deep learning model that extracts spatial features from images using convolutional layers.

## Dataset

The MNIST dataset contains 70,000 grayscale images of handwritten digits from 0 to 9.

- Training images: 60,000
- Testing images: 10,000
- Image dimensions: 28 × 28 pixels
- Number of classes: 10

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras

## Project Workflow

1. Load and explore the MNIST dataset.
2. Preprocess and normalize image pixel values.
3. Train the Perceptron model.
4. Build and train the ANN model.
5. Build and train the CNN model.
6. Evaluate model performance using classification metrics.
7. Compare results using visualizations.

## Evaluation Metrics

The models are evaluated using:

- Accuracy
- Confusion Matrix
- Classification Report
- Visual comparison of model predictions and performance

## Results

The project compares the performance of all three models to understand the impact of model architecture on handwritten digit recognition.

| Model | Approach |
|---|---|
| Perceptron | Linear classification |
| ANN | Fully connected neural network |
| CNN | Convolution-based image feature extraction |

Actual evaluation results and visual comparisons can be added here after training the models.

## Key Learnings

- Understanding the differences between traditional linear models and neural networks.
- Learning how ANN and CNN architectures process image data.
- Applying image preprocessing and normalization.
- Evaluating classification models using Scikit-learn and TensorFlow/Keras.
- Visualizing and comparing model performance.

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/MNIST-Perceptron-ANN-CNN-Comparison.git
   ```

2. Navigate to the project directory:

   ```bash
   cd MNIST-Perceptron-ANN-CNN-Comparison
   ```

3. Install the required libraries:

   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn tensorflow
   ```

4. Open and run the notebook using Jupyter Notebook or Google Colab.

## Future Improvements

- Compare training time and inference time.
- Analyze misclassified handwritten digits.
- Compare model performance using additional evaluation metrics.
- Deploy the best-performing model as an interactive application.

## Author

**Ritesh Das**

GitHub: [rites h23r](https://github.com/ritesh23r)

This project was developed for learning and experimentation with machine learning and deep learning techniques for image classification.
