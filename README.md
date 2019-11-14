# EIP4_assignment1
Session 1 Assignment - Basics of Convolution Neural Networks

# Score - 99.16%

print(score)

[0.03987084140867587, 0.9916]

# Definitions

## 1. convolution :  
The process of applying a filter  over an input image again and again(repeatedly) to extract the essential features from the image.

## 2.kernels : 
The operator which extracts features from the image(input) by looking at a part of it.The size of kernel is smaller than that of the input and the type of operation applied is dot product.

## 3. Epochs : 
Epoch is defined as passing the complete training data to a network only once.

## 4. 1X1 convolution : 
It is an operation, in which an input image is convolved with a 1X1 filter, through which the number of features can be changed. Here the height and width are same. 

## 5. 3X3 convolution: 
It is an operation, in which an input image is convolved with a 3X3 filter, to extract information like vertical, horizontal edges by considering information at neighbours.

## 6. Feature maps : 
The set of convolved features obtained by the application of filter over input image in a repeated manner(recursively).

## 7. Activation Function : 
It is a function that adds nonlinearity to obtain the essential features.

## 8. Receptive Field : 
It is the area of the input layer which contributes to only  one pixel of the immediate next layer. Local receptive field is the size of the kernel.

