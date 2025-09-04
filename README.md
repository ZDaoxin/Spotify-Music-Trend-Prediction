# Spotify Music Trend Prediction (2017–2023 → 2024)

## 📌 Overview
This project applies **machine learning techniques** to analyze Spotify’s *Top 200 Global* dataset (2017–2023, ~650K tracks) and forecast **music genre trends for 2024**.  
The study was conducted as part of an academic team project, focusing on **data preprocessing, clustering, time series forecasting, and supervised learning models**.

## 🎯 Objectives
- Predict which **music genres** are likely to dominate in 2024.  
- Compare the performance of multiple machine learning models.  
- Provide insights that could support strategic decisions such as licensing, artist collaboration, and recommendation systems.  

## 🛠 Methods & Workflow
1. **Data Preprocessing**  
   - Removed duplicates, irrelevant fields, and outliers (Gaussian filtering).  
   - Standardized features for consistency.  

2. **Feature Engineering**  
   - Applied **K-means clustering** on 7 track features (Danceability, Energy, Loudness, Speechiness, Acousticness, Instrumentalness, Valence).  
   - Derived 5 representative genres:  
     - Rock/Alternative  
     - Dance/Electronic  
     - Jazz/Classical  
     - Hip-hop/Rap  
     - Pop/R&B  

3. **Dimensionality Reduction**  
   - Used **PCA** for visualization and data distribution analysis.  

4. **Predictive Modeling**  
   - Implemented and compared:  
     - **Linear Regression**  
     - **Random Forest**  
     - **SARIMA (time-series)**  
     - **LSTM (RNN)**  
   - Evaluated with **MSE, MAE, R²** and **5-fold cross-validation**.  

## 📊 Results
- **Random Forest** achieved the best overall performance (Validation MSE ≈ 3276).  
- Predicted **Dance/Electronic** as the most dominant genre in 2024.  
- **Rock/Alternative** showed an upward trend.  
- **Hip-hop/Rap** and **Jazz/Classical** remained relatively stable with smaller market share.  

## 👥 Team Contribution
- Data preprocessing, clustering, and regression models.  
- Time-series modeling with SARIMA.  
- Implementation of Random Forest and PCA.  
- LSTM model development and Spotify API integration.  


## 🚀 Technologies Used
- Python (pandas, numpy, scikit-learn, statsmodels, keras, matplotlib)  
- Machine Learning & Time-Series Forecasting  
- Spotify API (for data reference)  

## 📖 License
This project is for academic purposes. Please cite or reference if used.  


