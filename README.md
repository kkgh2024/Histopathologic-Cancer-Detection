# Histopathologic-Cancer-Detection

The aim of this project is to develop a deep learning algorithm that identifies metastatic tissues in histopathologic scans of lymph node sections using a deep learning technique—Convolutional Neural Network (CNN). Our goal is to classify cancerous tissues into two categories: Malignant (labeled as “1”) and Benign (labeled as “0”). This project seeks to understand the cancer detection process using a provided dataset, which consists of numerous small pathology images labeled as “1” or “0”.The task is to predict labels for images in the test folder. A positive label means that the central 32x32px area of a patch has at least one pixel of tumor tissue. Tumor tissue outside this area doesn't affect the label.

# Dataset Description
This dataset comprises numerous small pathology images requiring classification. Each file is identified by an image ID. The train_labels.csv file provides the true labels for images in the train folder. The training data consists of 220,025 images, while the test folder contains 57,458 images.
