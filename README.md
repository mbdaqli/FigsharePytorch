# Brain Tumor MRI Classification

![Python](https://img.shields.io/badge/Python-3.8-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-1.9-red)
![License](https://img.shields.io/badge/License-MIT-green)

A deep learning project for classifying brain MRI scans to detect glioma tumors.
![Sample Images](FIgShareSHAP.png)
## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Results](#results)
- [SHAP Analysis](#shap-analysis)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Overview
This project implements a Convolutional Neural Network (CNN) in PyTorch to classify brain MRI scans as either containing glioma tumors or being tumor-free. The model is trained on grayscale MRI images and uses SHAP (SHapley Additive exPlanations) for model interpretability.

## Dataset
The dataset used is the [Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset) from Kaggle, containing:
- 926 glioma tumor images
- 937 no-tumor images
Results
The model achieved Accuracy of 99.29%.
![Results](Images/Plots)




## Model Architecture
The model consists of three convolutional blocks followed by fully connected layers.

![Model Architecture](images/model_architecture.png)


