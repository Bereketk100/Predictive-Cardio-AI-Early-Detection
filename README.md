# Predictive-Cardio-AI-Early-Detection
# AI-Powered Early Detection of Heart Irregularities

## Overview

This project aims to revolutionize cardiovascular healthcare by leveraging artificial intelligence and deep learning techniques for the early detection of heart irregularities. The developed model utilizes Long Short-Term Memory (LSTM) neural networks to analyze Electrocardiogram (ECG) data and proactively monitor heart rate variability, enabling timely interventions and potentially saving lives.

## Table of Contents

- [Features](#features)
- [Libraries & Dependencies](#libraries--dependencies)
- [Data Preprocessing](#data-preprocessing)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Getting Started](#getting-started)
- [Contributors](#contributors)
- [License](#license)

## Features

- **Early Detection:** The model is designed to identify heart irregularities at an early stage, allowing for timely medical interventions.

- **ECG Processing:** ECG data is preprocessed to extract relevant features that contribute to the model's predictions.

- **Proactive Monitoring:** Heart rate variability is monitored to provide insights into potential irregularities even before they become apparent.

## Libraries & Dependencies

The project utilizes the following libraries and dependencies:

- Keras
- NumPy
- pandas
- scikit-learn
- matplotlib

Refer to the source code for a comprehensive list of libraries used and their respective versions.

## Data Preprocessing

The ECG data is loaded from a CSV file and processed as follows:

- ECG data is cleaned and organized.
- The first three elements from each ECG row are extracted.
- Extracted features are converted from strings to float values.
- Extracted features are joined with the corresponding labels.

## Model Architecture

The LSTM neural network architecture consists of:

- Two LSTM layers for sequence analysis.
- Dropout layers to prevent overfitting.
- A dense output layer with ReLU activation.

The model is compiled with the Adam optimizer and binary cross-entropy loss.

## Training

The model is trained using a train-test split of the dataset. Early stopping is applied during training to prevent overfitting.

## Evaluation

The model's performance is evaluated using accuracy metrics. Training history is visualized to assess overfitting and convergence.

## Results

The trained model is capable of predicting heart irregularities with [mention accuracy/precision/recall/F1-score]. The project holds the potential to revolutionize cardiovascular healthcare by enabling proactive interventions.

## Getting Started

1. Clone this repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the project by executing `python main.py`.

## Contributors

- [Your Name](https://github.com/Bereketk100)

## License

This project is licensed under the [MIT License](LICENSE).
