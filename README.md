# 🩺 Diabetes Risk Prediction Using Statistics

A complete end-to-end statistics project using the **PIMA Indians Diabetes Dataset** from Kaggle.
This project applies every major concept in statistics — from descriptive analysis to machine learning — to predict whether a patient is at risk of diabetes.

---

## 📌 Project Overview

Diabetes is a chronic disease affecting millions worldwide. Early detection through data analysis can save lives.
This project uses real patient data to:
- Explore and clean the dataset
- Apply descriptive and inferential statistics
- Test hypotheses about which health features are significant
- Build a logistic regression model to predict diabetes risk

---

## 📂 Dataset

| Detail | Info |
|--------|------|
| **Name** | PIMA Indians Diabetes Dataset |
| **Source** | [Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database) |
| **Rows** | 768 patients |
| **Columns** | 9 (8 features + 1 target) |
| **Target** | Outcome (1 = Diabetic, 0 = Non-Diabetic) |

### Features:

| Feature | Description |
|---------|-------------|
| Pregnancies | Number of pregnancies |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure (mm Hg) |
| SkinThickness | Triceps skinfold thickness (mm) |
| Insulin | 2-hour serum insulin (mu U/ml) |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Diabetes likelihood based on family history |
| Age | Age of the patient |
| **Outcome** | **1 = Diabetic, 0 = Non-Diabetic** |

## 📊 Statistical Concepts Applied

| Phase | Concepts |
|-------|----------|
| **Phase 1 — Data Exploration** | Data types, missing values, zero imputation, class balance |
| **Phase 2 — Descriptive Statistics** | Mean, Median, Mode, SD, Variance, IQR, Skewness, Kurtosis |
| **Phase 3 — Visualizations** | Histograms, Box plots, Correlation heatmap, Scatter plots, Pie chart |
| **Phase 4 — Probability & Distributions** | Normal distribution, Shapiro-Wilk test, Q-Q plots, Z-scores, Bayes Theorem, Central Limit Theorem |
| **Phase 5 — Hypothesis Testing** | Two-sample t-test, Chi-square test, One-way ANOVA, Confidence intervals, Cohen's d |
| **Phase 6 — Logistic Regression** | Logistic regression, Odds ratio, Confusion matrix, Precision, Recall, F1 Score, ROC curve, AUC |

---

## 📈 Results

| Metric | Value |
|--------|-------|
| **Model** | Logistic Regression |
| **Accuracy** | ~83% |
| **AUC-ROC** | ~0.72 |
| **Top Predictor** | Glucose |
| **2nd Predictor** | BMI |

### Key Findings:
- ✅ **Glucose** is the strongest predictor of diabetes (p < 0.001, Large effect size)
- ✅ **BMI** is the second most important feature
- ✅ Patients with **BMI > 30** have significantly higher diabetes probability (Bayes Theorem)
- ✅ **Glucose and BMI** are the only features statistically significantly different between groups
- ✅ The model achieves **83% accuracy** with good Recall — important for medical diagnosis

---

## 📉 Figures Generated

| Figure | Description |
|--------|-------------|
| Figure 1 | Feature distributions by outcome (histograms) |
| Figure 2 | Box plots — spread and outliers |
| Figure 3 | Pearson correlation heatmap |
| Figure 4 | Scatter plots — key feature pairs |
| Figure 5 | Class distribution (pie chart) |
| Figure 6 | Q-Q plots — normality check |
| Figure 7 | Central Limit Theorem demo |
| Figure 8 | Hypothesis testing results (t-test, chi-square, ANOVA) |
| Figure 9 | Model evaluation (confusion matrix, ROC curve, coefficients) |

---


## 🛠️ Libraries Used

| Library | Purpose |
|---------|---------|
| `numpy` | Numerical computations |
| `pandas` | Data loading and manipulation |
| `matplotlib` | Plotting and visualizations |
| `seaborn` | Statistical visualizations |
| `scipy` | Hypothesis tests, normality tests |
| `scikit-learn` | Logistic regression, model evaluation |

---

## 📜 References

1. Smith, J.W. et al. (1988). *Using the ADAP Learning Algorithm to Forecast the Onset of Diabetes Mellitus.* — UCI ML Repository
2. Dataset: [Kaggle — PIMA Indians Diabetes](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
3. Montgomery, D.C. & Runger, G.C. — *Applied Statistics and Probability for Engineers*
