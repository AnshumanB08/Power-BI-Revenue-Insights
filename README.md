# 🏨 AtliQ Grands Revenue Insights  

Power BI dashboard providing revenue insights for AtliQ Grands (Hospitality Domain). The project analyzes hotel performance, occupancy, booking platforms, and pricing strategies to deliver actionable recommendations for revenue growth.  

---

## 📌 Problem Statement  
AtliQ Grands owns multiple five-star hotels across India and has been in the hospitality industry for the past 20 years. However, due to strong competition and ineffective management decisions, AtliQ Grands has been losing its **market share and revenue** in the luxury/business hotel category.  

To regain market share, the Managing Director of AtliQ Grands decided to incorporate **Business & Data Intelligence** into their strategy. Since they lacked an in-house analytics team, they outsourced the work to a third-party analytics provider to gain insights from their historical data.  

This project provides a **Power BI dashboard** that delivers revenue insights to support strategic decision-making.  

---

## 📂 Dataset & Resources  
The project uses five datasets provided in CSV format, with metadata included.   
1. **dim_date** – Calendar table with date, month, week, and day type.
2. **dim_hotels** – Hotel details such as ID, name, category, and city.
3. **dim_rooms** – Room details with categories (Standard, Elite, Premium, Presidential).  
4. **fact_aggregated_bookings** – Aggregated daily booking data with capacity and successful bookings.  
5. **fact_bookings** – Detailed booking-level data including revenue, ratings, booking platform, and status. 

👉 For detailed metadata, refer to: [meta_data_hospitality.txt](https://github.com/AnshumanB08/Power-BI-Revenue-Insights/blob/main/meta_data_hospitality.txt)  

---

## 📊 Dashboard Preview  

![Revenue Dashboard](https://github.com/AnshumanB08/Power-BI-Revenue-Insights/blob/main/Dashboard%20screenshot.png)  

🔗 **Live Dashboard Web View:**  
[Click here to explore](https://app.powerbi.com/view?r=eyJrIjoiMzZkYTFiMjQtYTRjYS00MTY2LWI0YmMtYmNjZjJkZGQ5MGYwIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)  

---

## 🧩 Data Model 

![Data Model](https://github.com/AnshumanB08/Power-BI-Revenue-Insights/blob/main/Data%20Model.png)  

---

## 📈 Key Insights & Recommendations  

1. **Occupancy vs Pricing Strategy**  
   - **Occupancy %** fluctuates week-on-week, while **ADR** (Average Daily Rate) remains flat.  
   - This indicates a **static pricing strategy**.  
   - **Recommendation:** Implement **dynamic pricing**, especially for weekends & holiday seasons, to maximize revenue.  

2. **Low Occupancy & Ratings**  
   - Hotels with **low occupancy** also show **low ratings** and **high cancellation %**.  
   - **Recommendation:** Improve customer experience by addressing review feedback and improving service quality.  

3. **Booking Platform Strategy**  
   - AtliQ’s **own booking platforms** (online & offline) have ADRs that are not significantly different from third-party platforms.  
   - Since they **don’t pay commission** on their own platforms, they can implement **promotional strategies** like **discount coupons, loyalty points, or cashback offers** to attract more direct bookings.  
   - This will help increase **realized revenue** while reducing dependency on external platforms.  

4. **Overall Conclusion**  
   - The **major issue** is ineffective **pricing strategy**.  
   - By adopting **dynamic & differential pricing** and **improving service quality**, AtliQ can regain **market share** and boost **revenue growth**.  

---

## 🛠 Tools & Technologies Used  
- **Power BI** – Data visualization & dashboard creation
- **Excel / CSV** – Data preparation 
- **DAX** – Measures & calculations  

---

## 🚀 How to Use  
1. Clone this repository.
2. Open the .pbix file in Power BI Desktop.
3. Connect datasets if needed (CSV files).
4. Explore dashboard and insights.

---

## 📣 Acknowledgement

This project is part of the Codebasics SQL Resume Project Challenge.
Check out for more details [here](https://codebasics.io/challenges/codebasics-resume-project-challenge/4).

---

## 🤝 Contributions 
Contributions, issues, and feature requests are welcome!

If you find this project insightful, ⭐ star this repository to support my work.

**Thank you for checking out my project!**
