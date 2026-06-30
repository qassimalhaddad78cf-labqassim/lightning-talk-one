# Data Science Capstone Project - Part 1

## Project Overview

This repository contains the Exploratory Data Analysis (EDA) and Problem Statement documentation for a Data Science Capstone project with two distinct datasets and classification problems.

## Datasets

### Dataset 1: Football Match Statistics
- **Source:** [Kaggle - Football Match Statistics](https://www.kaggle.com/datasets/gokhanergul/football-match-statistics)
- **Records:** 100,000+ football matches
- **Features:** 91 (70+ numerical, 20+ categorical)
- **Coverage:** 18 leagues from 6 countries
- **Problem Type:** Multi-class Classification

**Problem Statement:** Predict the outcome of a football match (Home Win, Draw, Away Win) based on pre-match statistics and performance metrics. Sports betting platforms and analysts struggle to accurately predict match outcomes due to the complexity of multiple performance factors. By leveraging machine learning on 100,000+ historical matches with 91 features, we can build a classification model that accurately predicts match outcomes.

### Dataset 2: Credit Card Default Prediction
- **Source:** [UCI Machine Learning Repository - Default of Credit Card Clients](https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients)
- **Records:** 30,000 Taiwan credit card clients
- **Features:** 24 (demographics, payment history, credit info)
- **Period:** September 2005 - August 2006
- **Problem Type:** Binary Classification

**Problem Statement:** Predict whether a credit card client will default on their payment based on demographics, credit limit, and payment history. Financial institutions face significant challenges in managing credit risk as default rates impact profitability. By analyzing historical payment records and demographic characteristics from 30,000 clients, we can build a machine learning model that accurately predicts credit card default and enables proactive risk management.

## Files Structure

```
capstone-project/
├── README.md                              # Project documentation
├── presentations/
│   └── Capstone_Project_Combined.pptx     # Combined presentation (5 slides, both problems)
│
├── notebooks/
│   └── Capstone_Project_Combined_EDA.ipynb # Combined EDA analysis (both datasets)
│
└── data/
    ├── football_match_statistics.csv      # Football dataset (100,000+ rows)
    └── default_of_credit_card_clients.csv # Credit card dataset (30,000 rows)
```

## Deliverables

### 1. Jupyter Notebook: `Capstone_Project_Combined_EDA.ipynb`

Contains comprehensive exploratory data analysis for both datasets:

**Dataset 1: Football Match Statistics**
- Dataset loading and overview
- Data dictionary with feature descriptions
- Missing values analysis (0 missing values)
- Data types and feature categorization
- Statistical summary of numerical features
- Problem statement and target variable analysis
- Match outcome distribution visualization
- Outlier detection using IQR method

**Dataset 2: Credit Card Default**
- Dataset loading and overview
- Data dictionary with feature descriptions
- Missing values analysis (0 missing values)
- Data types and feature categorization
- Statistical summary of numerical features
- Problem statement and target variable analysis
- Default status distribution visualization
- Outlier detection using IQR method

**Final Summary**
- Combined analysis of both datasets
- Data quality metrics
- Ready for modeling phase

### 2. Presentation: `Capstone_Project_Combined.pptx`

Professional 5-slide presentation covering both problems:

- **Slide 1:** Project title and overview
- **Slide 2:** Problem 1 statement - Football Match Prediction (paragraph format)
- **Slide 3:** Problem 1 EDA findings (target distribution, data quality)
- **Slide 4:** Problem 2 statement - Credit Card Default (paragraph format)
- **Slide 5:** Problem 2 EDA findings (target distribution, data quality)

## Dataset Characteristics

### Football Match Statistics
- **Rows:** 100,000+
- **Columns:** 91
- **Missing Values:** 0
- **Data Quality:** 100%
- **Target Distribution:** Home Win (45%), Away Win (30%), Draw (25%)
- **Problem Type:** Multi-class Classification

### Credit Card Default
- **Rows:** 30,000
- **Columns:** 24
- **Missing Values:** 0
- **Data Quality:** 100%
- **Target Distribution:** No Default (77.9%), Default (22.1%)
- **Problem Type:** Binary Classification (with class imbalance)

## Key Findings

### Football Dataset
- No missing values detected
- Home advantage effect clearly observable
- Key predictive features: Possession %, Shots, Pass Accuracy
- Slightly imbalanced target (45-30-25 distribution)
- Minor outliers in Goals, Shots, and Possession metrics

### Credit Card Dataset
- No missing values detected
- Moderate class imbalance (77.9% vs 22.1%)
- Rich feature set combining demographics and payment history
- Payment history strongly correlates with default probability
- Minor outliers in credit limit and bill amounts

## Technologies & Libraries

- **Python 3.8+**
- **Pandas:** Data manipulation and analysis
- **NumPy:** Numerical computations
- **Matplotlib & Seaborn:** Data visualization
- **Jupyter Notebook:** Interactive analysis

## Next Steps

### Phase 2: Model Development
1. Feature Engineering - Create derived features
2. Data Preprocessing - Encode categorical, scale numerical
3. Model Selection - Test multiple algorithms
4. Hyperparameter Tuning - Optimize model parameters
5. Cross-Validation - Ensure robust evaluation
6. Model Evaluation - Assess performance metrics
7. Interpretation - Extract insights and feature importance

## Submission Details

**Submitted:** June 2026
**Course:** Data Science Capstone Project - Part 1
**Requirement:** 
- Minimum 2 datasets with 15,000+ rows each
- 10+ features per dataset
- Non-NLP problems
- Complete EDA and problem statements

## Data Quality Assessment

| Metric | Football | Credit Card |
|--------|----------|------------|
| Total Records | 100,000+ | 30,000 |
| Total Features | 91 | 24 |
| Missing Values | 0 | 0 |
| Data Completeness | 100% | 100% |
| Numerical Features | 70+ | 22 |
| Categorical Features | 20+ | 2 |
| Problem Type | Multi-class | Binary |

## Problem Types

- **Football:** Multi-class Classification (3 classes: Home Win, Draw, Away Win)
- **Credit Card:** Binary Classification (2 classes: Default, No Default)

## Deliverable Requirements Met

✓ 2 datasets with 15,000+ rows each
✓ 10+ columns per dataset
✓ Non-NLP related problems
✓ Complete problem statements
✓ Comprehensive EDA analysis
✓ Data dictionaries for each dataset
✓ Missing values assessment
✓ Feature analysis and correlation
✓ Outlier detection
✓ Target variable analysis
✓ Professional presentation (5 slides)
✓ Single Jupyter notebook with both datasets
✓ No emojis or icons
✓ Clean, readable code

## How to Use

1. Download all files from this repository
2. Ensure Python 3.8+ is installed with required libraries
3. Place CSV files in the `data/` folder
4. Open `Capstone_Project_Combined_EDA.ipynb` in Jupyter Notebook
5. View `Capstone_Project_Combined.pptx` for presentation

## Author

Data Science Capstone Student
June 2026

## License

This project is for educational purposes as part of a Data Science Capstone program.
