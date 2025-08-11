# ✈️ Airline Data Analysis with Python & Pandas

## 📌 Project Overview
This project analyzes airline flight data using **Python, Pandas, Matplotlib, and Seaborn** to uncover pricing trends, route performance, and factors affecting flight costs.  
It includes **EDA (Exploratory Data Analysis)**, statistical summaries, and data visualizations to derive actionable business insights.

---

## 📂 Dataset Information
**Columns in the dataset:**
- `index` – Row index
- `airline` – Airline name
- `flight` – Flight code/number
- `source_city` – Departure city
- `departure_time` – Time of departure (Morning, Afternoon, Evening, Night)
- `stops` – Number of stops (Non-stop, 1 stop, 2+ stops)
- `arrival_time` – Arrival time
- `destination_city` – Arrival city
- `class` – Travel class (Economy / Business)
- `duration (in Hours)` – Flight duration in hours
- `days_left` – Days left before departure
- `price` – Ticket price (in ₹)

---

## 🔍 Key Analysis Questions
1. How do prices vary across airlines and classes?
2. Does the number of stops impact ticket prices?
3. How does booking time (`days_left`) influence pricing?
4. Which routes are the most expensive and cheapest?
5. Is there a relationship between flight duration and price?

---

## 📊 Visualizations
The analysis includes:
- **Histogram** – Price distribution  
- **Boxplots** – Price vs Class, Price vs Airline  
- **Scatterplots** – Days Left vs Price, Duration vs Price  
- **Pairplot** – Relationships between price, duration, and days left  
- **Heatmap** – Correlation between numeric variables  

---

## 🧠 Key Insights (Example Trends)
- Business class flights are significantly more expensive than Economy.
- Prices tend to increase sharply as the departure date approaches.
- Non-stop flights cost more despite shorter durations.
- Certain airlines consistently have higher average ticket prices.
- Price distribution is right-skewed with high outliers for premium routes.

---

## 🛠 Tools & Libraries
- **Python** (Data Processing & Analysis)
- **Pandas** – Data cleaning & transformation
- **Matplotlib** – Static visualizations
- **Seaborn** – Statistical visualizations
- **Jupyter Notebook** – Analysis environment


## 📁 Files
| Filename              | Description                         |
|-----------------------|-------------------------------------|
| `Airlines_data.csv` |  dataset |
| `Task5.ipynb`         | Jupyter Notebook with all cleaning steps |
| `README.md`           | Project summary and documentation   |
