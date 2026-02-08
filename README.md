# Chicago Airbnb Price Analysis

## Overview
This project analyzes 8,000+ Airbnb listings in Chicago to uncover **pricing patterns, demand signals, and neighborhood-level insights**. The goal is to translate raw listing data into **clear, business-relevant findings** that could support pricing strategy and market understanding.

## Business Questions
- Which Chicago neighborhoods command the highest median nightly prices?
- How does price differ by room type (entire home vs. private room)?
- Which listing features are most strongly associated with higher prices?
- What factors appear related to stronger demand (reviews and ratings)?

## Key Insights
- **Entire homes/apartments** consistently have higher median prices than private or shared rooms  
- **Location (neighborhood + latitude/longitude)** is the strongest driver of price variation  
- **Bedrooms and beds** show a strong positive relationship with price, with diminishing returns at higher counts  
- Listings with **higher review activity** tend to cluster in mid-priced ranges rather than luxury extremes  

## Analysis Approach
- Data cleaning and validation on a pre-processed dataset  
- Exploratory Data Analysis (EDA) using summary statistics and visualizations  
- Grouped analysis by neighborhood and room type  
- Correlation analysis to identify price drivers  
- Simple regression used **only to quantify relationships**, not as a predictive ML product  

## Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn (basic regression only)

## Files
- `Chicago Airbnb Analysis Project.ipynb` — full exploratory analysis and visualizations  
- `listings_chicago_clean.csv` — cleaned dataset used for analysis
