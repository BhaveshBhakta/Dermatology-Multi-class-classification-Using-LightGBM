# 🧠 Dermatology Multi-Class Classification

## 📌 Project Overview

This project involves building a machine learning model to classify dermatological diseases based on clinical and histopathological features. The dataset includes 366 instances and 34 input features extracted from skin-related symptoms and diagnostics, with the target variable being the disease class (6 categories).

---

## ⚙️ Technical Highlights

* **Dataset Source**: [Kaggle - Dermatology Dataset Classification](https://www.kaggle.com/datasets/olcaybolat1/dermatology-dataset-classification)
* **ML Models Used**:

  * Logistic Regression
  * Decision Tree
  * Random Forest
  * Extra Trees
  * XGBoost
  * CatBoost
  * LightGBM
* **Best Model Accuracy**: Achieved high performance with Logistic Regression, Random Forest, Extra Trees, and CatBoost (`R² ≈ 0.973`).
* **Visualizations**:

  * Distribution plots, Violin & Boxplots
  * Feature Correlation Heatmap
  * t-SNE for 2D feature representation
  * Radar Chart, KDE, and Pairplots
* **Feature Importance**: Used Random Forest to rank key diagnostic features.

---

## 🎯 Purpose and Applications

* Assist dermatologists in automating the diagnosis of skin conditions.
* Serve as an educational tool for medical ML use-cases.
* Can be extended to real-time diagnostic tools integrated with clinical systems.

---

## 🛠️ Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/BhaveshBhakta/Dermatology-Multi-class-classification-Using-LightGBM.git
   cd Dermatology-Multi-class-classification-Using-LightGBM
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. (Optional) Download dataset from [Kaggle](https://www.kaggle.com/datasets/olcaybolat1/dermatology-dataset-classification) manually if not included.

---

## 🤝 Collaboration

Contributions are welcome! If you’d like to improve model performance, add new visualizations, or integrate the project with a web interface:

* Fork the repository
* Create a new branch
* Submit a pull request

