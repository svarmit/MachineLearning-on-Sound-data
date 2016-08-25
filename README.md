# MachineLearning-on-Sound-data
### Predicting the source of Audio
This repository consists of files and the machine learning ipython notebook demonstrating the machine learning techniques to identify the source of audio

To complete this task I extracted the features from the audio files to train the machine learning model. I used the validation of models to fine tune the parameters and finally testing the model on the data. 

Implemented **K nearest neighbours** , **Random Forest**, **Support Vector Machine**

For measuring the performance of model I used accuracy score, precision score and the confussion matrix(to see the classes that are mis predicted and try to identify reason).

The best performance was given by SVM


**Data source https://serv.cusp.nyu.edu/projects/urbansounddataset/**

There are 10 different sound classes which are air_conditioner, car_horn, children_playing, dog_bark, drilling, engine_idling, gun_shot, jackhammer, siren and street_music.

