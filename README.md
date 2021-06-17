# Speech emotion recognition using ESN-IP
Implementation of echo state neural network empowered by intrinsic plasticity for classification problem 

In this project I rewrote the echo state neural network from scratch using the Matlab code by Andrea-V as a reference so I credit his work.
you can find the Matlab code in the following link:

https://github.com/Andrea-V/Echo-State-Network-with-Intrinsic-Plasticity

This code however, uses python numpy to build the echo state reservoir. Moreover, it is modified to solve a clssification problem in contrast with the Matlab code that uses the echo state to solve a regression problem.

### The dataset:
This project aims to do emotion recognition from speech. Therefore, it uses Berlin Dataset to train the model. It is famous dataset used by researchers doing speech emotion recognition.

In this project I used librosa and opensmile libraries to extract features from the sound. You can find 2 Google colaboratory notebook files in this repository, showing all the steps from dowinloading the dataset, extracting the features to creating the ESN class and using intrinsic plasticity formula and modifying it for classification problems.


#### Note
If you want to use this code please mention this repository as well as Andrea-V repository https://github.com/Andrea-V/Echo-State-Network-with-Intrinsic-Plasticity

