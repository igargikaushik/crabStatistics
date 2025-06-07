##### contains the datasets used for analysis, visualization, and model development.

## Dataset List

| Filename             | Description                                     | Source                         |
|----------------------|-------------------------------------------------|-----------------------------------------|
| `olympics2024`       | Medal counts of countries in olympics           | Used for EDA, visualization     |



### sources
https://data.worldbank.org/

---

## for multivariate analysis
**(df = px.data.tips())** a pandas DataFrame containing tabular data.

tips dataset contains records of restaurant tips 
used for demonstrating plotting libraries like Plotly, Seaborn, or matplotlib.

Columns in tips dataset:
Column	Description	Data Type
total_bill	Total bill (including tip) in USD	float
tip	Tip amount in USD	float
sex	Gender of the person paying (Male/Female)	categorical
smoker	Whether the person is a smoker (Yes/No)	categorical
day	Day of the week (Thur, Fri, Sat, Sun)	categorical
time	Time of the day (Lunch or Dinner)	categorical
size	Number of people at the table	integer
