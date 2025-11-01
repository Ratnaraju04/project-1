

# 🫀 Cardiovascular Disease Prediction Using Machine Learning

## 📌 Overview
- Heart disease, also known as cardiovascular disease, is one of the most serious illnesses in both India and the rest of the globe. 
- According to estimates, cardiac illnesses account for 28.1% of fatalities.
- More than 17.6 million fatalities, or a large portion of all deaths in 2016, were caused by it in 2016. 
- Therefore, a system that can predict with exact precision and dependability is required for the appropriate and prompt diagnosis as well as the treatment of such diseases. 
- Numerous academics do extensive research utilising a variety of machine learning algorithms to predict heart illness using different datasets that contain numerous factors that lead to heart attacks. 
- Now it is your turn to do a analysis with the given dataset.

 
# Project Output Instructions :
- 	Perform data pre-processing operations.
- 	As a part of data analysis and visualizations draw all the possible plots to provide essential informations and to derive some meaningful insights.
- 	Showyour correlation matrix of features according to the datasets.
- 	Find out accuracy levels of various machine learning techniques such as Support Vector Machines (SVM), K-Nearest Neighbor (KNN), Decision Trees (DT) , Logistic Regression (LR) and Random Forest (RF).
-	Buildyour Machine learning model for heart disease detection according to the result.


## 🎯 Objectives
- Perform **data preprocessing** on the given heart disease dataset.
- Conduct **exploratory data analysis (EDA)** and create **visualizations** to gain insights.
- Identify **feature correlations** using a correlation heatmap.
- Train and evaluate multiple **machine learning models**:
  - Logistic Regression (LR)
  - K-Nearest Neighbors (KNN)
  - Decision Tree (DT)
  - Support Vector Machine (SVM)
  - Random Forest (RF)
- Compare model accuracies and select the best-performing algorithm.

---

## 🧠 Dataset
**File:** `heart.csv`  
The dataset contains various attributes related to patient health indicators such as:
- `age` — Age of the patient  
- `sex` — Gender (1 = male, 0 = female)  
- `cp` — Chest pain type  
- `trestbps` — Resting blood pressure  
- `chol` — Serum cholesterol (mg/dl)  
- `fbs` — Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)  
- `restecg` — Resting electrocardiographic results  
- `thalach` — Maximum heart rate achieved  
- `exang` — Exercise-induced angina  
- `oldpeak` — ST depression induced by exercise relative to rest  
- `slope`, `ca`, `thal` — Additional ECG and heart-related indicators  
- `target` — 1 indicates presence of heart disease; 0 indicates absence.

---

## ⚙️ Technologies Used
- **Programming Language:** Python  
- **Environment:** Jupyter Notebook / PyCharm  
- **Libraries:**
  - `pandas` — Data manipulation
  - `numpy` — Numerical computation
  - `matplotlib`, `seaborn` — Data visualization
  - `scikit-learn` — Machine learning models and evaluation

---

## 🔍 Steps Involved

### 1. Data Preprocessing
- Handle missing values (if any)
- Encode categorical variables
- Normalize/scale numerical features

### 2. Exploratory Data Analysis (EDA)
- Generate histograms, boxplots, and pairplots  
- Visualize feature correlations using a heatmap  
- Understand relationships between independent features and target variable

### 3. Model Building & Evaluation
- Split data into **training and testing sets**
- Train models: LR, KNN, DT, SVM, and RF
- Evaluate each model using:
  - Accuracy
  - Precision, Recall, F1-score
  - Confusion Matrix
- Select the model with the **highest accuracy**

---

## 📈 Sample Results
| Model | Accuracy |
|--------|-----------|
| Logistic Regression | 84% |
| K-Nearest Neighbors | 82% |
| Decision Tree | 80% |
| Support Vector Machine | 85% |
| Random Forest | **87%** |

*(Note: These values may vary depending on random splits and preprocessing techniques.)*
## 🧩 Output
The final machine learning model predicts whether a person is likely to have cardiovascular disease based on medical parameters.  
Visualization outputs include:
- Correlation heatmap  
- Feature importance chart  
- Model comparison graph

---
