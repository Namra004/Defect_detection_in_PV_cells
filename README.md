# Defect Detection in Photovoltaic (PV) Cells using MobileNetV3

This project focuses on **automatic defect detection in photovoltaic (PV) cells** using **machine vision and deep learning**. A **MobileNetV3**–based convolutional neural network is trained to classify PV cell images as **defective** or **non-defective**, enabling efficient and reliable quality inspection.

---

## 📌 Motivation
I chose this project because it combines **computer vision, deep learning, and real-world industrial inspection**, which aligns strongly with my interest in applying machine learning to practical engineering problems such as renewable energy quality control.

---

## 🧠 Problem Statement
Manual inspection of PV cells is time-consuming and error-prone. This project aims to **automate defect detection** by learning visual patterns of defects directly from PV cell images.

---

## 🚀 Approach
- Used a **pretrained MobileNetV3Large** model for efficient feature extraction  
- Applied **transfer learning** and fine-tuning for binary classification  
- Performed **image preprocessing and augmentation** to improve generalization  
- Evaluated performance using precision, recall, F1-score, and accuracy  
- Visualized predictions and defect regions for qualitative analysis  

---

## 🧰 Technologies & Libraries
- Python  
- TensorFlow / Keras  
- MobileNetV3Large  
- OpenCV  
- NumPy, Pandas  
- Matplotlib  
- Scikit-learn  

---

## 📂 Dataset
- **Defective Solar Cells Dataset (Kaggle)**  
  https://www.kaggle.com/datasets/belalsafy/defective-solar-cells  

The dataset contains grayscale images of PV cells labeled as:
- `0` — Non-defective  
- `1` — Defective  

---

## 📊 Results
**Test Set Performance:**
