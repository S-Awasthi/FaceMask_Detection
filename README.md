# MaskEye: Effective Mask Detection System

## Introduction

MaskEye is a project focused on developing a machine learning model capable of detecting whether individuals in images are wearing face masks. Utilizing Python, OpenCV, and machine learning libraries, this project is designed to run efficiently in Google Colab.

## Key Features

- **Data Loading**: Import and preprocess image data from Google Drive.
- **Data Labeling**: Classify images into "with mask" and "without mask" categories.
- **Model Training**: Develop and train a Convolutional Neural Network (CNN) for detecting masks.
- **Model Evaluation**: Assess the model's accuracy and performance using test data.
- **Inference**: Predict mask presence in new images.

## Requirements

- Python 3.x
- Google Colab
- Google Drive account
- Libraries: OpenCV, TensorFlow/Keras, NumPy, os

## Setup Instructions

1. Clone this repository or download the project files.
2. Open `mask_detection.ipynb` in Google Colab.
3. Install the necessary libraries:
    ```python
    !pip install opencv-python
    !pip install tensorflow
    ```

## Usage Guide

1. **Mount Google Drive**: Execute the cell to mount your Google Drive to access the dataset.
2. **Prepare Data**: Load and label the image data.
3. **Train Model**: Define and train the CNN model.
4. **Evaluate Model**: Assess the model using test data.
5. **Inference**: Use the trained model to make predictions on new images.

## Dataset Organization

The dataset should be structured in Google Drive with two primary directories:
- `with_mask`: Contains images of individuals wearing masks.
- `without_mask`: Contains images of individuals without masks.

## Contributions

Contributions are welcome! Fork the repository and submit a pull request with your improvements.

## Acknowledgements

This project leverages OpenCV and TensorFlow. Special thanks to the creators of the datasets used for training and evaluation.
