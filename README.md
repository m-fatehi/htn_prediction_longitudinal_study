# Hypertension Prediction a Longitudinal Study 

This repository contains the Jupyter notebooks used in our study:  
**"A comparison of machine learning algorithms for predicting hypertension incidence based on longitudinal study."**

The code demonstrates data preprocessing, model training with multiple ML algorithms (XGBoost, Random Forest, Logistic Regression, etc.), and visualization of performance metrics. The XGBoost model showed the best performance in predicting 10-year hypertension incidence.

---

## 📁 Files

### 1. `data_exploration.ipynb`

This notebook includes:
- Exploratory data analysis (EDA) of baseline characteristics
- Distribution analysis of numerical features (histograms, QQ plots)
- Summary statistics (mean ± SD or median [IQR]) and normality checks
- Generation of **Table 1**, a publication-style summary of baseline demographics and clinical variables stratified by hypertension outcome (HTN+ vs HTN–)
- Statistical comparisons using t-test, Mann-Whitney U, and chi-square tests
- Subgroup analysis by sex
- Visualizations including boxplots, bar charts, and density plots

### 2. `data_preprocessing_model_training.ipynb`

This notebook includes:
- Data loading and preprocessing
- Feature engineering
- Train/test split
- Training of multiple machine learning models (KNN, Logistic Regression, XGBoost, Random Forest, Neural Network)
- Model evaluation and result comparisons


---

## 📊 Dataset

This study uses data from the **MASHAD cohort**, which followed 5,198 normotensive individuals over 10 years, of whom 2,017 developed hypertension.

Due to ethical restrictions, the dataset is not publicly available. For access, please contact:

📧 **Dr. Habibollah Esmaily**  
[esmailyh@mums.ac.ir](mailto:esmailyh@mums.ac.ir)  
Mashhad University of Medical Sciences

---

## 📝 Citation

This section will be completed and updated once the paper is accepted for publication.

---

## 🛡️ License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
