This project focuses on detecting Benign Prostate Hyperplasia (BPH) using medical imaging data and a deep learning pipeline combining ResNet18 for feature extraction and Support Vector Machine (SVM) for classification.

🔍 Overview
Benign Prostate Hyperplasia is a non-cancerous enlargement of the prostate gland, common among older men. Early detection can help in timely treatment and better quality of life. In this project, we apply deep learning techniques to automate the detection process.

📂 Dataset
The dataset used in this project is available on Kaggle:
🔗 [BPH Detection Dataset](https://www.kaggle.com/datasets/shahriar26s/benign-prostate-hyperplasiabph-detection)

The dataset consists of labeled images categorized for BPH detection tasks.

🛠️ Methodology
Preprocessing
Image resizing and normalization
Cleaning inconsistent or noisy samples (if any)

Data Augmentation
Random rotations, flips, brightness adjustments, etc.
Improves model generalization and robustness

Model Architecture
Feature Extraction: Pretrained ResNet18 (with final layers removed)
Classification: Support Vector Machine (SVM) applied on extracted features

Training & Evaluation
Train/test split from dataset

📈 Results
Metric	Value
Accuracy	99%

📌 Future Work
1. Explore different architectures (e.g., EfficientNet, ReXNet)
2. Hyperparameter tuning for improved performance
3. Deploy the model using a web interface

📧 Contact
S.M. Shahriar
Email: sayeem26s@gmail.com
Kaggle: https://www.kaggle.com/shahriar26s
