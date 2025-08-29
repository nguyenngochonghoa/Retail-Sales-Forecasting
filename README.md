# Retail Sales Forecasting

## 1. Introduction  
In today’s competitive retail landscape, the ability to **accurately forecast sales** is critical for:  
- Effective inventory management  
- Smarter marketing planning  
- Optimizing resources and budgets  

This project uses **Retail Data Analytics** from **45 retail stores** across multiple regions and departments.  
The dataset includes:  
- Features dataset  
- Sales dataset
- Stores dataset 

👉 **Goal**: Forecast future sales performance and provide actionable business strategies.  

---

## 2. Business Problems Addressed  
- Forecasting store- and department-level sales revenue.  
- Understanding the impact of markdowns (discounts) during holidays.  
- Evaluating the effect of seasonality (peak vs. off-peak months).  
- Assessing the influence of macroeconomic factors (Fuel Price, CPI, Unemployment).  
- Comparing performance across regions and store types to tailor strategies.  

---

## 3. Approach  
- **Business Problem Definition**: Defined retail sales forecasting challenges, including markdowns, holidays, seasonality, and macroeconomic effects.  
- **Data Preparation**: Collected, cleaned, standardized, and integrated retail datasets.  
- **Exploratory Analysis**: Identified sales trends, seasonality, KPIs, and regional performance through visualization.  
- **Modeling & Evaluation**: Compared ARIMA, Auto ARIMA, and SARIMA; selected manual ARIMA based on lowest RMSE.  
- **Business Insights**: Derived actionable strategies for pricing, promotions, seasonality planning, and regional optimization.  

---

## 4. Model Results  
- **Selected ARIMA (manual tuning)** → Best performance with the lowest RMSE ✅  
- **Auto ARIMA** → Higher RMSE, less effective than manual tuning.  
- **SARIMA** → Performed similarly to Auto ARIMA but not as strong as manual ARIMA.  

👉 **Conclusion**: **Manually tuned ARIMA is the recommended model for sales forecasting.**  

---

## 5. Business Recommendations  
🔹 **Markdown Optimization**  
- Increase markdowns during major holidays and promote them strongly.  
- Combine markdowns with other promotional campaigns for maximum impact.  

🔹 **Seasonality Strategy**  
- Launch strong promotions during off-peak months (June, August, December).  
- Secure inventory for peak months (April, May, October).  

🔹 **Regional & Store-Type Strategy**  
- Invest more in high-performing stores.  
- Support weaker stores with tailored inventory adjustments.  

🔹 **Targeted Marketing**  
- Localized marketing for specific regions.  
- Use both traditional and online channels.  
- Provide store-specific offers to boost revenue.  

🔹 **Economic & Holiday Adjustments**  
- When fuel prices or CPI decrease → stock more and adjust pricing to stimulate demand.  
- Prepare for peak shopping events (Christmas, Super Bowl, Thanksgiving) with bundled promotions.  

---

## 6. Key Takeaways  
- **Manual ARIMA** proved to be the most effective forecasting model (lowest RMSE).  
- Insights on **markdowns, seasonality, economic factors, and regional differences** provide actionable strategies to:  
  - Improve supply chain efficiency  
  - Execute smarter, data-driven marketing campaigns  
  - Maximize overall revenue  

📌 *This project was developed as our **final coursework project** in Business Intelligence. While ARIMA performed best, we recognize opportunities to further enhance the analysis by:*  
- Exploring advanced forecasting models (e.g., **Prophet, LSTM**).  
- Integrating **real-time data streams** for more dynamic predictions.  
- Expanding business recommendations with **profitability and customer segmentation analysis**.  

🚀 *This reflects our continuous learning mindset and interest in bridging data science with business decision-making.*  
