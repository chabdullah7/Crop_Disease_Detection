# Crop Disease Detection CNN

## Overview
This project implements a **Convolutional Neural Network (CNN)** for detecting diseases in **wheat and cotton leaves**. The notebook demonstrates:  
- Downloading and combining multiple leaf disease datasets  
- Data preprocessing and advanced augmentation (Random Erasing, MixUp, CutMix, Blur/Sharpen, Gaussian Noise)  
- Building a CNN from scratch for multi-class classification  
- Training with weighted Focal Loss to handle class imbalance  
- Evaluating model performance using accuracy, confusion matrix, and classification reports  
- Visualizing Grad-CAM to interpret model decisions  
- Exporting a mobile-optimized TorchScript model for deployment  

This project is particularly useful for **agriculture tech**, **crop health monitoring**, and **precision farming** applications.

## Features
- Clean preprocessing pipeline for wheat and cotton leaf images  
- Flexible CNN architecture with encoder blocks and dropout for regularization  
- Training loop with OneCycleLR scheduler, gradient clipping, and early stopping  
- Support for MixUp and CutMix data augmentation  
- Weighted Focal Loss for class imbalance  
- Performance evaluation with metrics and confusion matrix visualization  
- Grad-CAM visualizations to highlight disease-affected regions  
- TorchScript model conversion and mobile optimization  

## Files
- **Crop_Disease_Detection.ipynb** → Main notebook containing preprocessing, model, training, evaluation, Grad-CAM, and mobile export steps.  
- **best_advanced_crop_model.pth** → Saved best model checkpoint  
- **best_advanced_crop_model_traced.pt** → TorchScript traced model  
- **best_advanced_crop_model_mobile.pt** → Mobile-optimized TorchScript model  

## Results
The model outputs disease classifications for leaf images. Grad-CAM visualizations highlight areas influencing predictions.  
Example workflow:  

- Input leaf image  
- Model prediction with class probabilities  
- Grad-CAM overlay showing key regions influencing the prediction  

This allows visual and quantitative assessment of model performance.

## Author
Abdullah  
- GitHub: [github.com/chabdullah7](https://github.com/chabdullah7)  
- LinkedIn: [linkedin.com/in/ch-abdullah-b537951a](https://www.linkedin.com/in/ch-abdullah-b537951a)
