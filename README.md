# Handwritten Digit Classification

## Table of Contents
- [Overview](#overview)
- [Demo](#demo)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)

## Overview
A machine learning model that can recognize and identify handwritten digits (0-9) from images.

## Demo
Watch it [here](https://drive.google.com/file/d/1sjSvGlT1i74brNqmXFQyH_YxRUflUJu8/view?.usp=sharing).

## Features
- Trained on the MNIST dataset, featuring 28x28 grayscale images of handwritten digits from 0 to 9.
- Utilized a 4-layer neural network as the model architecture.
- Incorporated data preprocessing and cross-validation analysis to improve model performance. 

## Technologies Used
- **Language**: Python
- **Libraries**: TensorFlow, Scikit-learn, Matplotlib, NumPy

## Installation
1. **Prerequisites**: Install the following libraries:
   - Tensorflow
   - Scikit-learn
   - Matplotlib
   - Numpy
2. **Fork** this repository.
3. **Clone the repository**:  
   ```bash
   git clone https://github.com/<your_username>/Handwritten-Digit-Classification.git
   ```
4. **Navigate to the directory**:
   ```bash
   cd Handwritten-Digit-Classification
   ```

## Usage
1. Execute every code cell from top to bottom.
2. The last code cell, named "_For demonstration_", will randomly select an image from the test set, get the model's prediction for that image, and display the image, true label, and the model's prediction.
