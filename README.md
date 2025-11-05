# Working-On-Taitanic-Dataset
Welcome! This repository contains my exploratory data analysis (EDA) and data-preparation work on the popular Kaggle Titanic dataset.

## 🚀 Project Goals

- **Clean** and preprocess the Titanic dataset for analysis and future modeling.
- **Explore** the dataset using statistical summary and powerful visualizations.
- **Engineer** new, meaningful features to boost prediction power.
- **Analyze** survival rates based on passenger characteristics.


## 📋 Workflow Summary

- **Data Loading:** Used pandas/numpy to load and inspect the data.
- **Data Cleaning:**
  - Missing values handled (mean/mode for 'Age' & 'Embarked', dropped 'Cabin')
  - Removed unnecessary columns like PassengerId, Ticket, and Cabin
  - Converted data types for better memory efficiency

- **Exploratory Data Analysis (EDA):**
  - Univariate analysis: Found most passengers were male, 3rd class, and in 20–40 age group.
  - Multivariate analysis: Higher survival for females and first-class passengers
  - Boxplots, countplots and histograms visualized distributions & relationships

- **Feature Engineering:**
  - Added new columns (e.g., `Family_size`, `family_type`: Alone/Medium/Large)
  - Encoded categorical features for model-readiness

- **Outlier Handling:** 
  - Detected and filtered out outliers in 'Age' and 'Fare' columns


## 📊 Key Insights

- Around 62% of passengers did not survive; females and 1st class passengers had higher survival rates.
- Most passengers traveled alone.
- Large proportion boarded from port 'S'.


## 🔗 How to Run

1. Download the notebook or clone this repository.
2. Open `titanic_analysis.ipynb` in Jupyter Notebook, VS Code, or Kaggle.
3. Make sure `train.csv` from the Titanic dataset is in the correct path.
4. Step through the notebook to see cleaning, EDA, feature engineering, and prepping for ML.


## 🤖 Next Steps

- Build and train ML models (e.g., logistic regression, decision trees)
- Evaluate model performance with metrics like accuracy and confusion matrix
- Interpret results and iterate on feature engineering
  

## 🙋 Author

Tarequl Islam  
Undergraduate Student, Statistics  
Passionate about Data Analytics, ML, and Practical Projects


**Feel free to fork, use, or improve—PRs welcome!**

