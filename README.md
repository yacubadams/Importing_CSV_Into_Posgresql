# Importing_CSV_Into_Posgresql
Importing CSV file into Postgresql
CREATE TABLE olist_products_dataset (
  product_id VARCHAR(255) PRIMARY KEY,
  product_category_name VARCHAR,
  product_name_lenght INTEGER,
  product_description_lenght INTEGER,
  product_photos_qty INTEGER,
  product_weight_g INTEGER,
  product_length_cm INTEGER,
  product_height_cm INTEGER,
  product_width_cm INTEGER
)
