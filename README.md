# 🍽️ Identifying and Recommending the Best Restaurant

## 📌 Project Overview

This project is a **Data Analytics Capstone Project** focused on identifying and recommending the best restaurants using a real-world dataset. The analysis explores restaurant-related attributes such as cuisines, location, ratings, cost, and service availability to provide actionable insights into customer preferences and restaurant performance.

The project combines **data cleaning, exploratory data analysis (EDA), visualization, and feature engineering** to understand patterns in the restaurant industry and highlight factors that influence ratings and popularity.

---

## 📂 Dataset

The project uses two datasets:

1. **Restaurant Dataset** (`data.xlsx`)

   * Contains ~9,551 restaurant records across multiple countries.
   * Includes details such as restaurant name, country, city, address, cuisines, average cost, table booking availability, online delivery option, ratings, and votes.
2. **Country Code Dataset** (`Country-Code.xlsx`)

   * Provides country names mapped to numeric country codes.

---

## ⚙️ Tools & Libraries

* **Python**
* **Pandas** – Data manipulation
* **NumPy** – Numerical computations
* **Matplotlib & Seaborn** – Data visualization
* **Scikit-learn** – Outlier detection and preprocessing

---

## 🔑 Key Steps in Analysis

1. **Data Preprocessing**

   * Handled missing values in `Restaurant Name` and `Cuisines`.
   * Removed duplicates.
   * Treated outliers in `Votes` and `Average Cost for two`.

2. **Exploratory Data Analysis (EDA)**

   * Distribution of restaurants across countries and cities.
   * Ratio of restaurants allowing **table booking vs. no booking**.
   * Percentage of restaurants offering **online delivery**.
   * Relationship between customer votes and delivery options.
   * Analysis of cuisines across cities.

3. **Feature Engineering**

   * Split `Cuisines` column into multiple cuisine categories.
   * Mapped country codes to names for better readability.
   * Derived insights by grouping data on locality and cuisine types.

4. **Insights**

   * India dominates the dataset with the highest number of restaurants.
   * New Delhi has the maximum number of restaurants, while many smaller cities have only one.
   * Only ~14% of restaurants provide **table booking**, while ~25.7% offer **online delivery**.
   * Restaurants offering delivery tend to receive more customer votes.
   * North Indian cuisine is the most common across Indian cities.

---

## 📊 Visualizations

The project includes:

* Bar charts for restaurant distribution across countries and cities.
* Pie charts for booking and delivery service availability.
* Boxplots and histograms to analyze cost and vote distributions.
* Cuisine frequency analysis across cities.

---

## 🏆 Outcome

The project successfully identifies:

* **Top cuisines served** across cities.
* **Customer behavior trends** (votes, ratings, preferences).
* **Best-performing restaurants/localities** based on rating and popularity.

These insights can help:

* Customers find the best restaurants by cuisine and locality.
* Restaurant businesses improve services by understanding customer preferences.

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone <repo-link>
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:

   ```bash
   jupyter notebook "DA Capston project 1-Identifying and recommending best restaurant.ipynb"
   ```

---

## 📌 Future Improvements

* Build a **restaurant recommendation system** using collaborative filtering or content-based filtering.
* Incorporate **sentiment analysis** on restaurant reviews.
* Enhance geographical insights using interactive maps (Plotly/folium).

---

## 👨‍💻 Author

Capstone Project by **Sachin Khade**

