# Fashion-MNIST-Image-Classification

## Google Colab Link [Link Here......] (https://colab.research.google.com/drive/1MYT1dGUjIqs6C0C-omCNC2kfWYSYiuE-?usp=sharing)

### 1. What is the Fashion MNIST dataset?
Answer : The Fashion MNIST dataset is a collection of 70,000 grayscale images of clothing items such as shoes, bags, T-shirt. Each images is 28x28 pixels and belongs to one of 10 different fashion categories. It is commonly used as a benchmark machine learning algorithms for image classification.

### 2. Why do we normalize image pixel values before training?
Answer : We normalize image pixel values to scale them from the range 0–255 down to 0–1. This helps the neural network train faster and more efficiently by keeping input values small and consistent. Normalization also improves numerical stability and helps the optimizer converge more easily.

### 3. List the layers used in the neural network and their functions.
Answer : The model uses a Flatten layer to convert the 28×28 image into a one-dimensional array. A Dense hidden layer with 128 neurons and ReLU activation learns important features from the data. The final Dense output layer with 10 neurons produces the class scores for the 10 fashion categories.

### 4. What does an epoch mean in model training?
Answer : An epoch represents one complete pass of the entire training dataset through the neural network. During each epoch, the model updates its weights based on the training data to improve performance. Multiple epochs allow the model to learn patterns more effectively.

### 5. Compare the predicted label and actual label for the first test image.
Answer : The predicted label for the first test image matches the actual label. This means the model correctly classified the image into the appropriate clothing category, showing that the trained model is able to generalize to unseen data.

### 6. What could be done to improve the model’s accuracy?
Answer : The model’s accuracy could be improved by adding more hidden layers or increasing the number of neurons. Using convolutional neural network (CNN) layers instead of a simple dense network would help the model learn spatial features better. Other improvements include training for more epochs, adding dropout layers, or tuning hyperparameters.
