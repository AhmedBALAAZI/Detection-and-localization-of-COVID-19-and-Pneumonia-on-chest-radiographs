# Detection and localization of COVID 19 and Pneumonia on chest radiographs
## Overview

This repository contains the implementation of deep learning techniques for detecting and localizing COVID-19 lung lesions on chest radiographs. We utilized a multi-class classification approach with three deep learning architectures: DenseNet169, VGG16, and a custom sequential model. 

## Key Points

- **Objective**: Early diagnosis of COVID-19 using deep learning algorithms on chest X-rays.
- **Models Used**: DenseNet169, VGG16, and a non-pretrained sequential architecture.
- **Techniques**: Transfer learning and ensemble learning were employed to classify radiographs into three categories: "COVID", "Pneumonia", and "Normal".
- **Database**: The dataset consists of 3225 chest radiographs selected by a radiologist from the COVIDx-CXR version 8 database.
- **Results**: Achieved state-of-the-art results with accuracy values above 83% for individual models and up to 96% for ensemble models.
- **Visualization**: Class activation mapping (CAM) techniques were used to localize and visualize COVID lesions on chest radiographs.

## Getting Started

To get started with the code, please follow the instructions below.

### Prerequisites

- Python 3.x
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib


### Dataset

Available on : https://doi.org/10.6084/m9.figshare.25917340.v1

### Contributing
Contributions are welcome! Please open an issue or submit a pull request.

### License
This project is licensed under the MIT License - see the LICENSE file for details.

### Contact
For any questions, please contact [ahmed.balaazi@etudiant-fmt.utm.tn]
