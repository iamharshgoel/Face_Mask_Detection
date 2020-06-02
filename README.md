# Face_Mask_Detection
#Author : Harsh Goel
Date: 3rd June 

The Covid-19 changed our lives and has changed our habits and also because of it many of us entered social isolation. 
There are cities and places like marts, supermarkets, etc that it is an obligation to use a mask when you are  on the
streets or inside them. Thinking about this problem, this problem is to detect whether person is wearing mask or not.

The objective of this project is to train a deep convolutional neural network on images collected from the internet to 
check if a person is using a mask or not.

Finally, I use a two-step system to first “detect” faces on an image, using a trained face detector from OpenCV and after 
pass the found faces on the “mask predictor” that returns if the face is using a mask or not.
