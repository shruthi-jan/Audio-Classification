# Audio-Classification
The aim of the project is to classify audio as either music or speech.  
The Dataset used is the gtzan dataset : The Dataset contains 128 monophonic audio files ( 64 each of speech and audio), each file is 30s long. The sampling rate is 22050Hz.  

The 30s audio is cut into 5s chunks to make the predictions more accurate.

The spectrograms of the audio files are used as the features to train using CNN  
The model has an accuracy of 95%.
