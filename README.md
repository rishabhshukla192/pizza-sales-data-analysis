<p align="center">
  <img src="images/pizza%20image.jpg" style="max-width: 100%; height: auto;" alt="Pizza Banner">
</p>


## Background and Overview
Understanding customer behavior and product performance is crucial for optimizing sales in the food industry. This project explores a comprehensive dataset from a pizza sales database, analyzing sales trends, peak business hours, and product popularity to generate actionable business recommendations.


## Data Structure Overview
The dataset includes the following key tables and attributes:

- **Orders**: Order ID, Date, Time  
- **Order Details**: Order ID, Pizza ID, Quantity  
- **Pizzas**: Pizza ID, Name, Size, Price  
- **Pizza Types**: Pizza Type ID, Category, Ingredients  

The data spans a continuous period with consistent timestamp granularity, allowing time-series and categorical analysis.

---

## Executive Summary
This report delivers a high-level view of sales performance across pizza categories, sizes, and time intervals. Our goal is to identify top-performing products, determine demand cycles, and uncover insights that support marketing strategies, inventory planning, and product development.

### Key Deliverables:
- Highest revenue-generating pizza types  
- Most ordered pizzas by volume  
- Peak order hours  
- Sales distribution by pizza size and category  

---

## Insights and Deep Dive

### 1. Hourly Order Distribution
- Peak order times were observed between **12 PM – 2 PM** and **6 PM – 8 PM**.

![Hourly Orders](images/hourly%20distribution.png)

---

### 2. Pizza Size Preference
- **Medium and Large** pizzas lead in popularity and sales.

![Pizza Sizes](images/count%20of%20different%20pizza%20sizes.png)

---

### 3. Top Ordered Pizzas by Quantity
- Highlights pizzas that are most frequently ordered by volume.

![Top Ordered Pizzas](images/top%2010%20pizzas%20ordered%20quantitatively.png)

---

### 4. Top Revenue-Generating Pizzas
- Focuses on the pizzas bringing in the most revenue.

![Top Revenue Pizzas](images/top%2015%20revenue%20generating%20pizzas.png)

---

### 5. Revenue by Pizza Category
- Breaks down overall sales by pizza category (e.g., Veggie, Classic, Chicken).

![Category Revenue](images/revenue%20generated%20by%20each%20category%20of%20pizza.png)

---

## Recommendations

Based on the analysis, the following business strategies are recommended:

- **Time-based Promotions**: Offer discounts during slow hours (e.g., 3–5 PM) to increase throughput.  
- **Inventory Prioritization**: Ensure top-performing pizzas like *The Classic Deluxe* and *The Hawaiian* are always in stock during peak hours.  
- **Bundling Strategy**: Introduce combo deals that include high-margin but underperforming items.  
- **Category Campaigns**: Promote underperforming categories like Veggie or Mediterranean through themed weeks or offers.  
- **Menu Optimization**: Consider updating or removing low-demand pizzas to streamline operations.  

---

## How to Run This Project

1. Clone this repository
2. Open the `.csv` files in Excel or import them into Python or Jupyter for analysis
3. Visualizations are available in the `/images/` folder

---

**Developed by:** *Rishabh Shukla*  
**Tools Used:** Excel, MYSQL, Python (optional)  
**Dataset:** See `pizza_sales.zip` for the raw data

> All images and charts used in this README are stored in the `/images/` folder of this repository. Please ensure they are properly named as referenced above.
