# 📊 Ola Ride Analytics Dashboard
A Power BI dashboard and SQL analysis project using a 20,000+ Ola ride records dataset to extract actionable business insights such as revenue trends, cancellation behavior, customer value, and driver performance.

## 🛠️ Tools & Technologies
- **SQL** – Data cleaning and querying
- **Power BI** – Data visualization and dashboard creation
- **DAX** – Custom calculated measures and logic

## 📊 Dashboard Highlights
### Bookings Overview  
!(images/ride-volume-over-time.png)

### Vehicle Type   
!(images/revenue-by-payment-method.png)

### Revenue
!(images/cancellation-reasons.png)

### Cancellation  
!(images/ratings-comparison.png)

The dashboard is divided into five main sections:

### 1. 🚦 Overall Bookings Overview
- **Total Records Analyzed**: 20,000+
- **Success Rate**: ✅ 62%
- **Cancellation Rate**: ❌ 28.1%
  - Cancelled by Drivers: 17.91%
  - Cancelled by Customers: ~10%
  - Driver Not Found: ~9.9%
  
🔍 **Insight**: Driver-side issues contribute significantly to cancellation rate, affecting customer experience.

---

### 2. 🚗 Vehicle Type Analysis
- Total & Successful Booking Value per Vehicle
- Average and Total Distance Travelled
- Ratings Analysis by Vehicle Type

💡 **Insight**:
- **Mini** received the **highest customer ratings**
- **Prime Plus** received the **highest driver ratings**

📌 **Actionable Idea**: Expand Mini fleet for customer satisfaction and retain Prime Plus for high-value driver experience.

---

### 3. 💸 Revenue & Payments
- Revenue Breakdown by **Payment Method**
- Top 5 Customers by Total Spend
- Ride Distance Distribution by Date

📊 **Finding**:
- Most transactions were **cash-based**
- Ride distances drop significantly on **Sundays**

📌 **Actionable Idea**: Promote digital payments and target Sunday discounts to boost off-peak rides.

---

### 4. ❌ Cancellations Deep Dive
- Driver-side cancellations outnumbered customer ones.
- **Top reasons**: Personal issues and care-related emergencies.

📌 **Actionable Idea**: Introduce backup driver systems and better driver availability policies.

---

### 5. ⭐ Ratings Analysis
- Compared **driver vs. customer ratings** across vehicle types
- Plotted distribution to find satisfaction gaps

📊 **Key Insight**:
- **Mini** has the happiest customers
- **Prime Plus** is the most liked by drivers

---

## 🔍 Additional Opportunities (Future Work)

- Geo-mapping booking & cancellation clusters
- Churn prediction based on booking frequency
- Forecasting high-demand time slots
- Customer segmentation for targeted campaigns


- ## 🔗 Links
- 🖥️ **Live Power BI Dashboard**: [Click to View](YOUR_PUBLIC_LINK_HERE)
- 💾 **SQL Queries File**: [queries.sql](queries.sql)
- 📊 **Download Power BI File**: [OlaDashboard.pbix](OlaDashboard.pbix)
- 🖼️ **Project Screenshots**: See below

## 📷 Dashboard Previews

### 💡 Revenue by Payment Method  
![Revenue by Payment](images/revenue-by-payment-method.png)

---

### 📉 Cancellation Rate by Vehicle Type  
![Cancellation Rate](images/cancellation-rate-chart.png)

---

### 👑 Top Customers and Ratings  
![Top Customers](images/top-customers-table.png)

---

## 🚀 How to Run
1. Clone this repository
2. Open `OlaDashboard.pbix` using Power BI Desktop
3. Explore visuals, slicers, and DAX measures

---

## 🧠 About the Project
This project simulates the kind of business questions a **data analyst** might face in a ride-sharing company. From query formulation to dashboard storytelling, it showcases a hands-on approach to **turning raw data into actionable insights**.

---

## 📬 Contact
For any queries or suggestions, feel free to reach out:  
📧 anushadhiman101@gmail.com  
🌐 [LinkedIn](https://linkedin.com/in/anusha3768)
