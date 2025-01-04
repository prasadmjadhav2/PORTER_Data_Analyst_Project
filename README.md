!["PORTER Delivery hai?
#HoJayega!"](https://github.com/prasadmjadhav2/PORTER_Data_Analyst_Project/blob/main/PORTER_logo.png)

# PORTER Data Analyst and Machine Learning Project

This repository contains a comprehensive analysis of PORTER's delivery operations, customer behavior, and predictive modeling efforts to optimize revenue, efficiency, and customer satisfaction.

## Table of Contents
- [Insights](#insights)
  - [Revenue Segmentation by Customer Behavior](#revenue-segmentation-by-customer-behavior)
  - [Impact of Vehicle Type on Delivery Times](#impact-of-vehicle-type-on-delivery-times)
  - [Customer Retention Analysis](#customer-retention-analysis)
  - [Cancellation Trends and Reasons](#cancellation-trends-and-reasons)
  - [Delivery Bottleneck Analysis](#delivery-bottleneck-analysis)
  - [Driver Efficiency Metrics](#driver-efficiency-metrics)
  - [Revenue Leak Analysis](#revenue-leak-analysis)
  - [Dynamic Pricing Opportunities](#dynamic-pricing-opportunities)
- [Key Findings from Power BI](#key-findings-from-power-bi)
- [Actionable Recommendations](#actionable-recommendations)
- [Growth Strategies](#growth-strategies)
- [Projects Overview](#projects-overview)
  - [Data Analysis Using Python](#data-analysis-using-python)
  - [Machine Learning for Delivery Prediction](#machine-learning-for-delivery-prediction)
- [Dataset](#dataset)
- [How to Run](#how-to-run)
- [Contributors](#contributors)

!["POWER BI Dashboard Sample"](https://github.com/prasadmjadhav2/PORTER_Data_Analyst_Project/blob/main/pbi_dash_sample.png)
!["EXCEL Dashboard Sample"](https://github.com/prasadmjadhav2/PORTER_Data_Analyst_Project/blob/main/excel_dash_sample.png)

## Insights

### Revenue Segmentation by Customer Behavior
- **Key Insights:**
  - Corporate clients contribute significantly to revenue with the highest revenue per booking.
  - Individual customers dominate booking volumes.
- **Actions:**
  - Introduce tiered rewards for frequent users.
  - Expand corporate partnerships.
  - Offer premium services for high-value segments.

### Impact of Vehicle Type on Delivery Times
- **Key Insights:**
  - Two-wheelers deliver the fastest but yield lower revenue.
  - Larger vehicles cater to high-revenue clients but have longer delivery times.
- **Actions:**
  - Optimize vehicle assignment using AI.
  - Adjust pricing strategies based on vehicle type.

### Customer Retention Analysis
- **Key Insights:**
  - High retention correlates with consistent spending.
  - Most churn occurs after 1-2 bookings.
- **Actions:**
  - Offer discounts for new users.
  - Implement CRM-driven follow-ups.

### Cancellation Trends and Reasons
- **Key Insights:**
  - High cancellations during peak traffic and bad weather.
  - Delivery delays are the top reason for cancellations.
- **Actions:**
  - Provide real-time updates.
  - Allow rescheduling without penalties.

### Delivery Bottleneck Analysis
- **Key Insights:**
  - Traffic and weather significantly delay deliveries.
  - Rush hour bookings see a spike in failed deliveries.
- **Actions:**
  - Implement surge pricing during peak hours.
  - Collaborate with local authorities for better traffic management.

### Driver Efficiency Metrics
- **Key Insights:**
  - High-rated drivers are faster and improve satisfaction.
  - Unrated drivers often delay or fail deliveries.
- **Actions:**
  - Train low-rated drivers.
  - Incentivize high-rated drivers.

### Revenue Leak Analysis
- **Key Insights:**
  - Failed bookings lead to major revenue loss.
  - Low-value trips are more likely to fail.
- **Actions:**
  - Introduce a minimum revenue threshold.
  - Use predictive models for resource allocation.

### Dynamic Pricing Opportunities
- **Key Insights:**
  - Higher revenue during specific time slots and locations.
- **Actions:**
  - Promote high-revenue delivery windows.
  - Target low-revenue periods with discounts.

---

## Key Findings from Power BI
- **Success Rate:** 61.74%.
- **Top Revenue Cities:** Ahmedabad, Hyderabad, Mumbai.
- **Total Booking Value:** $141M.
- **High Utilization:** Three-wheelers and mini trucks.

---

## Actionable Recommendations
1. **Optimize Vehicle Allocation:** Deploy Tata Ace EV in high-demand cities.
2. **Reduce Cancellations:** Enhance communication tools.
3. **City-Specific Strategies:** Promote services in low-performing cities.
4. **Improve Customer Experience:** Incentivize personal users to lower cancellations.

---

## Growth Strategies
- Expand into Tier-2 cities.
- Invest in AI for predictive maintenance and optimization.
- Scale eco-friendly vehicle deployment.

---

## Projects Overview

### Data Analysis Using Python
- **Features:**
  - Data preprocessing: cleaning, handling missing values, and feature engineering.
  - Exploratory data analysis (EDA) using `matplotlib` and `seaborn`.
  - Visualization of revenue drivers, customer segments, and operational metrics.
- **Key Findings:**
  - Revenue distribution skews towards lower values.
  - Online payments yield higher driver ratings.
  - Identified three customer segments through clustering.

---

### Machine Learning for Delivery Prediction
- **Features:**
  - Random Forest Regressor to predict `Total KM`.
  - MultiOutput Regressor for simultaneous prediction of `Total KM` and revenue.
  - Hyperparameter tuning using Grid Search for Random Forest optimization.
- **Evaluation:**
  - Metrics such as Mean Squared Error (MSE) and R² Score.
  - Visualizations: scatter plots of actual vs. predicted values.
- **Key Findings:**
  - Revenue, Booking Value, and Fare Charge are critical predictors.

---

## Dataset
- **Source:** `PORTER_delivery_data.csv`
- **Features:** 40 columns including delivery metrics, financial details, and customer ratings.
- **Size:** 100,000 entries.

---
## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/porter-data-analysis.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the analysis or modeling scripts:
   - For analysis: `python data_analysis.py`
   - For modeling: `python ml_modeling.py`

---

## Contributors
- **Prasad Jadhav** (ML Engineer)
  - [LinkedIn](https://linkedin.com/in/prasadmjadhav2)
  - [GitHub](https://github.com/prasadmjadhav2)
  - Email: prasadmjadhav6161@gmail.com
