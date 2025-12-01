# House Price Prediction — Advanced Regression Project

*A complete end-to-end Machine Learning workflow for predicting real-estate prices.*

---

##  Project Overview

This project is a **full-stack regression pipeline** built on the famous Kaggle competition **"House Prices – Advanced Regression Techniques."**

The goal is to **predict the sales price of residential homes** using a combination of:

- Exploratory Data Analysis (EDA)
- Data Cleaning & Feature Engineering
- Outlier Treatment
- Handling Missing Values
- Encoding Categorical Features
- Feature Scaling
- Model Training & Evaluation
- Hyperparameter Tuning (GridSearchCV)
- Final Model Optimization (CatBoost)

This notebook was crafted with extreme attention to detail, ensuring that **every step is reproducible, intuitive, and technically solid**.

---

## Key Features of This Project

### Kaggle API Integration

Automated dataset download using Kaggle API inside the notebook. No manual downloading required.

### Deep EDA & Data Understanding

- Distribution plots
- Correlation heatmaps
- Target analysis
- Missing value profiling
- Relationship exploration with numerical & categorical features

### Data Preprocessing

A thorough preprocessing pipeline was implemented:

- Handling missing values using statistical & domain-driven strategies
- Log transformation for skewed features
- One-Hot Encoding for categorical variables
- Label Encoding where appropriate
- Standardization for numerical features
- Outlier filtering for extreme values
- Train/Test split following ML best practices

### Model Building & Benchmarking

Multiple algorithms were trained and compared:

| Model | Purpose |
|-------|---------|
| **Linear Regression** | Baseline model |
| **XGBoost** | Advanced boosting |

###  Final Optimized Model: XGBoost

CatBoost was selected as the final model because:

- Handles categorical data efficiently
- Robust against overfitting
- Provides superior RMSE performance
- Requires minimal manual encoding

###  Evaluation Metrics

The model performance was measured using:

- **RMSE (Root Mean Squared Error)** → Primary Kaggle competition metric
- **MAE (Mean Absolute Error)**
- **R² Score**

---

##  Dataset Description

The dataset includes **79 explanatory variables** describing:

- Lot size
- Building material
- Overall quality
- Neighborhood
- Basement & garage features
- Living area
- Year built
- Sale condition

###  Target Variable: SalePrice

The price of the home in USD.

---

##  Technologies Used

| Area | Tools |
|------|-------|
| **Programming Language** | Python |
| **Libraries** | Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib |
| **Advanced ML** | XGBoost |
| **Data Source** | Kaggle API |

---

##  Learning Outcomes

Through this project, I gained strong hands-on experience in:

- Data wrangling & preprocessing at real-world scale
- Analyzing skewness, correlations, and distributions
- Handling missing & categorical data systematically
- Designing complete ML pipelines
- Comparing traditional & boosting-based regression models
- Using GridSearchCV for hyperparameter optimization
- Building production-ready CatBoost regressors

This project strengthened my understanding of **regression algorithms, feature engineering, model tuning, and scientific ML experimentation.**

---

## Final Results

After multiple iterations, tuning cycles, and feature refinements:

### CatBoost achieved the best performance with the lowest RMSE.

This model is selected for final prediction and future deployment.

---

##  Project Structure

```
├── House_Price_Prediction.ipynb   # Main notebook
├── README.md                      # Project documentation
├── /data                          # Automatically downloaded via Kaggle API
└── /models                        # (Optional) Trained model files
```

---

##  Conclusion

This project demonstrates a **complete ML pipeline** starting from raw tabular data and ending with a **fully tuned, high-performance regression model**.

It showcases:

- My ability to implement end-to-end machine learning solutions
- Strong understanding of data preprocessing and regression modeling
- Hands-on experience with industry-relevant tools
- A structured, well-documented problem-solving approach

---

##  How to Run This Project

### Step 1 — Upload your Kaggle API key (kaggle.json)

Inside the notebook, run the upload cell.

### Step 2 — Execute the setup cells

This will install Kaggle API and download the dataset.

### Step 3 — Run the notebook step-by-step

Every block is clearly explained and produces immediate output.

---

##  Acknowledgements

Thanks to **Kaggle** for the dataset and the incredible community for providing invaluable insights and challenges.

---

##  License

This project is open source and available for educational and professional purposes.

---

**Happy Learning! **