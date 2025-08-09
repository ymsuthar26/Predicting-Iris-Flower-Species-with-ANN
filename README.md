# Predicting-Iris-Flower-Species-with-ANN
This notebook builds and trains an Artificial Neural Network (ANN) to classify Iris flower species (Setosa, Versicolor, Virginica) based on their features (sepal length, sepal width, petal length, petal width).
Key steps include:

Importing libraries (data handling, visualization, and deep learning).

Loading the Iris dataset and converting it into a usable Pandas DataFrame.

Data preprocessing – splitting into features and labels, one-hot encoding target labels, and train-test splitting.

Building the ANN model using Keras:

Input layer for the four features.
Hidden layers with activation functions like ReLU.
Output layer with softmax for multi-class classification.
Compiling the model with categorical crossentropy loss and an optimizer (Adam).
Training the model on the training set while validating on the test set.
Evaluating the accuracy and visualizing the training history (loss/accuracy curves).
Making predictions on new/unseen data.

## Libraries Used
numpy, pandas, matplotlib, seaborn, sklearn, tensorflow.keras

Ask ChatGPT
