# Generate-Synthetic-Images-with-DCGANs-in-Keras

## Blog

[Medium Blog](https://baotramduong.medium.com/generate-synthetic-images-with-deep-convolutional-generative-adversarial-network-dcgan-424528b3477b)

## Introduction

We will be using the Keras Sequential API with Tensorflow 2 as the backend to build and train a Deep Convolutional Generative Adversarial Network (DCGAN) to generate images of fashionable clothes.

## Data Source and Description

We will use the Fashion MNIST dataset. Fashion-MNIST is a dataset of Zalando's article images:
* Consisting of a training set of 60,000 examples and a test set of 10,000 examples. 
* Each example is a 28x28 grayscale image for a total of 784 pixels in total.
* Each example is associated with a label from 10 classes: 0 T-shirt, 1 Trouser, 2 Pullover, 3 Dress, 4 Coat, 5 Sandal, 6 Shirt, 7 Sneaker, 8 Bag, and 9 Ankle boot

<img src = '../main/Data & Images/sample.png' heighth='75%' width='75%'>

## Modeling

### Generator Architect

<img src = '../main/Data & Images/generator.png' heighth='75%' width='75%'>

### Discriminator Architect

<img src = '../main/Data & Images/discriminator.png' heighth='75%' width='75%'>

### DCGAN Architect

<img src = '../main/Data & Images/dcgan.png' heighth='75%' width='75%'>

### Training GIF

<img src = '../main/Data & Images/dcgan.gif'>

## Generation

<img src = '../main/Data & Images/synthetic images.png'>

## Future Work

* Build Conditional DCGAN

## Reference

Géron, A. (2020). Chapter 17: Representation Learning and Generative Learning Using Autoencoders and GANs. In Hands-on machine learning with SCIKIT-LEARN, Keras, and TENSORFLOW: Concepts, tools, and techniques to build intelligent systems (2nd ed., p. 567). O'Reilly. 

Radford, A., Metz, L., & Chintala, S. (2016). Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks. CoRR, abs/1511.06434.
