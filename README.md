# Airbnb-EDA-Analysis
This project presents an exploratory data analysis (EDA) of Airbnb listings to uncover insights about pricing, availability, and geographical distribution. The analysis is done using Python libraries like pandas, NumPy, matplotlib, and seaborn
# Objective
The goal of this project is to:
1.Examine how different features (like minimum nights, number of reviews, and beds) influence the pricing strategy.
2.Explore the geographical distribution of listings to identify high-density areas and popular zones across the city.
3.Analyze room types, prices, and availability across different neighborhoods.
4.Understand host behavior and listing patterns.
5.Visualize host activity and review frequency to evaluate trust and engagement levels.
# Dataset
The dataset contains 20,765 entries and 22 features, including:

id: Unique identifier for each listing
name: Title of the Airbnb listing
host_name: Name of the host
neighborhood_group: Group (borough) where the listing is located
latitude/longitude: Geolocation of listings
price: Nightly rental price
room_type: Type of accommodation (e.g., entire home, private room)
reviews_per_month: Average monthly reviews for the listing
availability_365: Number of available days in the year

📊 Project Workflow
✅ Task 1: Importing Dependencies
All required libraries are imported: pandas, numpy, matplotlib.pyplot, and seaborn.

✅ Task 2: Loading Dataset
Dataset is read using pandas.read_csv() and stored in a DataFrame.

✅ Task 3: Initial Exploration
Displayed the first and last five rows using head() and tail().

Checked dataset dimensions using shape.

Used info() and describe() for data types and statistical summary.

✅ Task 4: Data Cleaning
Checked and dropped missing values.

Removed duplicate records.

Converted specific columns (id, host_id) to object types.

Ensured clean and consistent data for analysis.

✅ Task 5: Exploratory Data Analysis (EDA)
📌 Outlier Detection
Boxplot to identify and filter out extreme price values.

📌 Price Distribution
Histogram showing price spread with bins.

📌 Availability Analysis
Distribution plot for availability_365.

📌 Categorical Analysis
Barplot of average prices across neighbourhood_group and room_type.

📌 Reviews vs Price
Scatterplot of number_of_reviews vs price with neighbourhood_group as hue.

📌 Pairplot for Key Features
Relationships between price, minimum_nights, number_of_reviews, availability_365, grouped by room_type.

📌 Geographical Spread
Scatterplot of listings based on latitude and longitude, color-coded by room_type.

📌 Correlation Heatmap
Heatmap to analyze correlation between numerical variables like price, availability, beds, etc.

