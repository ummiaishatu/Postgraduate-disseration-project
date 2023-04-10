This document explains the steps needed to build 
an EEG based recognition system. This text file will explain briefly waht each files does in the project and

- concatenate folder
converts the eeg data from an edf file to a csv file and finally concatenating data needed for training and testin 

- data analysis
this folder consists the file that visualises the filtered data and raw data that

- Deep learning folder 
consist of all the files implemented for the classification of EEEg data using CNN - GRu for 2 - 10 subjects
together with their accuracy plots and losses of the

- Emotive 30s CSV folder 
contains the converted csv file of the eeg data for each subjects

- - Emotive 30s EDF folder 
conatins the raw edf file of the eeg data for each subjects 

- feature analysis folder 
this foldeer conatins a file that generates the features of the eeg data and plots the PSD of each segment 
and it also shows what type of frequency band each segment is assigned to [delta, theta, alpha, beta, gamma]

- Machine learning folder
this folder contains all the files which implements the machine learning classification for the EEG data and using three 
different machine learning models KNN, SVM and random forest classification