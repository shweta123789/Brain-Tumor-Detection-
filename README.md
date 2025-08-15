# Brain-Tumor-Detection-
Brain Tumor Detection uses deep learning and Convolutional Neural Networks (CNNs) to classify MRI brain scans and identify the presence of tumors. The model is trained on labeled medical images, achieving high accuracy in distinguishing between tumor and non-tumor cases, aiding in faster and more reliable diagnosis.



# 🧠 Brain Tumor Detection using CNN

This project implements a **Convolutional Neural Network (CNN)** model to detect the presence of brain tumors from MRI images. By leveraging deep learning, the system can classify MRI scans into tumor and non-tumor categories with high accuracy, aiding in faster and more reliable diagnosis.

---

## 🚀 Features
- **Deep Learning-based** classification using CNN.
- **High accuracy** in detecting tumor presence.
- **Data preprocessing** and augmentation for better generalization.
- **Visualization** of training and validation accuracy/loss.
- Works with **publicly available MRI datasets**.

---

## 📂 Project Structure

├── data/ # Dataset (not included due to size)
├── notebooks/ Brain Tumor Detection using CNN
├── src/ 
│ ├── preprocessing.py
│ ├── train.py
│ ├── evaluate.py
│ └── utils.py


---

## 📊 Dataset
The datasets used in this project are publicly available:

1. **Kaggle - Brain Tumor MRI Dataset**  
   📎 [https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection)

2. **Kaggle - Brain Tumor Classification (MRI)**  
   📎 [https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri](https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri)

---

🧠 Model Details

Architecture: Convolutional Neural Network (CNN)

Layers: Conv2D, MaxPooling, Dropout, Dense

Loss Function: Binary Crossentropy

Optimizer: Adam

Metrics: Accuracy
