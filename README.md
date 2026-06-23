# Alfiya_CU_Project
Breast Cancer Detection Using SVM is a machine learning project that predicts whether a breast tumor is benign or malignant using medical diagnostic data. The system applies data preprocessing, feature scaling, and Support Vector Machine classification to assist healthcare professionals in early diagnosis.


# Breast Cancer Detection Using Support Vector Machine (SVM)

## 📌 Project Overview

Breast cancer is one of the leading causes of cancer-related deaths among women worldwide. Early detection plays a crucial role in improving treatment outcomes and survival rates.

This project presents a Machine Learning-based Breast Cancer Detection System using the Support Vector Machine (SVM) algorithm. The system analyzes medical diagnostic data and predicts whether a breast tumor is **Benign (Non-Cancerous)** or **Malignant (Cancerous)**.

The objective of this project is to demonstrate how Artificial Intelligence and Machine Learning can assist healthcare professionals in making faster and more accurate diagnostic decisions.

> **Note:** This system is intended as a decision-support tool and should not replace professional medical diagnosis.

---

## 🎯 Project Objectives

* Develop a breast cancer prediction model using SVM.
* Perform data preprocessing and feature scaling.
* Train and evaluate the machine learning model.
* Analyze model performance using various evaluation metrics.
* Visualize important insights from the dataset.
* Provide a simple and interpretable healthcare prediction system.

---

## 🏥 Dataset Information

**Dataset:** Breast Cancer Wisconsin Diagnostic Dataset

**Source:** UCI Machine Learning Repository

Dataset Characteristics:

* Total Records: 569
* Features: 30
* Classes:

  * Benign (B)
  * Malignant (M)
* Missing Values: None

Features include:

* Radius
* Texture
* Perimeter
* Area
* Smoothness
* Compactness
* Concavity
* Symmetry
* Fractal Dimension

---

## 🛠️ Technologies Used

| Technology   | Purpose                   |
| ------------ | ------------------------- |
| Python       | Programming Language      |
| Google Colab | Development Environment   |
| Pandas       | Data Processing           |
| NumPy        | Numerical Computation     |
| Matplotlib   | Data Visualization        |
| Seaborn      | Statistical Visualization |
| Scikit-Learn | Machine Learning          |
| Joblib       | Model Saving              |

---

## 🔄 Project Workflow

1. Data Collection
2. Data Exploration
3. Data Preprocessing
4. Feature Scaling
5. Train-Test Split
6. Model Training using SVM
7. Hyperparameter Tuning
8. Model Evaluation
9. Visualization
10. Model Saving and Prediction

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

* Dataset inspection
* Statistical summary
* Class distribution analysis
* Correlation analysis
* Feature importance exploration

Visualizations included:

* Class Distribution Plot
* Correlation Heatmap
* Confusion Matrix
* ROC Curve

---

## 🤖 Machine Learning Model

### Algorithm Used

**Support Vector Machine (SVM)**

Reasons for choosing SVM:

* Effective for binary classification
* Works well on medical datasets
* High accuracy
* Good generalization capability
* Handles high-dimensional data efficiently

### Kernel Used

* Radial Basis Function (RBF)

### Hyperparameters Tuned

* C
* Gamma
* Kernel Type

Grid Search Cross Validation was used to determine optimal parameters.

---

## 📈 Model Evaluation Metrics

The model was evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* ROC Curve
* AUC Score

### Formulae

**Accuracy**

Accuracy = (TP + TN) / (TP + TN + FP + FN)

**Precision**

Precision = TP / (TP + FP)

**Recall**

Recall = TP / (TP + FN)

**F1 Score**

F1 = 2 × (Precision × Recall) / (Precision + Recall)

---

## 📋 Results

The trained SVM model achieved excellent performance on the test dataset.

### Key Findings

* High classification accuracy
* Effective separation of benign and malignant tumors
* Low false-negative rate
* Strong ROC-AUC performance
* Suitable for healthcare decision-support applications

---

## 📷 Sample Visualizations

### Class Distribution

Shows the number of benign and malignant cases.

### Correlation Heatmap

Displays relationships among features.

### Confusion Matrix

Summarizes classification performance.

### ROC Curve

Illustrates model discrimination capability.

---

## 🚀 How to Run the Project

### Clone Repository

```bash
git clone https://github.com/your-username/Breast-Cancer-Detection-SVM.git
```

### Navigate to Project

```bash
cd Breast-Cancer-Detection-SVM
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Notebook

Open:

```text
breast_cancer_svm_simple_viva_ready.ipynb
```

using:

* Google Colab
* Jupyter Notebook

---

## 💻 Requirements

```text
numpy
pandas
matplotlib
seaborn
scikit-learn
joblib
```

Install all dependencies:

```bash
pip install -r requirements.txt
```

---

## 🔮 Future Enhancements

* Web Application using Flask/Django
* Mobile Application Integration
* Cloud Deployment
* Deep Learning-based Prediction
* Integration with Hospital Information Systems
* Real-time Diagnostic Dashboard

---

## 📚 Learning Outcomes

Through this project, the following concepts were learned:

* Machine Learning Fundamentals
* Classification Algorithms
* Support Vector Machines
* Data Preprocessing
* Feature Scaling
* Hyperparameter Tuning
* Model Evaluation
* Data Visualization
* Healthcare Analytics

---

## 👨‍🎓 Academic Information

**Project Title:** Breast Cancer Detection Using Support Vector Machine (SVM)

**Program:** Bachelor of Computer Applications (BCA)

**Domain:** Machine Learning / Healthcare Analytics

**Project Type:** Academic Final Year Project

---

## 📄 License

This project is developed for educational and academic purposes.

---

## ⭐ Acknowledgement

Special thanks to the UCI Machine Learning Repository for providing the Breast Cancer Wisconsin Diagnostic Dataset and to the open-source Python community for the tools and libraries used in this project.
