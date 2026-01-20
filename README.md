## 🩺 COVID-19 Detection from CT Scan Images using TensorFlow

### 📌 Project Overview

This project focuses on detecting **COVID-19 from chest CT scan images** using deep learning techniques. A convolutional neural network (CNN) model is developed and trained using **TensorFlow** to classify CT images and assist in automated medical image analysis.

The project is based on the **COVIDx CT dataset** available on Kaggle and aims to demonstrate how deep learning can support medical diagnosis by analyzing CT scan data.

### 📂 Dataset

* **Dataset Source:** COVIDx CT Dataset (Kaggle)  https://www.kaggle.com/datasets/hgunraj/covidxct
* **Data Type:** Chest CT scan images
* **Classes:** COVID-19 positive and non-COVID cases
* The dataset contains labeled CT images collected from real clinical cases.

### 🧠 Model & Approach

* Built using **TensorFlow** and **Keras**
* A **Convolutional Neural Network (CNN)** architecture is used for image classification
* Image preprocessing steps include resizing, normalization, and data augmentation
* The model is trained to learn discriminative features from CT images to identify COVID-19 infections
