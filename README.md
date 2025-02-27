# Neural Network Model for Iris Dataset

Implements a simple feedforward neural network using PyTorch to classify the Iris dataset. The model takes four input features, processes them through two hidden layers, and outputs the predicted class among three species of iris flowers.

## Model Architecture
- **Input Layer**: 4 features (sepal length, sepal width, petal length, petal width)
- **Hidden Layer 1**: 8 neurons with ReLU activation
- **Hidden Layer 2**: 9 neurons with ReLU activation
- **Output Layer**: 3 neurons (corresponding to the three iris species - setosa, versicolor, virginica)

## Python libraries installed:
- `torch`
- `torch.nn`
- `pandas`
- `matplotlib`

## Working

- The dataset is loaded into a Pandas DataFrame.

- Features (input variables) are extracted and processed.

- The neural network model is defined using PyTorch.

- Forward propagation is implemented with ReLU activation in hidden layers.

- The model outputs class predictions based on learned patterns.

- Training involves optimizing weights using loss functions and an optimizer.


