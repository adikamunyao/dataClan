# PenPal: Providing a solution for digitizing and securely storing handwritten notes

## Introduction

Writing things down by hand is an important way of keeping information for the future, but it can easily get ruined or lost. Saving handwritten documents digitally is important so that they can be easily searched and kept safe. However, because everyone's handwriting is different, it's tricky to do this. Penpal helps to solve this problem.
Handwritten text recognition (HTR) is a way to use a computer to read and understand words that are written by hand. To do this, the computer needs to be able to separate the words and read them in the right order. Scientists are always working on new and better ways to do this, like using different combinations of neural networks.
Recently, a new type of neural network called a \"vision transformer\" has been used to analyze images. They have been really good at recognizing images and have worked just as well as the best neural networks. In this project, the scientists will explore using vision transformers to recognize handwritten text.


![penpal](https://user-images.githubusercontent.com/22881701/230894592-40b715c8-c01d-4cfa-94f3-b143226d082e.jpg)

## Aims
* Develop a machine learning model that can recognize different styles of handwriting, so that it can accurately convert handwritten notes into digital format.
* Create a database to store digitized notes in a secure and organized manner.
* Implement encryption and other security measures to protect the privacy of the notes.


## Challenges & Limitations
There are a few big challenges when it comes to teaching a computer to read handwritten text. 
* One of the biggest challenges is creating a big enough dataset of labeled handwritten text to train the machine learning model. If there isn't enough data, then transfer learning might need to be used.
* Another key challenge is teaching the computer to recognize words that it hasn't been specifically trained on. This is important if the computer is going to be able to read text in different languages. Currently, most of the available datasets are in English, so this is a big challenge. The computer will also only be able to recognize letters and numbers from the Latin alphabet.



## Data source 
> [Iam](https://fki.tic.heia-fr.ch/databases/download-the-iam-handwriting-database).

> [EMNIST](https://www.nist.gov/itl/products-and-services/emnist-dataset).


