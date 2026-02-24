# Data mining

Link to the dataset: https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data

# Run

Use `pip install -r requirements.txt`

# Folder structures

```
House-Price-Prediction-DM/
│
├── data/                      # Contain data (Do not upload on Git)
│   ├── raw/                   # Original data from Kaggle (train.csv, test.csv, data_description.txt)
│   └── processed/             # Cleaned data (data_cleaned.csv)
│
├── notebooks/                 # (Jupyter Notebook)
│   ├── 01_data_preprocessing.ipynb    # Code preprocessing (1st member)
│   ├── 02_baseline_models.ipynb       # Code Linear regression (2nd member)
│   ├── 03_advanced_models.ipynb       # Code SVR, Gradient Boosting (2nd member)
│   └── 04_visualize_decision.ipynb    # Code summary chart, feature importance (Leader/3th member)
│
├── reports/                   
│   ├── figures/               # Images/charts from code
│   ├── report_final.pdf        
│   └── slides_presentation.pdf
│
├── src/                       
│   └── utils.py               # useful global function (vd: RMSE, draw charts)
│
├── .gitignore                 
├── requirements.txt           
└── README.md                  
```