# Hands-On End-to-End Machine Learning Models
### Final Term Project

**Name:** Lu'luah Buhairah  
**NIM:** 1103220134  
**Class:** Machine Learning Class

---

## 📌 Project Overview
This repository contains the submission for the Final Term Exam: **"Hands-On End-to-End Models Machine Learning"**. The goal of this project is to demonstrate the ability to build complete machine learning pipelines across different domains: Fraud Detection, Regression, and Image Classification.

The project consists of three main notebooks, covering data preprocessing, model training, and evaluation.

---

## 📂 Repository Contents

### 1. Fraud Detection Pipeline
* **File:** `1_Fraud_Detection_Pipeline.ipynb`
* **Domain:** Classification (Imbalanced Data)
* **Objective:** Predict the probability of a transaction being fraudulent (`isFraud`) using the IEEE-CIS Fraud Detection dataset.
* **Key Steps:**
  * Data Loading & Cleaning (Handling missing values).
  * Feature Engineering & Encoding.
  * Handling Class Imbalance.
  * Model Training & Evaluation using appropriate metrics.

### 2. Audio Year Prediction (Regression)
* **File:** `2_Audio_Regression_Pipeline.ipynb`
* **Domain:** Regression
* **Objective:** Predict the release year of a song based on its audio features using the YearPredictionMSD dataset.
* **Key Steps:**
  * Data Preprocessing (Scaling features).
  * Train-Test Split.
  * Implementation of Regression Models.
  * Performance Evaluation (RMSE, R2 Score).

### 3. Fish Image Classification (CNN)
* **File:** `3_Fish_CNN_Classification.ipynb`
* **Domain:** Computer Vision / Deep Learning
* **Objective:** Classify fish species from the Fish Image Dataset.
* **Key Steps:**
  * **Data Pipeline:** Optimized data loading using `tf.data` to prevent memory issues.
  * **Augmentation:** Applied RandomFlip, Rotation, and Zoom to increase model robustness.
  * **Modeling:**
    * **CNN From Scratch:** Custom architecture implementation.
    * **Transfer Learning:** Utilization of MobileNetV2 for improved accuracy.
  * **Interpretability:** Visualization of Feature Maps to understand model focus.

---

## 🚀 How to Run
All notebooks are designed to be run on **Google Colab**.

1. **Clone or Download** this repository.
2. Open the `.ipynb` files in [Google Colab](https://colab.research.google.com/).
3. **Upload Dataset:**
   * Ensure the required datasets (csv or image folders) are uploaded to your Google Drive or Colab Runtime environment.
   * Update the file paths in the first code cell if necessary.
4. **Execute:** Run all cells sequentially (`Runtime` > `Run all`).

---

## 🛠 Tools & Libraries
* **Python**
* **TensorFlow / Keras**
* **Scikit-Learn**
* **Pandas & NumPy**
* **Matplotlib & Seaborn**

