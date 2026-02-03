# **climate-impact-species-abundance**
Analysis of the correlation between temperature anomalies and terrestrial species abundance using XGBoost &amp; Random Forest.

## **Project Overview**
This project explores the relationship between global temperature anomalies and the relative abundance of terrestrial species. By integrating biological survey data with historical climate records, the analysis identifies critical thermal thresholds that impact population stability across various habitats.

## **Key Results**
- Model Accuracy: Achieved an 86% ROC-AUC using XGBoost and Random Forest to predict habitat suitability based on climate features.
- Thermal Thresholds: Identified that temperature anomalies exceeding +1°C correlate with a significant drop in the probability of high species abundance.
- Habitat Sensitivity: Discovered that Woodland and Semiarid habitats show higher volatility and more immediate population "crashes" following temperature spikes compared to Forest/Grassland mixes.

## **Methodology & Data**
Data Sources: Utilized the BioTIME database for species counts and NOAA/NASA datasets for global temperature anomalies.

## **Techniques:**
- Data Normalization: Applied Min-Max Scaling to compare relative abundance trends across habitats with vastly different raw population counts.
- Standardization: Utilized Z-score standardization to reveal hidden biological "pulses" in low-abundance environments.
- Machine Learning: Developed classification models (XGBoost, Random Forest) to evaluate the predictive power of temperature stability on ecological resilience.

## **Technologies Used**
- Language: Python
  -Libraries: Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn

## **How to Use**
- Clone the repository.
- Ensure you have the required libraries installed.
- Run the Jupyter Notebook to view the full analysis and visualizations.
