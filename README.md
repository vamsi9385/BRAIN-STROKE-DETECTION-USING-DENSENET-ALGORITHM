# BRAIN-STROKE-DETECTION-USING-DENSENET-ALGORITHM
his project implements a deep learning model for classifying brain CT scans as either "stroke" or "normal" using the DenseNet201 architecture. The dataset consists of categorized images and the model is trained with transfer learning and fine-tuning.

Table of Contents

-Project Overview
Dataset Structure
Requirements
Installation
Usage
Model Training
Evaluation
Results
Acknowledgments
Project Overview

This project uses TensorFlow and Keras to build a binary classification model. The model leverages transfer learning by using the DenseNet201 pre-trained on ImageNet.

Dataset Structure

The dataset is divided into three directories:

Train: 1843 images
Validation: 235 images
Test: 437 images
Requirements

Python 3.x
TensorFlow 2.x
Matplotlib
scikit-learn
Installation

Install the required packages by running:

pip install tensorflow matplotlib scikit-learn
Usage

Place your dataset in the following structure:
Brain_Stroke_CT-SCAN_image/
├── Train/
├── Validation/
└── Test/
Run the Jupyter notebook to train and evaluate the model.
Model Training

The model is trained using:

Transfer learning with DenseNet201
Binary cross-entropy loss
Adam optimizer
Fine-Tuning
After initial training, the model fine-tunes by unfreezing some layers of DenseNet201.

Evaluation

The model is evaluated using:

Accuracy
Precision, Recall, F1-score
Loss plots
Results

Test Accuracy: Achieved an accuracy of ~90% on the test dataset.
F1 Score: Evaluated to highlight the balance between precision and recall.
Acknowledgments

This project is based on TensorFlow's transfer learning framework.
Dataset used for training and testing the model is sourced from your provided directory.
