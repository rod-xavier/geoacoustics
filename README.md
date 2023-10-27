# geoacoustics
This repository contains codes regarding rainfall estimation through sound recordings, using machine learning algorithms

The approach used in the jupyter notebook consists of analyzing the sound recordings through power spectrum density plots, selecting the best frequency range to be used as input in the models, associating the recordings with sychronized rain gauge measurements.

The code used in sound_of_rainfall takes a dataset with information regarding timestamps, rain gauge measurements, .wav filenames, rain classes and PSD values. A random forest classifier is trained and tested on 10 days validation previously taken from the dataset, trains 3 regression models, predicts the values of the validation dataset and plots the R² in different time resamples.

A small sample of the data used in the research can be downloaded in the psd_data.zip file, amount of data is limited by the size suported in github (up to 25 MB).
