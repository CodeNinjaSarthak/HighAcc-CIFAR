# HighAcc-CIFAR

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/python-3.x-blue)
![TensorFlow](https://img.shields.io/badge/tensorflow-2.x-orange)

## Overview

**HighAcc-CIFAR** is a deep learning project that demonstrates achieving high accuracy on the CIFAR dataset. The project explores the transition from a custom model with moderate performance to a state-of-the-art model using EfficientNetV2B0, resulting in an impressive 97.49% accuracy. This repository includes all necessary code, model training details, and evaluation metrics, including plots of accuracy, loss, and a confusion matrix.

## Project Highlights

- **Custom Model:** Initially trained a custom neural network achieving 66.64% accuracy.
- **EfficientNetV2B0:** Utilized a pre-trained EfficientNetV2B0 model, trained from scratch to boost accuracy to 97.49%.
- **Performance Visualization:** Plotted training vs. validation accuracy and loss, highlighting improvements.
- **Evaluation Metrics:** Detailed confusion matrix and accuracy plots to assess model performance.

## Dataset

The project uses the CIFAR dataset, a well-known benchmark for image classification tasks. The dataset includes 60,000 images categorized into 10 classes, with 50,000 images for training and 10,000 for testing.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/CodeNinjaSarthak/HighAcc-CIFAR.git
   cd HighAcc-CIFAR
