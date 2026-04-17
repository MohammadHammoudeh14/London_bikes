# London Bike Sharing Data Analysis 🚲

## Project Overview
This project provides a comprehensive analysis of the London Bike Sharing dataset from Kaggle. The goal was to understand how external factors like weather, temperature, and time of day influence the demand for bike rentals in London. The project covers the entire data pipeline, from cleaning the raw data using Python to visualizing key insights in an interactive Tableau dashboard.

## Dashboard Preview
Below is a static view of the final dashboard. The visualizations highlight key metrics, trends, and environmental impacts on bike rides.

![London Bikes Dashboard](https://github.com/MohammadHammoudeh14/London_bikes/blob/52058757f532086c281b65c1f4397fbd34f957c5/Screen%20Shot%202026-04-17%20at%2010.43.12%20PM.png?raw=true)

---

## Tools & Technologies Used
* **Python (Google Colab):** For Data Cleaning, Feature Engineering, and initial Exploratory Data Analysis (EDA).
* **Pandas:** For data manipulation and preparing the dataset for visualization.
* **Tableau:** For creating an interactive dashboard and advanced data visualization.

## Data Processing (The "Cleaning" Phase)
The raw data was processed using a Python notebook in Google Colab to ensure accuracy and readiness for Tableau:
1.  **Column Renaming:** Renamed cryptic or non-intuitive column names (e.g., `t1`, `hum`, `cnt`) to professional, readable names (`Temperature`, `Humidity`, `Count`).
2.  **Date/Time Parsing:** Adjusted data types for timestamps to enable time-based analysis (hourly, 20-day moving average).
3.  **Feature Preparation:** Prepared the data to facilitate analysis by hour, specific date ranges, and categorical weather states.

## Key Insights from the Dashboard
* **Weather Impact:** Contrary to some expectations, the highest number of rides (over 13,000) occurred during "Broken Clouds" weather, suggesting that common London weather patterns are not a significant deterrent for cyclists.
* **The Temperature/Wind "Sweet Spot":** A clear concentration of high ride counts exists when temperatures are between 10°C - 17°C and wind speeds are moderate (approx. 7-15 Kph).
* **Daily Demand Patterns:** The "Hour of Time" chart reveals distinct peaks during morning commute hours (around 8 AM) and evening commute hours (5-6 PM), indicating heavy utility usage for work.

## Files in this Repository
* `London_Bikes.ipynb`: The Google Colab notebook containing all Python code for data cleaning.
* `Screen Shot 2026-04-17 at 10.43.12 PM.png`: The dashboard screenshot image.
* `London_bikes_raw`: Raw dataset brfore cleaning and processing.
* `London_bikes_final`: Ready yo analyzing dataset. 

## Next Steps
* **Predictive Modeling:** Develop a Machine Learning regression model to predict future bike rental demand based on weather forecasts.
* **Temporal Expansion:** Incorporate seasonal trends and holidays more explicitly to refine the demand forecast.
