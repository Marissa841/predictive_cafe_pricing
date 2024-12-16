### Overview
This project analyzes a cafe's pricing dataset to answer the business case question: What prices should a cafe's items be sold for to optimize the sales? Using the OSEMN data science process, the analysis identified key trends and features that influence sales.

### Business Case
A cafe aims to optimize pricing to maximize sales and profitability. By understanding the impact of features such as menu item type, customer behavior, weather, and promotions on demand, the cafe can set data-driven prices for its products. This analysis provides actionable insights for pricing strategies and improving overall revenue.

### Data
The dataset, "cafe_pricing.csv," includes 1,000 records of sales data with 13 features such as date, day of the week, time of day, menu item, price, units sold, competitor price, customer type, weather, holiday, special promotions, and profit margins.

### Methods
The project followed the OSEMN data science process:
- **Obtain**: Acquired the dataset from internal cafe records.
- **Scrub**: Cleaned and transformed the data, including combining duplicate categories (e.g., "croissant" and "Croissant") and adding a season column.
- **Explore**: Conducted exploratory data analysis (EDA) to understand trends in demand based on features such as day of the week, weather, and customer type.
- **Model**: Built a Random Forest Regression model to predict optimal pricing for each menu item.
- **Interpret**: Evaluated model performance and interpreted results to provide actionable recommendations.

### Results
The analysis provided the following insights:
- **Average Monthly Demand**: No clear trends in demand based on months were observed.
- **Day of the Week**: Small fluctuations in demand, with some days showing higher average sales.
- **Model Performance**: The Random Forest Regression model achieved strong predictive accuracy with meaningful feature importance.

### Conclusions + Future Work
Key recommendations for the cafe include:
1. **Adjust Pricing by Demand**: Optimize pricing for high-demand products like Coffee and Tea to maximize profitability.
2. **Promotions for Weather-Dependent Items**: Offer targeted promotions based on weather conditions to increase sales of items like Smoothies in summer or warm beverages in winter.
3. **Engage Loyal Customers**: Develop loyalty programs and pricing strategies to retain loyal customers.

For future work:
- Investigate pricing strategies for new product launches.
- Expand analysis to include regional competitors’ data.
- Develop predictive models for sales forecasting under varying economic conditions.

### For More Information
See the full analysis in the Jupyter Notebook or review the presentation for additional details. For further inquiries, contact Marissa Bush at Marissabush.02@gmail.com.

### Repository Structure
```
├── README.md
├── cafe_pricing.csv
└── cafe_pricing.ipynb
```

