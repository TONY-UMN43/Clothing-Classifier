# Clothing-Classifier (PyTorch)

## License
This project is for **viewing purposes only**.  
Do not copy, modify, or redistribute any part of this code without explicit permission.  
© 2025 Tony Akinyemi. All rights reserved.

A Deep Learning Project that explores **single-label**, using PyTorch. The goal was to use my own dataset of Pens and Pencils to train a Convolutional Neural Network Model that can make accurate predictions about any image that contains a pencil, pen, or both. 

# Project Highlights
- Created and Trained ResNet18 CNN Models using **PyTorch**
- Developed pipeline for **binary** classification
- Visualized results with **matplotlib** and **confusion matrices**
- Documented results in **Jupyter Notebook **
  
# This project scans an image of a pen or pencil and determines which writing utensil is in the image. 

# Technology Used
- Jupyter Notebook
- Python, PyTorch, PyTorchVision, PyTorchUtils
- Pre-Trained ResNet18
- SkLearnMetrics
- MatPlotLib for Visualization

# Model Files
🔗 [Download the pretrained model (44 MB)](https://drive.google.com/file/d/126_yqL9Ihc0xheJ7NPoVQx4rIppS64cU/view?usp=sharing)

# DataSet
- The DataSet was created by me

| Variation     | Training Set Size                             | Validation Set Size | Test Set Size |
|---------------|-----------------------------------------|----------|--------|
| ⚪️ Binary-Class  | 700 Images           | 150 Images | 150  Images  | 

# Variations of Model

| Variation     | Description                             | Training Accuracy | Testing Accuracy | Folder | DataSet |
|---------------|-----------------------------------------|----------|--------|--------|--------|
| ⚪️ Binary-Class  | Classify between shoes and socks                 | 98% | 91%    | [`/Binary-Class`](Socks-vs-Shoes-Classifier) |[`Binary-Class-DataSet`](https://drive.google.com/drive/folders/1Ge-QIjMrwEb83_CdX60tHpdv6QvaOkPr?usp=sharing) |


---

# Model Architecture (Binary)
- 3 Layer CNN
- ReLU Activation Functions
- MaxPooling & Dropout
- Cross-Entropy Loss Function
- Adam Optimizer

# Visualization
- Training vs Validation Plots
- Confusion Matrix
- Predictions with Labels
