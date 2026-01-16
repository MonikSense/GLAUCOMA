# Glaucoma Detection Using Ensemble Machine Learning

This repository contains the source code and metadata used for glaucoma detection
using ensemble machine learning models and retinal fundus images.

---

## 📊 Dataset Description

The retinal fundus images used in this study are obtained from the publicly available
**Kaggle Glaucoma Dataset**:

🔗 https://www.kaggle.com/datasets/arnavjain1/glaucoma-datasets

Due to file size limitations, the image files are **not hosted directly** in this
GitHub repository.

The dataset includes:
- Fundus images
- Cropped and square images
- Segmentation masks for optic disc and cup

---

## 📁 Data Files in This Repository

- `data/image_labels.csv`  
  Contains image filenames and corresponding glaucoma labels used for training
  and evaluation.

---

## ⚙️ Preprocessing

- Gaussian blur is applied to cropped fundus images for noise reduction.
- Ground truth segmentation masks are kept unaltered.
- The CSV file is used only for image-label mapping.

---

## 🧠 Models Implemented

- Baseline models:
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Decision Tree

- Ensemble models:
  - Random Forest
  - Gradient Boosting
  - Soft Voting Ensemble

---

## 📈 Evaluation Metrics

The models are evaluated using:
- Accuracy
- Precision
- Recall (Sensitivity)
- F1-score
- ROC-AUC

---

## 🚀 How to Use

1. Download the dataset from Kaggle using the link above.
2. Place the fundus images locally.
3. Update image paths in the preprocessing or training scripts.
4. Run the provided Python scripts for preprocessing and model training.

---

## 📌 Notes

- Image files are referenced externally due to GitHub storage limits.
- This repository focuses on reproducibility of preprocessing and model training.

---

## 📜 License

This project is intended for academic and research use only.
Please follow Kaggle dataset licensing terms when using the images.
