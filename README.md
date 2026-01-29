# Financial Investment Analytics – Madrid Real Estate Case Study

## Overview
This project presents a large-scale data analysis of Madrid’s real estate market with the goal of supporting investment decision-making through data-driven insights.

Using a dataset of over 100,000 properties, the analysis focuses on identifying patterns, undervalued assets and risk–return profiles across different districts. Although the domain is real estate, the analytical approach and methodology are directly applicable to financial services, risk analytics and anomaly detection contexts.



## Data
- 100,000+ property records with 39 features
- Property characteristics, pricing and location data
- Separate analysis of sales and rental markets
- Data includes numerical, categorical and geospatial attributes

The dataset required careful preprocessing due to missing values, outliers and heterogeneous feature distributions.



## Methodology
The analysis follows an end-to-end data science workflow:

- Data cleaning and validation
- Exploratory data analysis (EDA) and outlier handling
- Feature engineering (price per m², rental yield, segmentation indicators)
- Market segmentation (sales vs rentals)
- Predictive modeling using Random Forest Regressors
- Model evaluation using MAE and R² metrics



## Key Insights
- Clear differentiation between premium and emerging districts
- Identification of undervalued properties with attractive risk–return profiles
- Strong influence of location, property size and amenities on pricing dynamics
- Distinct drivers for sales prices versus rental prices



## Business Value
The results of this analysis support:
- Investment screening and prioritization
- Risk-aware capital allocation
- Portfolio diversification strategies

The same analytical framework can be adapted to transaction monitoring, anomaly detection and risk assessment use cases in financial services and fintech environments.



## Repository Structure
- `/notebooks/` – Reproducible analysis and modeling code
- `/report/` – Detailed case study report with visualizations and conclusions
- `/data/` – Data availability notes
- [Analysis Notebook](notebooks/madrid_real_estate_investment_analysis.ipynb)
- [Case Study Report (PDF)](report/madrid_real_estate_investment_case_study.pdf)



## Reproducibility
The analysis notebook is provided without stored outputs to keep the repository lightweight.
All figures, tables and results can be reproduced by running the notebook locally.

The main findings and visual results are summarized in the accompanying PDF report.

Users interested in exploring the full outputs can download and execute the notebook locally.



## Tools & Technologies
Python, pandas, NumPy, scikit-learn, Jupyter Notebooks
