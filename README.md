# Car Market Analysis


## 📌 Project Overview
This project involves **scraping car data** from the [CarDekho](https://www.cardekho.com/) website using **Python, BeautifulSoup, Requests, and Pandas**. The extracted data is then **analyzed and visualized in Power BI** to derive actionable insights about pricing, customer preferences, affordability, and brand performance.

## 🚀 Features & Insights
### 🔹 **Data Scraping**
- Extracted car details including **price, brand, model, EMI options, ratings, and reviews**.
- Used **BeautifulSoup** for parsing HTML and **Requests** for fetching data.
- Processed and structured the data using **Pandas**.

### 🔹 **Data Visualization in Power BI**
1. **Market Positioning: Brand vs. Price**
   - **Scatter Plot:** X-axis: On-road price, Y-axis: Ratings, Bubble size: Number of reviews.
   - Insight: Identifies which brands dominate premium, mid-range, and budget segments.

2. **Customer Preferences: Rating Trends by Price**
   - **Line Chart:** Ratings vs. Price range with trend lines.
   - Insight: Determines whether higher-priced cars consistently receive better ratings.

3. **Affordability Analysis: EMI Options**
   - **Bubble Chart:** X-axis: EMI, Y-axis: On-road price, Bubble size: Rating.
   - Insight: Identifies models offering the best balance between price and affordability.

4. **Brand Popularity Based on Reviews**
   - **Treemap/Bubble Chart:** Number of reviews per brand.
   - Insight: Measures customer engagement and interest in different brands.

5. **Top 5 Affordable Cars**
   - **Bar Chart:** Comparing cars based on EMI, price, and ratings.
   - Insight: Highlights the best-value models for budget-conscious buyers.

## 🛠️ Tech Stack
- **Python** (BeautifulSoup, Requests, Pandas)
- **Power BI** (Data modeling, visualizations, DAX calculations)

## 📂 Project Structure
```
├── data/                # Raw and processed datasets
├── scripts/             # Python scripts for web scraping
│   ├── scrape.py        # Main scraping script
│   ├── clean_data.py    # Data preprocessing and transformation
├── visuals/             # Power BI reports and screenshots
├── README.md            # Project documentation
└── car_data.pbix        # Power BI dashboard file
```

## 📈 Sample Visuals
![image](https://github.com/user-attachments/assets/46530d11-b977-4b60-97b7-dd6e5d44df50)


## 📜 License
This project is licensed under the **MIT License** – feel free to use and modify it.

## 🤝 Contributing
Contributions are welcome! If you’d like to improve the analysis or add new features:
1. Fork this repository
2. Create a new branch (`feature-new-visual`)
3. Commit your changes and push
4. Open a pull request

## ✨ Connect with Me
For any questions or collaborations, feel free to reach out!
📧 **Your Email**  | 🔗 [LinkedIn](https://linkedin.com/in/your-profile)  | 🐦 [Twitter](https://twitter.com/your-handle)

