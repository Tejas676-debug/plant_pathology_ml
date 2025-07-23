# Plant Pathology 2020 - Traditional ML Image Classification

This project classifies plant leaf images into disease categories using **traditional machine learning techniques** and **handcrafted features**, without using transfer learning or deep learning.

## 🔍 Problem Statement

Classify images into multiple categories, such as identifying different species of plants or diseases, using handcrafted features and traditional ML models (SVM, Random Forest, Gradient Boosting).

Dataset: [Plant Pathology 2020 - FGVC7 (Kaggle)](https://www.kaggle.com/c/plant-pathology-2020-fgvc7)

---

## 📁 Dataset

- Provided `train.csv` contains image IDs and labels (one-hot encoded).
- Images are provided in `.jpg` format.
- Labels are converted into single-class format for multi-class classification.

---

## 🧪 Features Extracted

- **Color Histogram** (RGB channels)
- **Local Binary Pattern (LBP)** for texture

---

## 🧠 Models Used

- Support Vector Machine (SVM)
- Random Forest
- XGBoost Classifier

---

## 📊 Evaluation Metrics

- Accuracy
- Classification Report (Precision, Recall, F1-Score)
- Confusion Matrix

---

## 🛠️ How to Run

Run the notebook in Google Colab:

1. Upload the dataset ZIP file.
2. The notebook handles extraction and preprocessing.
3. Feature extraction and model training are done cell-by-cell.

---

## 📦 Requirements

See `requirements.txt`.

---

## 🔗 Author

- **Tejas Kharche**