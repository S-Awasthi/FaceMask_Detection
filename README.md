# MaskEye
A robust and effective mask detection system


## Overview

This project focuses on developing a machine learning model to detect whether individuals in images are wearing face masks. The model is built using Python, OpenCV, and machine learning libraries, and is designed to be executed in Google Colab.

## Features

- **Data Loading**: Load and preprocess image data from Google Drive.
- **Data Labeling**: Categorize images into "with mask" and "without mask" labels.
- **Model Training**: Train a Convolutional Neural Network (CNN) for mask detection.
- **Evaluation**: Evaluate the model's performance on test data.
- **Inference**: Make predictions on new images.

## Prerequisites

- Python 3.x
- Google Colab
- Google Drive account
- Libraries: OpenCV, TensorFlow/Keras, NumPy, os

## Installation

1. Clone the repository or download the project files.
2. Open the `mask_detection.ipynb` file in Google Colab.
3. Ensure the required libraries are installed:
   ```bash
   !pip install opencv-python
   !pip install tensorflow
   ```
## Usage

1. **Mount Google Drive**: Run the cell to mount your Google Drive to access the dataset.

2. **Data Preparation**: Load and label the image data.

3. **Model Training**: Define and train the CNN model.

4. **Model Evaluation**: Evaluate the model on test data.
5. 
6. **Inference**: Make predictions on new images.


## Dataset

The dataset should be organized in Google Drive with two main directories:
- `with_mask`: Contains images of people wearing masks.
- `without_mask`: Contains images of people not wearing masks.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements.

## Acknowledgements

- This project utilizes [OpenCV](https://opencv.org/) and [TensorFlow](https://www.tensorflow.org/).
- Thanks to the creators of the datasets used for training and evaluation.

---


