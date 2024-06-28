# PRODIGY_ML_04

Prodigy Machine Learning Internship Task 4

Develop a hand gesture recognition model that can accurately identify and classify different hand gestures from image or video data, enabling intuitive human-computer interaction and gesture-based control systems.

Dataset: https://www.kaggle.com/datasets/gti-upm/leapgestrecog

## Data Extraction

- Import all the necessary Libraries
- Mount Google colab with Google-Drive
- Import zip file from your Google Drive and extract it's content

## Data Preprocessing

- Loading the images and their classes
- Shuffle the data
- Normalise the data
- Apply one hot encoding
- Reshape the data(Images)
- Split the data into Training set and Test set

## Model Training

- Apply Sequential from keras models
- Apply the first layer
- Apply hidden layers
- Apply the dense last layer
- Compile the model
- Fit the model with the training data

## Model Evaluation

- Get the summary
- Get Model loss chart and model accuracy chart for every epochs
- Show the confusion matrix
- Prediction
