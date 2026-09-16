# 🍽️ Turning Yelp Data into Restaurant Intelligence

### End-to-End Python, SQL & Time Series Analytics in Jupyter Notebook

> 💻 **Entire project developed in Python Jupyter Notebook**, with SQL queries executed directly against a SQLite database for data extraction, transformation and analysis.


## 📌 Project Overview

This project analyses Yelp restaurant data to understand how **user engagement** is associated with restaurant success.

Using **SQL and Python**, the analysis examines reviews, tips, check-ins, ratings, sentiment-related engagement, elite users and engagement trends over time.

## 🎯 Business Objective

The objective is to identify factors associated with restaurant performance and understand how customer engagement can provide insights into restaurant success.

## 🔍 Key Business Questions

- How does user engagement vary with restaurant ratings?
- Are reviews, tips and check-ins correlated?
- How does engagement differ between high-rated and low-rated restaurants?
- How do engagement patterns change over time?
- How do useful, funny and cool review interactions relate to restaurant success?
- What role do Yelp Elite users play in overall engagement?
- What are the busiest hours for restaurant-related activity?

## 🗄️ Dataset

The project uses a subset of the **Yelp Open Dataset**, covering businesses across **8 metropolitan areas in the USA and Canada**.

The original data is provided as JSON files and includes:

- Business
- Review
- User
- Tip
- Check-in

The JSON data is transformed into a SQLite database to enable SQL-based analysis. :contentReference[oaicite:2]{index=2}

## 🛠️ Tools & Technologies

- SQL
- SQLite
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Folium
- SQLAlchemy
- Jupyter Notebook

## 🔄 Data Pipeline

![Yelp Data Pipeline](Yelp%20Data%20Pipeline.png)

The pipeline reads Yelp JSON data, converts the records into Pandas DataFrames and loads them into a SQLite database for analysis.

## 📊 Analysis Performed

### User Engagement & Ratings

Analysed the relationship between:

- Review count
- Check-in count
- Tip count
- Average star rating

Restaurants rated 4.0 stars showed the highest average engagement in the analysis.

### Engagement Correlation

Examined correlations between reviews, tips and check-ins to understand whether different forms of user engagement move together.

### High-Rated vs Low-Rated Restaurants

Compared businesses with ratings of **3.5+** against those below 3.5 across:

- Reviews
- Check-ins
- Tips

### Geographic Analysis

Calculated a restaurant success score combining average rating and review count to compare restaurant performance across cities.

### Time-Series Analysis

Examined engagement patterns over time and investigated trends and seasonality in reviews and tips.

### Review Engagement & Sentiment

Analysed `useful`, `funny` and `cool` interactions associated with reviews and their relationship with restaurant success metrics.

### Yelp Elite Users

Compared Elite and non-Elite users in terms of user population and total review contribution.

### Peak Engagement Hours

Analysed review, tip and check-in activity by hour to identify periods of highest restaurant-related engagement.

## 📈 Key Findings

- The dataset contains **150,346 businesses**, of which **35,004 open restaurant businesses** were identified for the main analysis.
- Restaurants rated **4.0 stars** showed the highest average engagement.
- High-rated restaurants averaged approximately **63 reviews, 81 check-ins and 8 tips**, compared with **37 reviews, 65 check-ins and 5.5 tips** for low-rated restaurants.
- Yelp Elite users represented only about **4.6% of users** in the analysis but contributed approximately **44% of all reviews**.
- Restaurant-related engagement was concentrated during the **4 PM–1 AM** period.
- Philadelphia had the highest calculated success score among the cities analysed.

## 💡 Business Insight

The analysis indicates that restaurant performance should not be evaluated using ratings alone.

Combining **ratings, reviews, tips, check-ins, user behaviour and time-based engagement** provides a broader view of restaurant visibility and customer interaction.

The findings can support decisions around customer engagement, staffing, operating hours and reputation management.

## 📂 Repository Contents

| File | Description |
|------|-------------|
| `Yelp_Project_14.09.2026.ipynb` | Complete SQL and Python analysis |
| `Yelp Data Pipeline.png` | Data ingestion and database pipeline |
| `YELP Report.pdf` | Detailed project report |
| `Images/` | Selected analysis visualisations |
| `README.md` | Project documentation |

## 👤 Author

**Bharat Reddy**

Data Analytics | Business Analytics | SQL | Python | Power BI
