TerraMind
Comprehensive Analysis of ML/DL Models for Spectral Index Prediction and Land Use Change Detection Using Sentinel-2 and Landsat-8 Imagery

🌍 Overview
TerraMind is a dual-path geospatial intelligence project that applies machine learning and deep learning models to:

Predict key spectral indices (NDVI, EVI, NDBI, BSI) from Sentinel-2 multispectral imagery using regression models.

Detect long-term land use and land cover (LULC) changes using Landsat-8 surface reflectance data via classification in Google Earth Engine (GEE).

This project demonstrates the integration of remote sensing data, cloud-based geospatial processing, and AI/ML for scalable environmental monitoring.

🛰️ Data Sources
Sentinel-2 (ESA): Used for index prediction via ML regressors

Landsat-8 (USGS/NASA): Used for 2013 vs 2023 land classification and change detection

Data processed using Google Earth Engine and Python (scikit-learn, NumPy, pandas)

🔍 Objectives
Predict vegetation and urban indices using ML/DL models

Evaluate performance of various models (Extra Trees, Random Forest, Gradient Boosting, etc.)

Detect decade-scale LULC transitions (2013–2023)

Visualize and quantify urbanization, vegetation loss, and barren land expansion

🧠 Models Used
Linear Regression

Ridge Regression

Random Forest

Extra Trees Regressor (Top Performer)

Gradient Boosting

Metrics:

R² Score

MAE & RMSE

Relative Accuracy

🌐 Tools & Platforms
Google Earth Engine (GEE) – For image preprocessing, classification & change detection

Python – For modeling and evaluation (scikit-learn, matplotlib)

Jupyter Notebook – For pipeline development

GeoTIFF/CSV – For data handling

📊 Key Results
Extra Trees Regressor achieved ~94.5% overall accuracy for spectral index prediction

Random Forest Classifier used in GEE highlighted ~16.3% increase in urban area and ~13.7% decrease in vegetation from 2013 to 2023

Visual classification maps and change masks validated observed spatial transformations

📌 Applications
Urban planning

Environmental monitoring

Policy-making for climate resilience

Sustainable land management

🧭 Future Work
Integrate CNNs/LSTMs for spatial-temporal modeling

Fuse climate and socio-economic data for deeper insights

Apply to other regions under environmental stress
