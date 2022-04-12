# End to end Automatic-sound-Recognition(ASR) using Convolutional Neural Network
A speech recognition system based on Convolutional Neural Network built using TensorFlow

This is an application written in Python that recognizes keyworda from various human audio clips and it uses the deep learning toolkit TensorFlow to create and train a convolutional neural network

## Here I have use portion of speech commands dataset which contains short (one-second or less) audio clips of commands, such as "down", "go", "left", "no", "right", "stop", "up" and "yes"
![Capture](https://user-images.githubusercontent.com/83339884/163010058-7ba0b75f-8b8c-4fb5-9570-f74aa021da79.JPG)

## then i converted Waveforms into spectograms by using short Time Fourier Transformation(STFT)  which show frequency changes over time and can be represented as 2D images and that we can feed to our neural network to train the model.

