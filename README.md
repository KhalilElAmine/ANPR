# ANPR
# Automated Number Plate Recognition (ANPR) Project



The Automated Number Plate Recognition (ANPR) Project offers an end-to-end solution for real-time license plate detection and recognition. It includes training a custom model using TensorFlow Object Detection (TFOD), license plate detection using a camera feed, and accurate number extraction using EasyOCR.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [Training a Custom Model](#training-a-custom-model)
  - [License Plate Detection and Number Extraction](#license-plate-detection-and-number-extraction)
- [Directory Structure](#directory-structure)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Overview

The ANPR Project seamlessly integrates TensorFlow's object detection, custom model training, license plate detection, and EasyOCR's text recognition to provide an efficient and accurate Automated Number Plate Recognition system.

## Features

- Training a custom model using TensorFlow Object Detection (TFOD).
- Real-time license plate detection using camera feed.
- Precise license plate number extraction using EasyOCR.
- TensorFlow Lite format for deployment on resource-constrained devices.

## Getting Started

### Prerequisites

- Python 3.7
- TensorFlow 2.7
- PyTorch
- EasyOCR
- Other dependencies (specified in `requirements.txt`)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/ANPR.git
   cd ANPR

## Usage

### Training a Custom Model
1. Follow the steps under [Setting Up Google Colab](#setting-up-google-colab) to open the `training.ipynb` notebook in Google Colab.
2. Instead of using the provided ANPR dataset, replace it with your own dataset. Make sure your dataset is organized in a similar structure as the provided dataset (images and corresponding annotations).
3. Modify the training steps and parameters in the notebook according to your dataset and requirements.
4. Execute each cell in the notebook to train your custom ANPR model.
5. Once training is finished, the model will be saved to your Google Drive.

1. Download the dataset from Kaggle (add specific instructions if required).

2. Open the "Training.ipynb" notebook for a step-by-step guide to training your custom model using TensorFlow Object Detection (TFOD).

## License Plate Detection and Number Extraction

