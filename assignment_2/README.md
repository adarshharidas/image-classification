# Assignment 2 - Fashion-MNIST CNN

The solution is in `fashion_mnist_cnn.ipynb`. It is a beginner-friendly Jupyter notebook organized according to all five parts of the assignment.

## What the notebook covers

1. Loads Fashion-MNIST from TensorFlow/Keras.
2. Displays dataset sizes, image dimensions, and five labeled sample images.
3. Normalizes and reshapes the images for a CNN.
4. Builds the required two-convolution CNN model.
5. Trains with 10 epochs and a batch size of 32.
6. Prints final training accuracy and test accuracy.
7. Displays predictions for 10 test images.
8. Displays a confusion matrix and classification report.
9. Answers all six model-analysis questions.

No separate CSV or image folder is needed. TensorFlow downloads Fashion-MNIST automatically the first time the dataset-loading cell runs.

## Setup

From the project directory, run:

```bash
python3 -m pip install -r assignment_2/requirements.txt
jupyter notebook assignment_2/fashion_mnist_cnn.ipynb
```

In Jupyter, run the cells from top to bottom. The first dataset download requires an internet connection. Later runs use the downloaded copy.

Training time depends on the computer. If training is slow while learning, temporarily change `EPOCHS = 10` to `EPOCHS = 2`. Change it back to 10 for the final assignment output.
