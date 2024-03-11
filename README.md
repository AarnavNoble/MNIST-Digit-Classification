**MNIST-Digit-Classification**

**Trained a neural network to accurately recognize handwritten digits from images in the MNIST dataset.**

Data Exploration:

- Used Keras to load the MNIST dataset with 28x28 pixel grayscale digit images.

- Visualized sample images from each digit class for a better dataset understanding.

Data Preprocessing:

- Employed one-hot encoding for digit labels and normalized values to a 0-1 range.

- Reshaped image data for compatibility with the neural network.

Neural Network Architecture:

- Implemented a Sequential model using Keras.

- Added two dense layers with 128 neurons and ReLU activation.

- Utilized dropout regularization to prevent overfitting.

- Applied softmax activation in the output layer for multi-class classification.

Model Training:

- Compiled the model with categorical crossentropy loss and the Adam optimizer.

- Trained the model on the dataset with 10 epochs and a batch size of 512.

Evaluation + Confusion Matrix:

- Assessed the model's performance on the test dataset, achieving high accuracy.

- Generated a confusion matrix to visualize digit classification performance.

Special thanks to Andreas Zinonos for his insightful walkthrough.
