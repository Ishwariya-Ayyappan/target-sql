# 🛒 Target Brazil E-commerce: BigQuery SQL Analytics

A comprehensive SQL-driven business intelligence project analyzing Target’s Brazilian e-commerce operations (2016–2018) using Google BigQuery.  
Gain actionable insights into customer behavior, sales seasonality, logistics, and economic impact - all powered by advanced SQL queries.

---


## 🚀 How to Use

1. **Prepare your BigQuery environment:**  
   - Import the dataset using the provided schema in `bigquery_setup/`.
2. **Run SQL scripts:**  
   - Execute queries in the `sql_queries/` folder for each analysis section.
3. **Review insights:**  
   - Use the inferences and recommendations below to guide business decisions.

---

## 📊 Core Insights

### 1. **Exploratory Analysis**
- **Coverage:** Orders from **8,011 cities** and **27 states** - nationwide reach.
- **Timeframe:** Data spans from **2016-09-04** to **2018-10-17**.
- **Customer Table:** Rich in demographic and geographic data for targeted marketing.

### 2. **Growth & Seasonality**
- **Order Growth:**  
  - Orders jumped from **329 (2016)** to **45,101 (2017)**, then to **54,011 (2018)** (Jan–Aug).
  - **136% YoY growth** in order value from 2017 to 2018 (Jan–Aug).
- **Seasonality:**  
  - **Peak months:** May–August (late spring/summer).
  - **Lull:** September–October, with minor recovery in November–December.
- **Order Timing:**  
  - **Afternoon (38k orders)** and **night (28k orders)** are peak shopping times.
  - **Dawn** sees the fewest orders (5k).

### 3. **Geographical & Customer Distribution**
- **State Coverage:** Customers in all 27 states; strong presence in populous regions.
- **Market Penetration:** High diversity in customer base, enabling region-specific strategies.

### 4. **Economic Impact**
- **Order Value:**  
  - Significant increase in total payment value, reflecting both more orders and higher-value transactions.
  - **State-level breakdowns** reveal where revenue is concentrated.
- **Freight Analysis:**  
  - Wide variation in freight costs by state due to geography and infrastructure.
  - Some states face high logistics costs, others benefit from proximity to hubs.

### 5. **Logistics & Delivery**
- **Delivery Delays:**  
  - Notable gap between estimated and actual delivery times - a key area for improvement.
- **Freight & Delivery Times:**  
  - Top 5 states with highest/lowest average freight and delivery times identified.
  - Infrastructure and distance are major factors.

---

## 💡 Under-the-Surface Insights

- **Latent Market Potential:**  
  - States with lower order volumes but high average order value could be ripe for targeted campaigns.
- **Customer Behavior Patterns:**  
  - Afternoon/evening peaks suggest marketing and support staff should be aligned with these periods.
- **Logistics Bottlenecks:**  
  - High delivery delays correlate with states having poor infrastructure or longer distances from distribution centers.
- **Freight Cost Optimization:**  
  - States with consistently low freight costs can serve as models for process improvements elsewhere.
- **Seasonal Inventory Planning:**  
  - Stockouts or overstocking risks can be mitigated by aligning inventory with the clear seasonality in demand.
- **Revenue Concentration Risk:**  
  - Heavy dependence on a few states for revenue could be a vulnerability - diversification is key.

---

## 📝 Strategic Recommendations

1. **Optimize Delivery Performance**
   - Invest in logistics partnerships and last-mile solutions in high-delay states.
   - Use historical delay data to improve delivery time estimates and customer communications.

2. **Targeted Marketing & Support**
   - Increase marketing spend and customer support availability during afternoon and night peaks.
   - Run region-specific campaigns in underperforming but high-value states.

3. **Seasonal Inventory Management**
   - Pre-stock inventory for May–August peaks; reduce inventory in off-peak months to cut costs.

4. **Freight Cost Reduction**
   - Negotiate better rates with carriers in high-cost states.
   - Explore micro-fulfillment centers in remote regions to lower average freight costs.

5. **Customer Segmentation**
   - Use geographic and behavioral data to create tailored offers for different customer segments.

6. **Expand in Untapped Regions**
   - Analyze states with low order count but high average value for expansion opportunities.

7. **Monitor Revenue Concentration**
   - Develop contingency plans to mitigate risks from over-reliance on a few high-revenue states.

8. **Continuous Data Monitoring**
   - Set up dashboards for real-time tracking of order trends, delays, and regional performance.

---

## 📚 Data Sources

- **Tables:** `orders`, `customers`, `order_items`, `payments`, `geolocation`, `sellers`
- **Platform:** Google BigQuery (SQL)
- **Period:** 2016-09-04 to 2018-10-17

---

## 🤝 Contributing

Pull requests, feedback, and suggestions are welcome!  
For major changes, please open an issue first.

---

> **Data-driven strategies are the backbone of sustainable e-commerce growth.**



