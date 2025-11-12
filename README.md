# Mushroom Classification: Edible vs Poisonous

**Author:** Aanchal Gupta 
**Date:** 11 November 2025  

---


## Notebook
You can view the full Jupyter Notebook here:  
[**classification_aanchal.ipynb**](https://github.com/aanchalgt/ml_classification_aanchal/blob/main/classification_aanchal.ipynb)

---

## Peer Review
[classification_NathanSloss.ipynb](https://github.com/nwn8/applied-ml-nates/blob/main/notebooks/Midterm/classification_NathanSloss.ipynb)

---

## Project Overview
This project analyzes the **UCI Mushroom dataset** to predict whether a mushroom is **edible** or **poisonous** based on its physical features.  
The dataset contains **8,124 samples** and **23 categorical features** such as cap shape, cap color, odor, gill size, and stalk characteristics. The target variable is `class` (edible = 0, poisonous = 1).

---


## Dataset
- Source: [UCI Machine Learning Repository – Mushroom Dataset](https://archive.ics.uci.edu/ml/datasets/Mushroom)  
- All features are categorical; missing values are represented as `?` (notably in `stalk-root`).  
- Preprocessing includes handling missing values and one-hot encoding categorical features for model input.

---

## Methodology
1. **Data Exploration**: Explored feature distributions and checked for missing values.  
2. **Data Preparation**: Imputed missing values, one-hot encoded categorical features, and split data into training and test sets.  
3. **Model Training**:  
   - Logistic Regression  
   - Decision Tree Classifier  
4. **Evaluation**: Models were evaluated using accuracy, precision, recall, F1-score, and confusion matrices.  
5. **Comparison**: Compared performance of both models and discussed feature importance.

---

## Key Findings
- Both models performed very well, achieving **high accuracy (>95%)**.  
- Features such as **odor**, **gill-size**, and **cap-shape** were most predictive of mushroom edibility.  
- Decision Tree slightly outperformed Logistic Regression due to its ability to capture **non-linear feature interactions**.  
- Missing values were effectively handled by introducing a "missing" category.

---

## Conclusion
The Mushroom dataset demonstrates that categorical features like odor and gill characteristics can strongly predict mushroom edibility.  
Decision Tree models provide slightly better performance for this dataset, but both models are reliable for classification tasks.

---
