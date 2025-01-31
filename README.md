# Computer vision course
 computer vision full course from university

# PPE Detection using SH17 Dataset

## Overview

 [ЗДЕСЬ НА РУССКОМ ЯЗЫКЕ](https://docs.google.com/document/d/1LkdvEmE2FLsYRguRhFOqCsodcBeHrmXkXWm6ov9KE-g/edit?usp=sharing)


This project focuses on detecting Personal Protective Equipment (PPE) using the SH17 dataset. The goal is to build a computer vision model capable of identifying whether individuals in images or video streams are wearing the necessary safety gear, such as helmets, vests, and gloves. This is particularly useful in industrial and construction environments to ensure safety compliance.

The project is implemented in Python using YoloV8, and it is hosted on Google Colab for easy access and experimentation.

---

## Table of Contents
1. [Project Description](#project-description)
2. [Dataset](#dataset)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Model Architecture](#model-architecture)
6. [Results](#results)
7. [Contributing](#contributing)
8. [License](#license)

---

## Project Description
The aim of this project is to develop a model for detecting Personal Protective Equipment (PPE) in images or video streams. The model is trained on the SH17 dataset, which contains annotated images of individuals wearing (or not wearing) safety gear like helmets, vests, and gloves.

The project is implemented as a Google Colab notebook, making it easy to run and experiment with without requiring local setup.

---

## Dataset
The SH17 dataset is used for training and evaluation. It includes:
- Images of workers in industrial settings.
- Annotations for PPE items such as helmets, vests, and gloves.
- Labels indicating whether the required safety gear is being worn.

The dataset is preprocessed and split into training, validation, and test sets to ensure robust model performance.

---

## Installation
To run this project, you need access to Google Colab. Follow these steps:

1. Open the notebook in Google Colab:
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sabahoth01/Computer-vision-course/blob/main/PPE_Detection_using_sh17_dataset.ipynb)

2. Ensure you have a Google account to save your progress and access GPU resources.

3. Run the notebook cells sequentially to install dependencies, load the dataset, train the model, and evaluate performance.

---

## Usage
1. **Training the Model**:
   - Run the cells in the notebook to preprocess the data, define the model architecture, and train the model.
   - The notebook includes options to use GPU acceleration for faster training.

2. **Testing the Model**:
   - After training, the model can be tested on the validation or test set to evaluate its performance.
   - You can also upload custom images or videos to test the model in real-world scenarios.

3. **Saving and Loading the Model**:
   - The trained model can be saved and loaded for future use, either in Colab or locally.

---

## Results
The model achieves the following performance metrics on the SH17 dataset:
- **Accuracy**: X%
- **Precision**: Y%
- **Recall**: Z%
- **F1-Score**: W%

Sample predictions are visualized in the notebook, showing bounding boxes and labels for detected PPE items.

---

## Contributing
Contributions to this project are welcome! If you'd like to contribute, please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request with a detailed description of your changes.

---


