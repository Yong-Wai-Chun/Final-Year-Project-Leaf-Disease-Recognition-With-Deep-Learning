<h1 align="center">
  MMU's FINAL YEAR PROJECT: Leaf Condition Analysis Using Convolutional Neural Network and Vision Transformer
</h1>

## Introduction
This project is about proposing a hybrid model of customized Convolution Neural Network (CNN) model and a standard Vision Transformer (ViT) model on leaf disease recognition. In the end, a comparative analysis with other state-of-the-art Deep Learning models are displayed to show the findings. Datasets are called "New Plant Diseases Dataset".

## Brief Methodology
<p align="center">
  <img width="60%" src="https://github.com/Yong-Wai-Chun/miscellaneous/blob/main/pic/Screenshot%202024-10-28%20002017.png?raw=true">
  <br> Figure 1: Methodology Pipeline
</p>

1. CNN (Backbone): Convolutional layers for feature map extraction, pooling for spatial downsizing, batch normalization and ReLU activation function.
2. ViT (2nd layer processing + classifier): Patch + position embedding, transformer encoding, attention modules and MLP classifier.

## Comparative Analysis with State-of-the-Art Models & Findings
<p align="center">
  <img width="60%" src="https://github.com/Yong-Wai-Chun/miscellaneous/blob/main/pic/Screenshot%202024-10-28%20003910.png?raw=true">
  <br> Figure 2: Comparative Analysis
</p>
When it comes to accuracy, speed, and resource usage. The proposed method has the most balanced and optimized results compared among the other methods. For more details, kindly read the poster and the research paper as attached.

The journal paper has been published to the International Journal of Computing and Digital Systems, DOI: http://dx.doi.org/10.12785/ijcds/1601125

https://hdl.handle.net/20.500.14536/5494

## Steps for Running & Testing

1. Download the dataset from the Kaggle link
2. Go through the steps and run the file of Pre-processing.ipynb first
3. Run FYP_models.ipynb
4. Finally run the GUI.py for the streamlit apps testing.

## Reference
https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset
