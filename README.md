# End to end Automatic-sound-Recognition(ASR) using Convolutional Neural Network
A speech recognition system based on Convolutional Neural Network built using TensorFlow

This is an application written in Python that recognizes keyworda from various human audio clips and it uses the deep learning toolkit TensorFlow to create and train a convolutional neural network

## Here I have use portion of speech commands dataset which contains short (one-second or less) audio clips of commands, such as "down", "go", "left", "no", "right", "stop", "up" and "yes"
![Capture](https://user-images.githubusercontent.com/83339884/163013825-ac76b953-4dfb-4476-81de-5682a4afbbf4.JPG)

## then i converted Waveforms into spectograms by using short Time Fourier Transformation(STFT)  which show frequency changes over time and can be represented as 2D images and that we can feed to our neural network to train the model.
![c1](https://user-images.githubusercontent.com/83339884/163013486-75274680-3565-40bb-b485-c1e31ed577e8.JPG)
examples of some of the spectograms
![c2](https://user-images.githubusercontent.com/83339884/163013921-d74db7cc-4a1c-4a03-928e-d00a55be34de.JPG)

Then I have feeded these spectograms to our Convolutional Neural Network layers
![c3](https://user-images.githubusercontent.com/83339884/163014416-8dab4e6b-b855-451c-a320-fb34996a939d.JPG)

## To evaluate th model I have used accuracy score and confusion matrix plot
![c4](https://user-images.githubusercontent.com/83339884/163015191-c53328a2-c8f1-4529-9132-30a425c1874a.JPG)
![c5](https://user-images.githubusercontent.com/83339884/163015207-4b8226b4-ac3b-43d6-99aa-e143b689f9d6.JPG)

At last I evaluated the model using a sample test file contaning 'No' keyword audio sample and preditcting the accuracy of our model
![c6](https://user-images.githubusercontent.com/83339884/163015228-6c1e3cda-77aa-45f7-858b-6c5f25872cce.JPG)

