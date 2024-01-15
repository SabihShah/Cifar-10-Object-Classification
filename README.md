# Cifar-10-Object-Classification
The cifar-10 dataset is a widely used image dataset for ML/DL. It contains 50000 training images of size (32,32,3)

## **Note: This is a lightweight model to show the implementation of object classification on cifar-10 dataset**

## Dataset
- The cifar-10 dataset is used for this project. It can be downloaded here: https://www.cs.toronto.edu/~kriz/cifar.html
- It contains 5 training batches and 1 test batch, each containing 10000 images with labels.
- Each image is of size (32,32,3)
- The images are divided into 10 classes.

## Implementation
### Libraries used:
- tensorflow
- opencv
- matplotlib
- numpy
- pickle

### Getting started
```sh
pip install requirements.txt
```
```sh
git clone https://github.com/SabihShah/Cifar-10-Object-Classification.git
```
**or**
create a new file and using saved model weights, skip the training and onto the testing using
```sh
tensorflow.keras.models.load_model
```

## Training
- relu activation function is used and softmax for multi-class classification in the last layer
- Model is trained for 10 epochs with adam optimizer and sparse_categorical_crossentropy loss function
