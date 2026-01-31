# Food Delivery Analytics

## 📌 Project Overview
This project is a hackathon submission focused on analyzing food delivery data by integrating multiple real-world data sources and extracting meaningful business insights. The analysis covers order trends, user behavior, city and cuisine performance, membership impact, and revenue distribution using Python and data visualization techniques.

---

## 📂 Datasets Used
The project uses three datasets provided in different formats:

- **orders.csv** – Transactional order data  
- **users.json** – User master data (user details and membership type)  
- **restaurants.sql** – Restaurant master data (cuisine and ratings)

---

## 🔗 Data Integration
- The datasets were merged using **LEFT JOINs** to retain all order records.
- Join keys used:
  - `orders.user_id` → `users.user_id`
  - `orders.restaurant_id` → `restaurants.restaurant_id`

The final merged dataset was exported as:
- **`final_food_delivery_dataset.csv`**

This dataset acts as the **single source of truth** for all analyses.

---

## 📊 Analysis Performed

### 1️⃣ Order Trends Over Time
- Monthly and quarterly order trends
- Revenue seasonality analysis

### 2️⃣ User Behavior Patterns
- Orders per user distribution
- Identification of frequent and high-value users
- Average order value per user

### 3️⃣ City-wise & Cuisine-wise Performance
- City-wise revenue comparison
- Cuisine popularity analysis
- City vs Cuisine heatmap for performance intensity

### 4️⃣ Membership Impact (Gold vs Regular)
- Comparison of total orders, total revenue, and average order value
- Contribution analysis using bar and donut charts

### 5️⃣ Revenue Distribution & Seasonality
- Revenue distribution statistics
- Detection of outliers and high-value orders
- Seasonal revenue patterns

---

## 📈 Visualizations
The following visualization techniques were used:
- Line charts
- Bar charts
- Histograms and box plots
- Pie / donut charts
- Heatmaps
- Interactive maps for city-wise analysis

All visualizations were created using **Matplotlib**, **Seaborn**, and **Folium**.

---

## 🛠 Tools & Technologies
- **Programming Language:** Python  
- **Data Handling:** Pandas  
- **Database:** SQLite  
- **Visualization:** Matplotlib, Seaborn, Folium  
- **Environment:** Jupyter Notebook  

---

## ▶️ How to Use
1. Clone the repository
2. Open the Jupyter Notebook:
