Predictive Modelling for Product Revenue Forecasting in Retail, Manufacturing, and Distribution Industries

Problem Statement:
Our project focused on predicting sales revenue for specific products or categories across manufacturing, retail, and distribution sectors. We aimed to forecast not just total revenue but also the granular revenue of each product based on their attributes to inform business decisions related to analysis, investment, budgeting, and operational management.

Data and Preprocessing:

Data from the Olist E-commerce public dataset, containing 100k orders from 2016 to 2018 in Brazil, was cleaned and preprocessed. Irrelevant columns and duplicates were removed, null values dropped, and certain categorical variables were converted to numerical. A 'sales revenue' feature was engineered by multiplying the 'item count' with the 'item price'.

Analysis and Modelling:

Employed three models: Linear Regression, Decision Tree, and Random Forest. The Linear Regression model demonstrated a good predictive capability, with an R-squared value of 85% for the training set, but had a high error level. The Decision Tree model showed a prediction accuracy of 78%, improving upon optimization. The Random Forest model had variable performance, but post-optimization, it exhibited a robust fit with an R^2 score of 89% on the training set and 85% on the test set.

Key Findings:

While the Linear Regression model was decently accurate, it showed limitations across the entire dataset. The Decision Tree model correctly estimated about 79% of sales changes, proving useful. The Random Forest model emerged as the most reliable for sales revenue prediction, marking its potential in business decisions.



The dataset wireframe info:
Int64Index: 117329 entries, 0 to 117328
Data columns (total 38 columns):
 #   Column                         Non-Null Count   Dtype  
---  ------                         --------------   -----  
 0   order_id                       117329 non-null  object 
 1   order_item_id                  117329 non-null  int64  
 2   product_id                     117329 non-null  object 
 3   seller_id                      117329 non-null  object 
 4   shipping_limit_date            117329 non-null  object 
 5   price                          117329 non-null  float64
 6   freight_value                  117329 non-null  float64
 7   payment_sequential             117329 non-null  int64  
 8   payment_type                   117329 non-null  object 
 9   payment_installments           117329 non-null  int64  
 10  payment_value                  117329 non-null  float64
 11  customer_id                    117329 non-null  object 
 12  order_status                   117329 non-null  object 
 13  order_purchase_timestamp       117329 non-null  object 
 14  order_approved_at              117314 non-null  object 
 15  order_delivered_carrier_date   116094 non-null  object 
 16  order_delivered_customer_date  114858 non-null  object 
 17  order_estimated_delivery_date  117329 non-null  object 
 18  review_id                      117329 non-null  object 
 19  review_score                   117329 non-null  int64  
 20  review_comment_title           13892 non-null   object 
 21  review_comment_message         49679 non-null   object 
 22  review_creation_date           117329 non-null  object 
 23  review_answer_timestamp        117329 non-null  object 
 24  postal_code                    117329 non-null  int64  
 25  city                           117329 non-null  object 
 26  state                          117329 non-null  object 
 27  product_category_name          115634 non-null  object 
 28  product_name_lenght            115634 non-null  float64
 29  product_description_lenght     115634 non-null  float64
 30  product_photos_qty             115634 non-null  float64
 31  product_weight_g               117309 non-null  float64
 32  product_length_cm              117309 non-null  float64
 33  product_height_cm              117309 non-null  float64
 34  product_width_cm               117309 non-null  float64
 35  seller_zip_code_prefix         117329 non-null  int64  
 36  seller_city                    117329 non-null  object 
 37  seller_state                   117329 non-null  object 
dtypes: float64(10), int64(6), object(22)
memory usage: 34.9+ MB



