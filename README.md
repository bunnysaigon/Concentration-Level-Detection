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

### File Structure
* data: The input mEEG data is located within the data folder. There all 24 data files in total, eight files for each class (neutral, concentrating, relaxed).
* sample: This contains a sample of EEG data for visualizing.
* cleaned_data: This directory will contain the parsed EEG data. This will be automatically generated when running the program.
* features_extracted: This folder will contain the extracted features from input EEG data.
* test_train: This directory contains the training (75%) and testing (25%) dataset.

### Input and output
* The input data is recording with MUSE 2 on eight subjects on 60-second sessions for each state. The BlueMuse and MuseLSL were utilized to import the data.
* As for output, the CNN-based deep learning model categorizes the EEG data into three concentration-level classes: neutral, concentrating, relaxed.

### Executing program
* The program has two parts.
* First, run the script (Feature Extraction.ipynb) for feature extraction which will pre-process the input EEG signals.
* Then run the script (Concentration Level Detector.ipynb) which will build the deep learning model and perform the classification task. 
