🏠 Housing Data Analysis of Metropolitan Cities

📌 Project Overview

This project analyzes housing data from major metropolitan cities in India using Python. The goal is to explore the dataset, understand market trends, and derive insights about housing prices, locations, and amenities.

The dataset is taken from Kaggle: "Housing Dataset in Metropolitan Combined".

________________________________________

📂 Dataset Description

  •	Rows: 32,963

  •	Columns: 41

The dataset contains property listings across multiple metropolitan cities with details such as:

  •	Basic Info: City, Location, Price, Area, Bedrooms, Bathrooms

  •	Amenities: Gymnasium, Swimming Pool, Lift, Car Parking, 24x7 Security, Power Backup, etc.

  •	Property Type: Apartment, Villa, Builder Floor, etc.

  •	Other Features: Furnishing status, Transaction type, and additional facilities.

________________________________________

🔎 Steps Performed in the Notebook

1. Importing Libraries

  •	Loaded essential libraries: pandas, numpy, matplotlib, seaborn.

2. Data Loading & Exploration

  •	Loaded dataset (merged_files.csv) into a Pandas DataFrame.

  •	Displayed first & last rows (head(), tail()).

  •	Checked dataset shape → 32,963 rows × 41 columns.

  •	Used .info() and .describe() for data types, missing values, and summary stats.

3. Data Cleaning

  •	Identified null values and handled them where necessary.

  •	Converted data types (like numerical conversions for price/area).

4. Exploratory Data Analysis (EDA)

  •	Distribution of property prices and area.

  •	Price variation across cities.

  •	Average price per city.

  •	Top 10 locations with most listings.

  •	Top 10 locations with highest average price.

  •	Most common amenities across houses.


5. Feature Analysis

  •	Effect of Gymnasium on housing price.

  •	Effect of Swimming Pool on housing price.

  •	Correlation analysis (e.g., between price, area, and bedrooms).

6. Key Insights

  •	Mumbai has the highest total housing prices, followed by Delhi.

  •	Delhi has the highest average property cost, while Hyderabad is the most affordable.

  •	Noida leads in terms of housing demand with the most listings.

  •	Premium locations (like 15th Road) have the highest average prices, indicating luxury markets.

  •	Amenities like Gymnasium and Swimming Pool significantly increase housing prices.

  •	Strong correlation between area and number of bedrooms, while price is moderately correlated with area.

________________________________________

📊 Tools & Libraries Used

  •	Python

  •	Pandas – Data handling

  •	NumPy – Numerical operations

  •	Matplotlib / Seaborn – Data visualization

________________________________________

🚀 How to Run

  1.	Clone this repository:

  2.	git clone <your-repo-link>

  3.	Open the Colab Notebook:

  4.	Housing_Data_Analysis_of_Metropolitan_cities.ipynb

  5.	Run all cells sequentially to reproduce the analysis.

________________________________________

📌 Conclusion

This beginner project provides insights into real estate markets of Indian metropolitan cities. It highlights city-wise variations, location demand, and the role of amenities in pricing. The analysis can help real estate investors, buyers, and developers understand housing market trends.

________________________________________

✨ Next Steps (Future Work):

  •	Implement Machine Learning models to predict house prices.

  •	Build interactive dashboards for visualization.

  •	Expand analysis with time-series trends (if temporal data available).

________________________________________

✨ Made with Python, Pandas, Seaborn & Matplotlib.


