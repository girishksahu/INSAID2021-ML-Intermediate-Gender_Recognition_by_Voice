# INSAID2021-ML-Intermediate-Gender_Recognition_by_Voice
INSAID 2021 ML Intermediate Term Project
# Project Description
## Introduction
Client for this project is a Telecom company.

They are a leading telecom company with 5 million users.
They want to keep track of the number of male and female users but as the user count increases the task becomes more tedious.

They want to automate the process of keeping track of male and female users using their voice.
Their research and development teams are trying to understand the acoustic properties of the voice and speech so that they can use it to enhance the customer experience in their new product.

## Current Scenario
Determining a person’s gender as male or female, based upon a sample of their voice, initially seems to be an easy task.

Often, the human ear can easily detect the difference between a male or a female voice within the first few spoken words.
However, designing a computer program to do this turns out to be a bit trickier.

Currently, the company is keeping track by manually entering the data for the user being male or female by listening to their voice which is a tedious task for the employees.

## Problem Statement
The current process suffers from the following problems:

* The current process is a manual classification of gender using their voice.
* This is very tedious and time-consuming as it needs to be repeated every time a new customer joins.

They want to automate the process of predicting the male or female voice using acoustic properties of the voice or speech rather than doing this manual work.

## Project Task
* Dataset consisting of recorded voice samples, collected from male and female speakers are provided.
* Project task is to build a classification model using the dataset.
## Project Deliverables
* Deliverable: Gender prediction using voice.
* Machine Learning Task: Classification
* Target Variable: label
* Win Condition: N/A (best possible model)
## Evaluation Metric
* The model evaluation will be based on the F1 Score score.
# Data Description
* This dataset was created to identify a voice as male or female, based upon acoustic properties of the voice and speech.
* The column label is also present in the dataset which has two values male and female.

This is the data that we have to predict for future samples.

The dataset is divided into two parts: Train and Test sets.

## Train Set:
* The train set contains 2851 rows and 22 columns.
* The last column label is the target variable.
## Test Set:
* The test set contains 317 rows and 21 columns.
* The test set doesn’t contain the label column.
* It needs to be predicted for the test set.

# Dataset Feature Description
The Dataset contains the following columns:

| ID | Feature Name | Description of the feature |
| :-- | :--| :--| 
|01| **Id**   | Unique Id of the record |
|02| **meanfreq**      | Mean frequency (in kHz) for the voice sample|
|03| **sd**        | Standard deviation of the frequency|
|04| **median**          | Median frequency (in kHz) for the voice sample|
|05| **Q25**      | First quantile (in kHz) |
|06| **Q75**           | Third quantile (in kHz)|
|07| **IQR**     | Interquartile range (in kHz) |
|08| **skew**     | Skewness of the voice sample|
|09| **kurt**        | Kurtosis of the voice sample                                         |
|10| **sp.ent**          | Spectral entropy                                   |
|11| **sfm**         | Spectral flatness of the voice sample  |
|12| **mode**     | Mode frequency                                   |
|13| **centroid**     | 	Frequency centroid                                  |
|14| **peakf**     | Peak frequency (the frequency with the highest energy)                                  |
|15| **meanfun**     | Average of fundamental frequency measured across the acoustic signal           |
|16| **minfun**     | Minimum fundamental frequency measured across the acoustic signal           |
|17| **maxfun**     | Maximum fundamental frequency measured across the acoustic signal                              |
|18| **meandom**     | Average of dominant frequency measured across the acoustic signal                                  |
|19| **mindom**     | Minimum of dominant frequency measured across the acoustic signal                                  |
|20| **maxdom**     | Maximum of dominant frequency measured across the acoustic signal                                  |
|21| **dfrange**     | Range of dominant frequency measured across the acoustic signal                                  |
|22| **modindx**     | Modulation index. Calculated as the accumulated absolute difference between adjacent Measurements of fundamental frequencies divided by the frequency range|
|23| **label**     | The label for the voice sample (male or female)|
