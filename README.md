# SMS-Spam-Detection-ML-Model
This repository contains a machine learning model for SMS spam detection using Logistic Regression and TF-IDF feature extraction. Detecting SMS spam is crucial for preventing unwanted messages and maintaining user privacy.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Usage](#usage)
- [Data Preprocessing](#data-preprocessing)
- [Feature Extraction](#feature-extraction)
- [Model Training](#model-training)
- [Model Evaluation](#model-evaluation)
- [Results](#results)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Unwanted SMS spam messages can be a nuisance and a security concern. This machine learning model uses Logistic Regression to classify SMS messages as either spam or not spam (ham) based on their content.

## Dataset

The SMS spam dataset used for this model is provided in the 'spam.csv' file, encoded in Latin-1. It contains SMS messages labeled as either 'spam' or 'ham' (not spam). The dataset is preprocessed to handle missing values and label encoding.

## Usage

To use this SMS spam detection model:

1. Clone this repository to your local machine.
2. Ensure you have the required Python libraries installed (see Dependencies section).
3. Run the provided Python script, which includes data preprocessing, feature extraction, model training, and evaluation.
4. View the model's accuracy on the test data.

You can customize the model by adjusting hyperparameters, experimenting with different feature extraction methods, or using your own SMS dataset.

## Data Preprocessing

Data preprocessing involves handling missing values by replacing them with empty strings and label encoding to convert the 'spam' and 'ham' labels into binary values (0 for spam and 1 for ham).

## Feature Extraction

Feature extraction is performed using TF-IDF (Term Frequency-Inverse Document Frequency) vectorization. It converts the text data into numerical format, representing the importance of words in the SMS messages.

## Model Training

The machine learning model used in this project is Logistic Regression. The model is trained on the training data, where it learns to classify SMS messages based on their TF-IDF features.

## Model Evaluation

The model's performance is evaluated using accuracy, which measures the percentage of correctly classified SMS messages as either spam or ham.

## Results

The accuracy of the SMS spam detection model is provided in the README or as part of the repository documentation. Users can assess the model's effectiveness in classifying SMS messages.

## Dependencies

To run this project, you need the following dependencies:

- Python (3.x)
- NumPy
- Pandas
- Scikit-learn

You can install these dependencies using `pip` or `conda`.

## Contributing

Contributions to this project are welcome! If you have ideas for improving the model, adding new features, or enhancing the documentation, please open an issue or submit a pull request.
