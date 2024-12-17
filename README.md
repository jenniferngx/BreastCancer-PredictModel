## 🩺 **Malignant Breast Cancer Prediction Model**
Using Machine Learning to Classify Benign and Malignant Breast Cancer Cases

---
## 🚀 **Project Overview**  
This project builds a **predictive classification model** using **R** to identify whether breast cancer tumors are **benign** or **malignant**. By leveraging multiple machine learning algorithms, this analysis explores performance metrics to determine the most accurate and reliable model for medical diagnosis.

The full report contains the end-to-end process: from data preprocessing and exploration to model building, evaluation, and insights.

---

## 🔍 **Key Objectives**  
1. Preprocess and analyze breast cancer datasets for model input.  
2. Build and compare classification models, including:  
   - **Logistic Regression**  
   - **Random Forest**  
   - **Support Vector Machine (SVM)**  
3. Evaluate model performance using key metrics like accuracy, precision, recall, and F1-score.  
4. Identify the most significant predictors of malignant breast cancer cases.  

---
## 🛠️ **Tools & Technologies**  
- **Programming Language**: R  
- **Libraries**: `caret`, `randomForest`, `e1071`, `gbm`, `ggplot2`, `dplyr`  

--- 
## 🧩 **Methodology**  

1. **Data Preprocessing**  
   - Imported the dataset using `read.csv`.  
   - Cleaned and scaled features for consistency.  
   - Handled missing values and split the data into **train** and **test** sets.

2. **Exploratory Data Analysis (EDA)**  
   - Used **ggplot2** to visualize key features and their relationships.  
   - Explored feature correlations and class distributions (benign vs. malignant).

3. **Model Building**  
   Implemented and compared multiple classification models:  
   - **Logistic Regression** (baseline model)  
   - **Random Forest**  
   - **Support Vector Machine (SVM)**   

4. **Model Evaluation**  
   Evaluated performance using the following metrics:  
   - **Accuracy**  
   - **Precision**  
   - **Recall**  
   - **F1-Score**  
   - **ROC-AUC Curve**
---

## 📊 **Results**  

| **Model**                | **Accuracy** | **Optimized Accuracy** |
|--------------------------|--------------|------------------------|
| Logistic Regression      | 95.18987%    | 96.20253%              |
| Random Forest            | 94.68354%    | 94.93671%              |
| Support Vector Machine   | 97.72152%    | 94.93671%              |


**Best Performing Model**: **Logistic Regression** is chosen for its balance of accuracy and interpretability, with 96.2% accuracy.

---

## 🔑 **Key Insights**  
- **Model Performance**: Logistic Regression was the top-performing model that balances accuracy and interpretability, with 96.2% accuracy.  
- **Feature Importance**: Features like **fractal dimension**, **smoothness**, **symmetry**, and **radius** were the most critical predictors of malignancy.  
- **Clinical Relevance**: These features provide valuable insights into the complexity, irregularity, and growth variability of tumors, offering support for oncologists in diagnosing breast cancer.


Read my [full paper](https://drive.google.com/file/d/1tUAjJn_6ZYH8GinAMr3lNKdx_RlYK2q-/view).
