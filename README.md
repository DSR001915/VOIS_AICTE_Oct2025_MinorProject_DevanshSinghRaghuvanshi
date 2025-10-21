# Airbnb NYC Analysis

## 📊 Project Overview

This project analyzes the **Airbnb listings dataset for New York City** to uncover insights about pricing, availability, room types, reviews, and geographic trends. Using data cleaning, exploratory data analysis (EDA), and visualization techniques, this study highlights key factors influencing listing popularity, pricing strategies, and guest behavior.

The insights are useful for:

* **Hosts**: to optimize pricing and availability
* **Guests**: to understand trends and choose accommodations wisely
* **Airbnb / Analysts**: to identify opportunities for market growth

---

## 🗂 Dataset

* **Source:** Airbnb NYC Dataset (2019)
* **Number of Rows:** 102,599
* **Number of Columns:** 26
* **Key Features:**

  * `name`, `host_name`, `neighbourhood_group`, `neighbourhood`
  * `room_type`, `price`, `minimum_nights`, `number_of_reviews`
  * `reviews_per_month`, `availability_365`, `latitude`, `longitude`

---

## 🧹 Data Cleaning & Preprocessing

* Standardized column names: lowercase and underscores (`reviews per month → reviews_per_month`)
* Converted numeric columns (`price`, `minimum_nights`, `reviews_per_month`) to proper data types
* Converted `last_review` to datetime
* Removed duplicates and outliers (e.g., `price > 1000`)
* Handled missing values: filled NaNs for `reviews_per_month` and other key features

---

## 📈 Exploratory Data Analysis (EDA)

* **Listings Distribution** by `neighbourhood_group` and `room_type`
* **Price Analysis**: boxplots by `neighbourhood_group`, identification of expensive listings
* **Availability Analysis**: distribution of days available per year
* **Review Analysis**: distribution of number of reviews, reviews per month correlation
* **Correlation Analysis**: heatmap of numeric features
* **Geographical Analysis**: interactive map of listings by neighborhood and price

---

## 📊 Key Insights

1. **Manhattan and Brooklyn** dominate Airbnb listings; other boroughs have growth potential.
2. **Entire homes/apartments** are most expensive but highly booked; private rooms offer a budget-friendly alternative.
3. Listings with **higher reviews** generally have better visibility and occupancy.
4. **Price outliers** suggest hosts can optimize pricing to remain competitive.
5. Many listings are available **year-round**, allowing for strategic seasonal pricing.
6. Geospatial analysis highlights **centralized listings**, revealing opportunities in underserved neighborhoods.

---

## 🛠 Technologies Used

* **Programming Language:** Python 3.x
* **Libraries:** pandas, numpy, matplotlib, seaborn, plotly
* **Tools:** Jupyter Notebook / Google Colab

---

## 📌 Project Structure

```
Airbnb-NYC-Analysis/
│
├── AB_NYC_2019.csv          # Dataset
├── Airbnb_EDA.ipynb         # Jupyter notebook with full analysis
├── README.md                # Project documentation
└── requirements.txt         # Python dependencies
```

---

## 🔗 Future Enhancements

* **Predictive Pricing Model**: Use ML to predict optimal prices for listings
* **Booking Trends Analysis**: Monthly/seasonal booking trends
* **Sentiment Analysis**: Analyze guest reviews for satisfaction insights
* **Dashboard**: Interactive dashboard using Plotly Dash or Tableau

---

## 📂 How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/Airbnb-NYC-Analysis.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open `Airbnb_EDA.ipynb` in Jupyter Notebook or Google Colab.
4. Run all cells to reproduce the analysis and visualizations.

---

## 📌 Author

**Devansh Singh Raghuvanshi**

* GitHub: [github.com/DSR001915](https://github.com/DSR001915)
* LinkedIn: [linkedin.com/in/DEVANSH SINGH RAGHUVANSHI](https://www.linkedin.com/in/devansh-singh-raghuvanshi-30b578231/)

---

