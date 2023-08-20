# e-commerce-analysis

note: i havent even review the dataset yet, this is just a doodle brainfart

Lorem ipsum dolor imet

**Tools**

Tools used: Python, SQLite (DB Browser)

**Objective:**

1. Location thematic
   - Which city where the company has the largest transactions
   - Which area (zip code) where there is a significant number of buyer vs seller

2. Time Thematic
   - When usually customer purchase an order vs when they pay
   - How big (if any) there is a mismatch between estimated delivered time and actual delivered time

3. Product thematic
   - Which item is the best seller, what's their category and how much is the price
   - Which category is the best seller in each country
   - Weight of which item usually delivered, and their size (width, length, height)

**Columns to be combined**

1. Location thematic
   - ```customer_id``` unique id assigned to each order with the customer
   - ```geolocation_lat``` latitude
   - ```geolocation_lng``` longitude
   - ```geolocation_city``` city coordinates
   - ```geolocation_state``` state code
   - ```seller_city``` seller city
   - ```seller_zip_code_prefix``` seller city zip code
   - ```customer_city``` customer city
   - ```customer_zip_code_prefix``` customer city
   - ```geolocation_zip_code_prefix``` zip code



   - ```customer_unique-id```  unique id assigned to a single individual
   - ```customer_id``` unique id assigned to each order with the customer
   - ```geolocation_zip_code_prefix``` zip code
   - ```geolocation_lat``` latitude
   - ```geolocation_lng``` longitude
   - ```geolocation_city``` city coordinates
   - ```geolocation_state``` state code
   - ```customer_city``` customer city
   - ```customer_zip_code_prefix``` customer city
   - ```seller_city``` seller city
   - ```seller_zip_code_prefix``` seller city
   - ```order_purchase_timestamp``` 
