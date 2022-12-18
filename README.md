# Concentration Level Classification using mEEG data

Our work aims to identify a mechanism for detection human emotions and concentration levels using EEG signals.

## Description

We utilized a commercial and portable Muse 2 headband with four EEG channels (TP9, AF7, AF8, TP10). Using mobile EEG (mEEG) inputs, we present a CNN model for concurrently detecting emotions and concentration levels. With an experiment on eight participants, we were able achieve an accuracy of over 90%.


## Getting Started

### Dependencies

* Python 3
* Compatible with common OS: MacOS, Windows, etc.

### Installing

* Download the zip and install the packages listed within the script.

### Executing program

* The input data is located within the data folder. There all 24 data files in total, eight files for each class. It is four-channel EEG data obtained from MUSE 2 on eight subjects on 60-second sessions for each state.  
* The program has two parts. First, run the script for feature extraction which will pre-process the EEG signals. 
* Then run the script for detection which will build the deep learning model and perform the task. 

