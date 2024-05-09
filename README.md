# Pneumonia_Detection_Hamoye_StoryBoard

---
title: Pneumonia Detection.App
emoji: 📚
colorFrom: pink
colorTo: green
sdk: streamlit
sdk_version: 1.34.0
app_file: app.py
pinned: True
license: mit
---

# Pneumonia Detection Model

This repository contains a deep learning model for detecting pneumonia from chest X-ray images. The model is built using TensorFlow and utilizes the ResNet50V2 architecture.

## Dataset

The dataset used for training and evaluation consists of chest X-ray images categorized into two classes: normal and pneumonia. The dataset can be obtained from [Kaggle](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia).

## Model Architecture

The model architecture is based on the ResNet50V2 convolutional neural network, pretrained on the ImageNet dataset. The final layer of the ResNet50V2 backbone is replaced with a Global Average Pooling layer followed by a Dense layer with sigmoid activation, making it suitable for binary classification.

## Results

The model achieved an accuracy of X% on the test dataset, with a precision of X% and recall of X%.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
