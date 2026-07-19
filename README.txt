# Airbnb Global Market Project

## Project Overview

This project analyses 250,000+ Airbnb listings and 5 million+ customer reviews across multiple international cities to understand market characteristics, identify key pricing factors, analyse demand trends, and provide data-driven investment recommendations.

The project combines exploratory data analysis, machine learning, and business intelligence dashboards to answer important questions for Airbnb hosts and potential investors.

---

## Business Questions

This project aims to answer:

- Which cities have the highest Airbnb market potential?
- Which markets are expensive, affordable, or highly competitive?
- What factors have the greatest impact on Airbnb pricing?
- How does traveller demand change over time and across seasons?
- Which cities and neighbourhoods provide the best investment opportunities?

---

## Dataset

The dataset contains:

- **250,000+ Airbnb listings**
- **5 million+ customer reviews**
- Multiple international cities

Data includes:

- Listing information (property type, room type, capacity, amenities)
- Host characteristics
- Pricing information
- Customer review ratings
- Location and neighbourhood information
- Monthly demand trends

Cleaned datasets and raw datasets (including data dictionary) are available here:

Raw datasets: https://drive.google.com/drive/folders/182INZ0DjOvrCZrSwb4y7l2W_uPoZ81r7?usp=sharing
Cleaned datasets: https://drive.google.com/drive/folders/1AxvUJfT-s6LYiLCCD1osmOGxndP4NQCe?usp=sharing

---

## Technologies Used

### Data Analysis & Visualisation
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

### Machine Learning
- Scikit-learn
- SHAP
- XGBoost

### Business Intelligence
- Power BI

---

## Machine Learning Models

Developed and compared multiple machine learning models to predict Airbnb pricing:

- Random Forest
- Gradient Boosting
- Extra Trees
- XGBoost

Model interpretation was performed using **SHAP analysis** to identify the most important price drivers.

---

## Power BI Dashboard

An interactive Power BI dashboard was developed to provide business insights into Airbnb markets.

The dashboard can be downloaded here:

https://drive.google.com/file/d/1Wt_WX8enCGt-HdAYEMdpvkaQYlIi-jQu/view?usp=sharing

Dashboard pages:

### 1. Market Overview
- City comparison
- Price distribution
- Average pricing
- Preferred Room Type 

### 2. Price Drivers
- Price vs Host Experience
- Impact of property characteristics (number of bedrooms, accommodations and amenities) on pricing

### 3. Demand Analysis
- Yearly demand trends
- Seasonal patterns
- Rating Performance Table

### 4. Investment Analysis
- High-potential cities
- Top-performing neighbourhoods
- Investment opportunity ranking

---

## Dashboard Preview

### Market Overview
dashboard1.png

### Price Drivers
dashboard2.png

### Demand Analysis
dashboard3.png

### Investment Analysis
dashboard4.png

### SHAP Feature Importance
shap.png

---

## Key Findings

- Property characteristics such as **accommodation capacity, bedrooms, and amenities** are important factors influencing Airbnb prices.
- Airbnb demand decreased significantly during COVID-19 and showed recovery afterwards.
- Certain neighbourhoods demonstrated strong demand despite limited supply, indicating potential investment opportunities.
- Market performance varies significantly across cities, highlighting the importance of location-based investment strategies.

---

## Project Structure

Airbnb-Market-Analysis/
│
├── notebooks/
│ ├── Data_Cleaning.ipynb
│ ├── Exploratory_Analysis.ipynb
│ └── Price_Prediction_Model.ipynb
│
├── dashboard/
│ ├── dashboard1.png
│ ├── dashboard2.png
│ ├── dashboard3.png
│ ├── dashboard4.png
│ ├── shap.png
│ └── Airbnb_Dashboard.pbix
│
├── data/
│ └── Data_Dictionary.xlsx
│
└── README.md