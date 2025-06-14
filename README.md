# Clothing-Classifier (PyTorch)

## License
This project is for **viewing purposes only**.  
Do not copy, modify, or redistribute any part of this code without explicit permission.  
© 2025 Tony Akinyemi. All rights reserved.

A Deep Learning Project that explores **Binary Classification**, using PyTorch. The goal was to use my own dataset of Shoes and Socks to train a Convolutional Neural Network Model that can make accurate predictions about any image that contains a Shoe or Sock. 

While the initial version of this project only has binary classification between socks and shoes, the broader vision for 'Clothing-Classifier' is to expand it to multi-class classification between pants, shirts, socks, and shoes.

# Project Highlights
- Created and Trained ResNet18 CNN Models using **PyTorch**
- Developed pipeline for **binary** classification
- Visualized results with **matplotlib** and **confusion matrices**
- Documented results in **Jupyter Notebook **
- All visuals and results are in  [`this Folder`](Socks-vs-Shoes-Classifier)
  
# Project Description
This project was developed to demonstrate a real-life application for Binary Classification. At its core, this project uses the CNN Architecture to extract features from images and then uses those features to make predictions on new images that the model hasn't seen before. The Pre-Trained ResNet18 model was used for this Binary Classification task because the ResNet18 is a powerful model that can be used on small datasets to detect key features from a collection of images. Because of this, the model can make predictions with high accuracy and the training stage is quicker than a Custom Pytorch NN Model.

# Technology Used
- Jupyter Notebook
- Python (3.12), PyTorch, PyTorchVision, PyTorchUtils
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
| ⚪️ Binary-Class  | Classify between shoes and socks                 | 98% | 91%    | [`/Binary-Class`](Socks-vs-Shoes-Classifier) |[`Binary-Class-DataSet`](https://drive.google.com/file/d/1grDEHJwWNAAbU6TtLRKW3iQS_F0DfBns/view?usp=sharing) |


---

# Model Architecture (Binary)
- Pre-Trained ResNet18
- Froze the CNN Layers
- Changed Final Classifier layer to 1 neuron
- BCE-With-Logits-Loss Loss Function
- Adam Optimizer

# Visualization
- Training vs Validation Plots
- Confusion Matrix
- Predictions with Labels
