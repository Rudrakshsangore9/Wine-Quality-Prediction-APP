#  Wine Quality Prediction App  

A **Streamlit-based web application** that predicts the quality of **Red and White wines** using a trained **Random Forest Regressor** model. The app allows users to interactively select wine features via sliders and instantly receive a predicted wine quality score.  


## Features  
- Predict wine quality for **Red** and **White** wines.  
- Uses **Random Forest Regressor** models trained on the UCI Wine Quality dataset.  
- Input features through an **interactive slider-based UI** in Streamlit.  
- Scales input features for accurate predictions.  
- Provides predictions with accuracy improvements from z-score normalization and hyperparameter tuning.  
- Delivers **real-time results** with response times under 1 second.  

## Dataset  
The app uses the **Wine Quality dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality).  

- `winequality-red.csv` → Red wine samples (~1600 records)  
- `winequality-white.csv` → White wine samples (~4900 records)  

Each dataset contains physicochemical features such as acidity, sugar, pH, alcohol content, and quality scores (0–10).  

