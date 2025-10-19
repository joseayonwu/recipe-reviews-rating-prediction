# Recipe Reviews — Rating Prediction (1–5 Stars)

This repo contains my end-to-end analysis and classification models to predict exact star ratings (1–5) from the **Recipe Reviews** dataset.  
Scope includes **data cleaning**, **exploratory data analysis (EDA)**, **feature engineering**, **modeling** (Logistic Regression & Random Forest), and **evaluation** with accuracy, precision, recall, F1-score, and confusion matrices.

## Deliverables
- **Main notebook** (`recipe_reviews_analysis.ipynb`) – fully reproducible Jupyter notebook.
- **Data** (`recipe_reviews.csv`) – source dataset used in the analysis.
- **Figures/outputs** – saved charts and artifacts for quick review.

## Tech
Python, pandas, numpy, scikit-learn, matplotlib.

## Structure (target)
recipe-reviews-rating-prediction/
│
├── data/
│ └── recipe_reviews.csv
│
├── notebook/
│ └── recipe_reviews_analysis.ipynb
│
├── outputs/
│ └── (charts, metrics, or saved models)
│
└── README.md

## Notes
- Missing values were identified and cleaned.
- Models compared Logistic Regression and Random Forest for 1–5 star prediction.
- Class imbalance and feature importance were analyzed.
