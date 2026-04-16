# 1. Netflix Analytics: Data Visualization Dashboard

A dynamic and interactive **Power BI dashboard** designed to explore Netflix content trends—focusing on content distribution, genre popularity, country-wise analysis, and audience ratings.

---

## 2. Short Description / Purpose

The Netflix Data Visualization Dashboard is built to analyze and present insights from Netflix content data. It helps users understand patterns in movies and TV shows, identify top-performing genres and countries, and explore audience preferences through ratings and trends.

---

## 3. Tech Stack

The dashboard was built using the following tools and technologies:<br>

• **Power BI Desktop** – Main platform used to create interactive dashboards and visualizations.<br>
• **Power Query** – Used for data cleaning, transformation, and shaping.<br>
• **DAX (Data Analysis Expressions)** – Used to create calculated measures and KPIs.<br>
• **Data Modeling** – Relationships built between dataset fields for filtering and aggregation.<br>
• **Python (Pandas, Matplotlib)** – Used for preprocessing and exploratory data analysis.<br>
• **File Formats** – `.pbix` for dashboard, `.csv` for dataset, `.ipynb` for analysis.<br>

---

## 4. Data Source

The dataset contains Netflix content information including movies and TV shows.

**Dataset includes:**

* Title
* Type (Movie / TV Show)
* Country
* Genre
* Rating
* Duration
* Date Added

The dataset was cleaned and transformed using Python and Power Query before visualization.

---

## 5. Features / Highlights

### • Business Problem

With thousands of titles available on Netflix, it becomes difficult to quickly analyze:

* Which countries produce the most content
* What genres are most popular
* How content has grown over time
* What type of audience Netflix targets

---

### • Goal of the Dashboard

To build an interactive dashboard that:

* Provides clear insights into Netflix content trends
* Helps users analyze content distribution and growth
* Supports data-driven decisions for content strategy
* Enhances understanding of audience preferences

---

### • Walkthrough of Key Visuals

#### 🔹 KPI Cards (Top Section)

* Total Content: 8803
* Total Countries: 124
* Total Movies: 6127
* Total TV Shows: 2676
* Total Genres: 43

---

#### 🔹 Content Added Per Year (Line Chart)

Shows how Netflix content has grown over time, highlighting rapid expansion after 2016.

---

#### 🔹 Top 10 Content Producing Countries (Bar Chart)

Displays countries like **United States, India, United Kingdom** contributing the most content.

---

#### 🔹 Content Distribution (Country-wise) (Stacked Bar Chart)

Compares **Movies vs TV Shows** percentage across countries.

---

#### 🔹 Top 10 Genres (Donut Chart)

Highlights most popular genres such as:

* International Movies
* Dramas
* Comedies

---

#### 🔹 Top 10 Latest Content (Table)

Shows recently added titles with type and duration.

---

#### 🔹 Top 5 Content Ratings (Pie Chart)

Displays audience categories such as:

* TV-MA
* TV-14
* PG-13

---

#### 🔹 Filters (Slicers Panel)

* Year filter
* Country filter

Allows dynamic interaction with all visuals.

---

### • Business Impact & Insights

* **Content Growth Insight:** Netflix saw massive expansion post-2016
* **Regional Analysis:** USA dominates content production
* **Genre Trends:** International content is highly popular
* **Audience Targeting:** Most content is for mature audiences (TV-MA, TV-14)
* **Strategic Use:** Helps businesses understand streaming trends and audience behavior

---

## 6. Screenshots / Demo

https://github.com/Yashp077/Netflix_data_visualization_dashboard/blob/main/netflix_dashboard.png

---

## 7. Conclusion

The Netflix Data Visualization Dashboard successfully transforms raw data into meaningful insights through interactive and visually appealing reports. By analyzing content distribution, genre trends, country contributions, and audience ratings, the dashboard provides a clear understanding of Netflix’s content strategy and growth patterns.

This project demonstrates the power of data visualization in simplifying complex datasets and enabling data-driven decision-making. It also highlights the importance of combining data cleaning, modeling, and visualization techniques to build effective analytical solutions.

Overall, the dashboard serves as a practical example of how business intelligence tools like Power BI can be used to uncover trends, improve insights, and support strategic planning in the entertainment industry.


