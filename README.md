# Predictive Modelling for Product Revenue Forecasting

## Overview
**Predictive Modelling for Product Revenue Forecasting in Retail, Manufacturing, and Distribution Industries** aims to revolutionize how businesses forecast sales revenue. By integrating an innovative conversational chatbot interface, this tool leverages Python and FastAPI on the backend along with React JS on the frontend to offer an intuitive, interactive avenue for data analysis.

## Problem Statement
Our project focuses on predicting sales revenue for specific products or categories across manufacturing, retail, and distribution sectors. We aim not just to forecast total revenue but to provide granular revenue predictions for each product based on their attributes. This informs critical business decisions related to analysis, investment, budgeting, and operational management.

## Data and Preprocessing
Utilizing data from the Olist E-commerce public dataset containing 100k orders from 2016 to 2018 in Brazil, we performed comprehensive cleaning and preprocessing:
- Removal of irrelevant columns and duplicates
- Dropping of null values
- Conversion of certain categorical variables to numerical formats
- Engineering a 'sales revenue' feature by multiplying 'item count' by 'item price'

## Analysis and Modelling
We employed three models for our analysis:
- **Linear Regression**: Demonstrated good predictive capability with an R-squared value of 85% for the training set, albeit with a high error level.
- **Decision Tree**: Showed a prediction accuracy of 78%, which improved upon optimization.
- **Random Forest**: Exhibited robust fit post-optimization with an R^2 score of 89% on the training set and 85% on the test set.

## Key Findings
- The **Linear Regression model** was decently accurate but showed limitations across the entire dataset.
- The **Decision Tree model** correctly estimated about 79% of sales changes, proving to be useful.
- The **Random Forest model** emerged as the most reliable for sales revenue prediction, marking its potential in business decision-making.

## Conclusion
The predictive modelling project for product revenue forecasting demonstrates the profound impact of advanced data analysis techniques in deciphering complex market dynamics. Our findings underscore the value of leveraging sophisticated models like Random Forest for their predictive prowess and adaptability. As we continue to refine our models and incorporate richer datasets, we anticipate providing even more accurate forecasts, further empowering businesses to make strategic decisions with confidence and precision.

## Dataset Wireframe Info

## Dataset Wireframe Info
```plaintext
Int64Index: 117329 entries, 0 to 117328
Data columns (total 38 columns):
 #   Column                         Non-Null Count   Dtype  
---  ------                         --------------   -----  
... [abbreviated for brevity] ...
35  seller_zip_code_prefix         117329 non-null  int64  
36  seller_city                    117329 non-null  object 
37  seller_state                   117329 non-null  object 
dtypes: float64(10), int64(6), object(22)
memory usage: 34.9+ MB
