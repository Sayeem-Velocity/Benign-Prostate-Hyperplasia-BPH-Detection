
# 🧬 BPH Detection using ResNet18 and SVM

## 🔍 Project Overview

This project focuses on detecting **Benign Prostate Hyperplasia (BPH)** using medical imaging and a deep learning pipeline. The approach integrates **ResNet18** for feature extraction and a **Support Vector Machine (SVM)** classifier to enable automated, accurate diagnosis.

---

## 🩺 About BPH

**Benign Prostate Hyperplasia** is a non-cancerous enlargement of the prostate gland, commonly affecting older men. Early detection is crucial for timely intervention and improved quality of life. This project aims to assist clinicians through a reliable AI-based detection system.

---

## 📂 Dataset

The dataset used is publicly available on Kaggle:
🔗 [BPH Detection Dataset](https://www.kaggle.com/datasets/shahriar26s/benign-prostate-hyperplasiabph-detection)

* Labeled medical images
* Categories: BPH and Normal

---

## 🛠️ Methodology

### 🔧 Preprocessing

* Resized all images to uniform dimensions
* Normalized pixel values
* Removed inconsistent or low-quality samples

### 🔄 Data Augmentation

* Applied random rotations, flips, and brightness shifts
* Aimed at enhancing model generalization and robustness

### 🧠 Model Architecture

* **Feature Extraction:** Pretrained **ResNet18** with final layers removed
* **Classification:** Extracted features passed to an **SVM** classifier

### 🏋️‍♂️ Training & Evaluation

* Dataset split into training and testing subsets
* SVM trained on deep features generated from ResNet18

---

## 📈 Results

| Metric   | Value |
| -------- | ----- |
| Accuracy | 95.5%   |

---

## 🚀 Future Work

* Experiment with architectures like **EfficientNet** and **ReXNet**
* Perform **hyperparameter tuning** for optimal performance
* Develop a **web-based interface** for clinical usability

---

## 📬 Contact

**S.M. Shahriar**
📧 Email: [sayeem26s@gmail.com](mailto:sayeem26s@gmail.com)
📊 Kaggle: [shahriar26s](https://www.kaggle.com/shahriar26s)
