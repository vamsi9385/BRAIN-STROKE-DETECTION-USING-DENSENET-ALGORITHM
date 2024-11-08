# Brain Stroke Classification using DenseNet201

This project implements a deep learning model for classifying brain CT scans as either "stroke" or "normal" using the DenseNet201 architecture. The dataset consists of categorized images and the model is trained with transfer learning and fine-tuning.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset Structure](#dataset-structure)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Acknowledgments](#acknowledgments)

## Project Overview

This project uses TensorFlow and Keras to build a binary classification model. The model leverages transfer learning by using the DenseNet201 pre-trained on ImageNet.

## Dataset Structure

The dataset is divided into three directories:
- **Train**: 1843 images
- **Validation**: 235 images
- **Test**: 437 images

## Requirements

- Python 3.x
- TensorFlow 2.x
- Matplotlib
- scikit-learn

## Installation

Install the required packages by running:

```bash
pip install tensorflow matplotlib scikit-learn

#Place your dataset in the following structure:
Brain_Stroke_CT-SCAN_image/
├── Train/
├── Validation/
└── Test/
