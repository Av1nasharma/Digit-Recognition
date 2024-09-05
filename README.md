# Deep-Learning-MNIST---Handwritten-Digit-Recognition

An implementation of multilayer neural network using keras with an Accuracy: mean=98.960 std=0.097, n=5 using 5-crossfold Validation and using the built-in evaluation of 99.13

## About MNIST dataset:

MNIST (Modified National Institute of Standards and Technology database) is probably one of the most popular datasets among machine learning and deep learning enthusiasts. The MNIST dataset contains 60,000 small square 28×28 pixel grayscale training images of handwritten digits from 0 to 9 and 10,000 images for testing. So, the MNIST dataset has 10 different classes.
<br/><br/>

## Steps:

1. Import the libraries and load the dataset: Importing the necessary libraries, packages and MNIST dataset
2. Preprocess the data
3. Create the model
4. Train and Evaluate the Model
5. Saving the model
6. Make Predictions

## Summary of Sequential model

![Scummary](Images/Summary%20of%20the%20Model.png)
<br/><br/>

## Accuracy

**Accuracy** using **5-crossfold Validation** is mean=98.960 std=0.097, n=5 and using the built-in evaluation of **99.13**

![Custom number prediction](Images/accuarcy%20custom.png)

![prediction](Images/accuracy%20with%20custom%20data.png)

<br/><br/>

## Prediction

### A. Dataset images

![Data Set Prediction](Images/data%20set%20image%20prediction.png)

### B. Testing with Custom Number

![Custom number prediction](Images/TestNumber.png)
<br/>
![prediction](Images/prediction.png)
<br/><br/>

# Run

```
python3 predict.py
```
