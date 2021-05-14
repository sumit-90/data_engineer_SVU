# data_engineer_SVU

Analyze our customer behavior and combine content into different data sets.

Task1: For task1 I have used started_streams.csv and whatson.csv datasets. I captured recent date from whatson.csv and filtered data according to product_code (TVOD and EST and joined those two dataframes using broadcast join to optimize it.

Task2: By grouping on columns ("device_name", "country_code", "product_type") I got the number of unique users and content count as per the date and product title.

Task3: By grouping on "genre", "user_id" I got the most popular Genre and what hours people watch.
