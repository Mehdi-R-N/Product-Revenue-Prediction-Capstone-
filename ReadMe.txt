Capstone Project (Products Segmentation)

Questions:
We have products be able to predict: 
1.	Where are the optimal locations to sell our products?
2.	When is the best time to sell our products?
3.	At what price point should we sell our products?
4.	Who is the target customer base for our products?
5.	What type of promotions would be most effective for our products, and when should these be implemented?
6.	What are the key product attributes (quality, size, weight, etc.) that affect its sales performance?
7.	Which sales representative is best suited to sell each of our products?


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



