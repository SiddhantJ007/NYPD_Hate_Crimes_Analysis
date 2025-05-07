# NYPD Hate Crimes Analysis

## 📊 Overview
This project analyzes hate crime data from NYC, applies machine learning models, and provides insights and recommendations.

## 📁 Files
- `NYPD_Hate_Crimes_Analysis.ipynb` → Jupyter Notebook with all code and visualizations.
- `Report.pdf` → Detailed project report with insights and recommendations.
- `requirements.txt` → Python dependencies.
- `README.md` → Project overview and instructions.

## Prerequisites  
**Tested Python version:** 3.9.13  
(Other 3.9 patch releases should work, but 3.8 or 3.10+ may throw library errors.)

## If you have pyenv installed
- `pyenv install 3.9.13`        
- `pyenv local 3.9.13`            
- `python -m venv venv && source venv/bin/activate`
- `pip install -r requirements.txt`

## Installation
1. Clone the repo:
   ```bash
   git clone https://github.com/siddhantj007/NYPD_Hate_Crimes_ML_Project.git

2. Install the required packages:
   ```bash
   pip install -r requirements.txt

3. How to Use:
- Open the Jupyter Notebook
- Run the cells sequentially.

Models Used:
- Logistic Regression
- Random Forest
- XGBoost
Model evaluation with precision, recall, and F1-score

## Results
- Best model: XGBoost
- Recommendations: Improve with more diverse data and better feature engineering.

**macOS note:** XGBoost wheels require libomp.
Install once via Homebrew: `brew install libomp`.
