# ColorizeMe

ColorizeMe is an image processing project that utilizes autoencoders to transform black and white images into vibrant and realistic colorful images. This repository contains the code and resources necessary to implement the colorization process seamlessly.

Autoencoder are special type of deep learning architecture that consist of two networks encoder and decoder. The encoder, through a series of CNN and downsampling, learns a reduced dimensional representation of the input data while decoder through the use of CNN and upsampling, attempts to regenerate the data from the these representations. A well-trained decoder is able to regenerated data that is identical or as close as possible to the original input data. Autoencoder are generally used for anamoly detection, denoising image, colorizing the images. Here, i am going to colorize the landscape images using autoencoder.


Image Colorization
Image colorization using different softwares require large amount of human effort, time and skill.But special type of deep learning architecture called autoencoder has made this task quiet easy. Automatic image colorization often involves the use of a class of convolutional neural networks (CNN) called autoencoders. These neural networks are able to distill the salient features of an image, and then regenerate the image based on these learned features.
![image](https://github.com/Aditi-Singh-24/ColorizeMe/assets/120120463/408b7abf-6c97-4322-b56f-d09c13662d60)

# Dataset link:
https://www.kaggle.com/datasets/theblackmamba31/landscape-image-colorization
