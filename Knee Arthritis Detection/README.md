# Knee Arthritis Detection Notebook

This repository contains a Jupyter Notebook for detecting knee arthritis using machine learning techniques. The notebook demonstrates the complete workflow from data loading, preprocessing, model training, evaluation, to prediction.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [References](#references)

## Overview

This notebook represents the application of Deep Learning for detecting the level of knee arthritis by a provided X-ray.

## Dataset

The [dataset](https://www.kaggle.com/datasets/hafiznouman786/annotated-dataset-for-knee-arthritis-detection) used in this notebook is assumed to be pre-split into the 5 categories (Normal, Doubtful, Mild, Moderate, Severe).
## Prerequisites

Before running the notebook, you need to have the following libraries installed:

- Python 3
- Jupyter Notebook
- Tensorflow
- Keras
- matplotlib
- numpy

## Installation

To set up your environment, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/akhundMurad/KneeArthritisDetection.git
    ```

2. Navigate to the project directory:
    ```bash
    cd KneeArthritisDetection
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To run the notebook, follow these steps:

1. Start Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

2. Open `KneeArthritisDetection.ipynb` in your Jupyter environment.

3. Follow the steps in the notebook to execute each cell. Make sure to run the cells to avoid any errors.

## Results

The notebook will output various results including data visualizations, model performance metrics, and predictions. Make sure to review the results section to understand the effectiveness of the model.

**As a result of the experiment, I tuned the model to increase validation accuracy from 35% to 82%.**

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please create a pull request or raise an issue.

## References

- Krizhevsky, A., Sutskever, I., & Hinton, G.E. (2012). ImageNet classification with deep convolutional neural networks. Communications of the ACM, 60, 84 - 90.
- Glorot, X., & Bengio, Y. (2010). Understanding the difficulty of training deep feedforward neural networks. International Conference on Artificial Intelligence and Statistics.
- Antony, J., McGuinness, K., Moran, K., & O’Connor, N.E. (2017). Automatic Detection of Knee Joints and Quantification of Knee Osteoarthritis Severity Using Convolutional Neural Networks. IAPR International Conference on Machine Learning and Data Mining in Pattern Recognition.
- Chollet, F. (2017). Deep learning with python. Manning Publications.
