# Dynamic-Pricing-Engine-for-E-Commerce
Role: Data Scientist | Tools: Python, Pandas, XGBoost, Scikit-learn, Matplotlib
Domain: Retail Pricing Optimization, Predictive Modeling

# Project Overview:
Built a machine learning-driven dynamic pricing engine to optimize product prices in a simulated e-commerce environment, aiming to maximize revenue by predicting demand responses to pricing strategies.

# Key Components:
Synthetic Dataset Generation: Simulated multi-product sales data with time-based trends, competition, marketing signals, and customer behavior attributes.

Exploratory Data Analysis (EDA): Uncovered pricing vs. demand relationships, seasonal demand patterns, and key drivers influencing revenue.

# Feature Engineering:

Constructed features like price_diff, discount, inventory_ratio, rolling_avg_units, and calendar features (dayofweek, holiday).

One-hot encoded product categories for improved model learning.

# Demand Prediction Model:

Trained an XGBoost regression model to predict units sold based on price, competition, marketing, and time-based inputs.

Achieved R² = 0.51, MAE = 4.34, and RMSE = 5.57 on the test set.

# Dynamic Pricing Simulation:

Designed a pricing simulation loop to test various price points and forecast revenue outcomes.

Selected the optimal price per product by maximizing predicted price × units_sold.

Visualized revenue vs. price curve to illustrate optimization behavior.

Outcome:
Developed a revenue-maximizing pricing recommendation system.

Demonstrated ability to integrate predictive modeling with business decision-making.

Packaged results into a reusable pricing engine template that can scale across products and time windows.
