# Brain MRI Tumor Classification using CNN

This project implements a Convolutional Neural Network (CNN) using TensorFlow to classify brain MRI scans as **tumor** or **non-tumor**. The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection).

## 📁 Dataset
- Two folders: `yes/` (with tumor) and `no/` (without tumor)
- Resized to 128x128 and normalized

## 🧠 Model
- 2 Convolutional layers with MaxPooling
- Fully connected layer with dropout
- Binary output (sigmoid)

## 📊 Results
- Achieved ~94% test accuracy
- Evaluated using confusion matrix and classification report

## 🔧 Tech Stack
- Python, TensorFlow, OpenCV, Matplotlib, Seaborn, Scikit-learn

## 📌 How to Run
1. Install dependencies:
    ```
    pip install -r requirements.txt
    ```
2. Run `mri_classifier.ipynb` or `main.py`


