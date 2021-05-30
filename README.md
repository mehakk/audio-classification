# audio-classification

This repository contains implementations of classifying a set of audio keywords using 3 types of neural networks:

**1. Artificial Neural Network (ANN)**

**2. Convolutional Neural Network (CNN)**

**3. Recurrent Neural Network (RNN)**



**Dataset:** 

http://download.tensorflow.org/data/speech_commands_v0.01.tar.gz

I have used only 6 words from the above dataset (one, two, three, stop, left, right). You can choose as many types you want but be sure to update the units in the output layer of each model as per the number of output labels (keyword labels)

**Key libraries used:**
1. Librosa
2. TensorFlow (Keras)
3. ScikitLearn

**Steps involved:**
1. Library import
2. Audio data exploration for understanding
3. Audio data load, resampling, filtering
4. Audio feature extraction using MFCCs
5. Create dataframe for X (audio samples) and Y (labels)
6. Encoding the output labels
7. Split train and test data
8. Feature scaling (if needed)
9. Model creation (initialize, compile, fit)
10. Model prediction and evaluation
