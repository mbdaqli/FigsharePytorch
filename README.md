
# Brain Tumor Classification Project

## Overview
This project uses deep learning to classify brain MRI scans for tumor detection, specifically focusing on distinguishing glioma from normal brain tissue.

## Dataset
The dataset consists of brain MRI scans from [Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset) on Kaggle, containing labeled images of glioma and normal brain tissue.

## Methodology
- Created a CNN using PyTorch
- Trained on 128x128 grayscale MRI images
- Used SHAP for model explainability

## Results
The model achieved 92% accuracy on the test set. SHAP analysis revealed that the model focuses on tumor regions for positive predictions.

## How to Run
1. Clone this repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run the notebook or main script: `python main.py`

## Dependencies
- PyTorch
- NumPy
- Matplotlib
- scikit-learn
- SHAP
