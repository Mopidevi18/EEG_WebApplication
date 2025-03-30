# Emotion Classification Using EEG Data

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Web Application](#web-application)
- [Authors](#authors)
- [Acknowledgements](#acknowledgements)
- [References](#references)
- [License](#license)

## Overview
This project implements emotion recognition using EEG signals from the DEAP dataset. It leverages various deep learning architectures and preprocessing techniques to classify human emotions. The goal is to build an efficient and accurate emotion classification system that can be accessed via a user-friendly web application.

## Features
- **Data Preprocessing:**
  - Fast Fourier Transform (FFT)
  - Wavelet Transform
  - Correlation Coefficients (Pearson & Spearman)
- **Deep Learning Models:**
  - Convolutional Neural Network (CNN)
  - Long Short-Term Memory (LSTM)
  - Gated Recurrent Unit (GRU)
- **Web Application:**
  - Built a web application for interactive emotion classification from EEG data.
- **Performance:**
  - Best model (FFT + LSTM) achieves up to **93% accuracy** for two-class classification.
  - Developed an LSTM-based deep learning model with wavelet features for EEG emotion recognition, improving
 accuracy by 2% over the initial model to **86%** for ten-class classification.

## Installation
### Prerequisites
- Python 3.7 or higher
- Required Python libraries: TensorFlow/Keras, NumPy, Pandas, Dash, etc.

### Steps
1. **Clone the repository:**
   ```bash
   git clone <repo-url>
   cd <repo-directory>
