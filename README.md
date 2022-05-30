# Python-Custom-Digit-Recognition

Introduction: Optical Character Recognition (OCR) is a subfield of Image
Processing which is concerned with extracting text from images or scanned
documents.In this project, we will focus on building a mechanism that will
recognize handwritten digits. We will be reading images containing
handwritten digits extracted from the MNIST database and handwritten
dataset and try to recognize which digit is represented by that image.
This method takes images and converts them into a digital form readable by
computers, it applies certain algorithms on them, and results in a better quality
images.It overlaps the image with all the images in the reference set and find
the correlation between them in order to be able to determine the digit it
represents.

Objective: Handwritten digit recognition system (HDR) is meant for
receiving and interpreting handwritten input in the form of pictures or paper
documents. Traditional systems of handwriting recognition have relied on
handcrafted features and a large amount of prior knowledge. Training an
Optical character recognition (OCR) system based on these prerequisites is a
challenging task. Convolutional neural networks (CNNs) are very effective in
perceiving the structure of handwritten characters/words in ways that help in
automatic extraction of distinct features and make CNN the most suitable
approach for solving handwriting recognition problems.
Keywords: Image Processing, Optical Character Recognition, Handwritten
Digits, OpenCV, K-Nearest Neighbour, Neural Networks, HOG, Image
Correlation, Machine Learning.

Method: The weights are saved after training the model and these weights are
then used to process images of multiple characters. The images are broken
down into segments omitting extra spaces by drawing contours around the
object of interest and then the characters are extracted. Once the characters are
extracted the digits are segregated from the letters and the digits are returned.

Conclusion: "Handwritten Digit Recognition" was designed and
implemented, so as to overcome the limitations faced by automating the
existing error prone manual process. The current system is trained on the
handwritten digits and handwritten letters from mnist and kaggle respectively.
The goal of this project is to apply and manipulate the basic image correlation
techniques to build program and keep polishing and enhancing in order to
investigate to which extent it can get improved. This would allow us to see
how far we can go, in terms of accuracy and performance.

Future Scope:

➢ One of the major enhancements can be a Multilingual Handwritten Digits
recognition that would suit the diversity of languages.

➢ To develop a user-friendly interface to upload images from any
site/urls/computer .

➢ Identify Special characters and segregate them as a separate class.

Limitations: Although the Proposed Recognition model is a better model
than other existing models, the current model has its own limitations which
might need to be kept in mind. The model is trained on English Alphabets and
digits only. There are many languages in the world and the recognition of
handwritten characters of these languages still remains to be a challenging
task. Reason being the availability of Dataset in machine suitable format and
Feature extraction.
The other limitation is that the model fails to precisely recognise special
characters in an image as the model is trained to identify only letters and
digits. Although the model can classify the special characters/unseen
characters as one of the available classes, it would add up to the error rate of
the model.

Applications: : The main objective of this work is to ensure effective and
reliable approaches for recognition of handwritten digits and make banking
operations easier and error free.

![image](https://user-images.githubusercontent.com/74086712/171017577-4825ae45-1af4-4bac-b44d-f6849e6a344e.png)
