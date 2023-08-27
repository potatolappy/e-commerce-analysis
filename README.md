# e-commerce-analysis

a pacmannn SQL Wrangling project

**Tools**

- Jupyter Notebook, better suited for narrative story telling
- SQLite (DB Browser), somehow the dataset provided is in .db not .sql, so will be using this one

**Some key highlights of the project**

- Using z-scores parameter to detect outliers, and normalize the data
- cleaning / dropping null values
- formatting datatypes in SQL
- some visualizations using seaborne

**Objective:**

Finding out what insights that can be generated from the data

Theme: Location efficiency, identifying tier 1, 2 and 3 cities

1. Best selling product category
   conclusion: more marketing effort should be directed towards health, watches, bed & bath, sports & computer accessories 
  
2. Revenue generated in each city
   conclusion: Sao Paolo is a tier 1 city, almost 20% of revenue generated in this single city alone
   
5. most expensive logistic cost in each city
   conclusion: none of the top 10 most expensive city is also the most profitable one, consider reducing or relinquish office operation in that region

**Cleaning process**

1. inspecting shape and general info (done in Python)
2. inspecting null values (done in Python)
3. inspecting inconsistent datatype (done in SQL)
4. inspecting duplicates (done in Python)
5. inspecting outlier (done in python)

the analysis can be viewed at ```olist_analysis.ipynb``` while the file can be accessed at ```olist_data.csv``` and ```product_translation.csv``` to change portoguese -> english

the entire dataset can be found here: https://drive.google.com/drive/folders/1y-or_Rba1ambWkkNzhYKtRHRwC7g0A5n
