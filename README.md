# PenPal: Providing a solution for digitizing and securely storing handwritten notes

## Introduction

Handwriting is a crucial method of storing knowledge for the future, yet it is easily destroyed or lost. It is critical to save handwritten papers digitally so that they may be quickly found and kept secure. However, because everyone's handwriting is unique, this is a difficult task. This difficulty can be solved with the aid of  PenPal.
Handwritten text recognition (HTR) is a method of using a computer to read and comprehend handwritten words. To do this, the computer must be able to separate words and read them in the correct order. Scientists are continually looking for new and better ways to achieve this, such as employing various neural network combinations.
A new sort of neural network known as a "vision transformer" has recently been utilized to evaluate photos. They have performed just as well as the greatest neural networks when it comes to picture recognition. The scientists will investigate the use of vision transformers to detect handwritten text in this study.



![penpal](https://user-images.githubusercontent.com/22881701/230894592-40b715c8-c01d-4cfa-94f3-b143226d082e.jpg)

## Metric of Success

* Character Error Rate: this is a metric of the performance of an automatic speech recognition (ASR) system. This value indicates the percentage of characters that were incorrectly predicted. The lower the value, the better the performance of the ASR system with a CharErrorRate of 0 being a perfect score.
* Word Error Rate: this is the ratio of errors in a transcript to the total words spoken. A lower WER in speech-to-text means better accuracy in recognizing speech.



## Aims
* Develop a machine learning model that can recognize different styles of handwriting, so that it can accurately convert handwritten notes into digital format.
* Create a database to store digitized notes in a secure and organized manner.
* Implement encryption and other security measures to protect the privacy of the notes.


## Challenges & Limitations
There are a few big challenges when it comes to teaching a computer to read handwritten text. 
* One of the biggest challenges is creating a big enough dataset of labeled handwritten text to train the machine learning model. If there isn't enough data, then transfer learning might need to be used.
* Another key challenge is teaching the computer to recognize words that it hasn't been specifically trained on. This is important if the computer is going to be able to read text in different languages. Currently, most of the available datasets are in English, so this is a big challenge. The computer will also only be able to recognize letters and numbers from the Latin alphabet.

## Background

* Handwritten Text Recognition.

Handwritten text recognition comes in two types: offline and online. We can use offline recognition for handwritten text recognition tasks where we only have access to a static image of the writing. For online recognition, we need a special electronic pen that records the order of the written strokes, so we can use it for tasks that require this level of detail, such as signature verification or handwriting analysis. However, online recognition is less common due to the requirement for specialized equipment.

* Neural Networks.

Neural networks extract information from handwriting images. They have an input, hidden, and output layer. Deep learning networks have more than three layers and recognize complex patterns. Each node in a layer is connected to all nodes in the next layer, called a fully connected layer. The value of a node is determined by multiplying the input with the weight, passing through an activation function. During training, our goal is to minimize a loss function.

* Convolutional Neural Networks

A CNN is a neural network for images and audio. It has an input layer, convolutional layers that identify important features, pooling layers that simplify data, and an output layer. Early layers find simple features and later layers find complex shapes to recognize the object in the image. We can use it for image and audio recognition tasks.



## Data source 
> [Iam](https://fki.tic.heia-fr.ch/databases/download-the-iam-handwriting-database).

> [EMNIST](https://www.nist.gov/itl/products-and-services/emnist-dataset).


![modeel](https://user-images.githubusercontent.com/22881701/230956464-4e0cff6e-6c4c-42be-8386-064f5a8af79f.png)


## Recommendations 

## Conclusions 


