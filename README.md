# Fashion-MNIST Deep Learning Classification

A deep learning image classification project using TensorFlow and Keras to investigate how neural network architecture and training choices affect performance on the Fashion-MNIST dataset.

## Project Overview

This project explores multi-class image classification using the Fashion-MNIST dataset, which contains 70,000 grayscale images across 10 clothing categories.

A baseline neural network was developed and systematically modified to investigate the effect of:

- Hidden layer size
- Network depth
- Dropout regularisation
- Batch size
- Model capacity and generalisation

The models were evaluated using training, validation and test performance, supported by learning curves and confusion-matrix analysis.

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook / Google Colab

## Dataset

Fashion-MNIST consists of:

- 60,000 training images
- 10,000 test images
- 10 clothing classes
- 28 × 28 grayscale images

Image pixel values were normalised to the range 0–1 and flattened into 784-dimensional vectors for use with fully connected neural networks.

## Model Experiments

The investigation follows a controlled experimental approach.

### Baseline Model
A feedforward neural network was established as the baseline for comparison.

### Increased Hidden-Layer Size
The number of hidden units was increased to investigate whether greater model capacity improved classification performance.

### Deeper Network
An additional hidden layer was introduced to examine whether increased network depth improved feature representation.

### Dropout Regularisation
Different dropout configurations were investigated to evaluate their effect on overfitting and generalisation.

### Batch Size
Training configurations were compared to investigate how batch size affected model performance.

## Evaluation

Model performance was assessed using:

- Training accuracy
- Validation accuracy
- Test accuracy
- Learning curves
- Confusion matrix
- Per-class classification behaviour

The experiments achieved approximately **89% test accuracy**, while also demonstrating the trade-offs between model complexity, regularisation and generalisation.

## Key Skills Demonstrated

- Deep learning model development
- Multi-class image classification
- Neural network architecture experimentation
- Data preprocessing
- Model evaluation
- Hyperparameter experimentation
- Overfitting and regularisation analysis
- Visualisation and interpretation of machine-learning results

## Project Notebook

The complete implementation, experiments, outputs and analysis are available in:

`fashion_mnist_deep_learning.ipynb`

## Running the Project

The notebook can be run using Google Colab or a local Jupyter environment with the required Python libraries installed.

Fashion-MNIST is loaded directly through TensorFlow/Keras, so no separate dataset download is required.
