# Smart Hospitality Insights: Power BI Solution for Hotel Booking Demand

## Table of Contents
1. [Overview](#overview)
2. [Tech Stack Used](#tech-stack-used)
3. [Executive Summary](#executive-summary)
4. [Problem Statement](#problem-statement)
5. [Solution / Implementation](#solution--implementation)
6. [Benefits](#benefits)
7. [Challenges](#challenges)
8. [Conclusion & Recommendations](#conclusion--recommendations)
9. [Demo](#demo)

## Overview
This project applies **Business Intelligence (BI)** techniques to analyze hotel booking data and address three key challenges in the hospitality industry — **high cancellation rates**, **revenue optimization**, and **effective customer targeting**.  
Using the **Hotel Booking Demand dataset** from Kaggle (Mostipak, n.d.), which contains over 119,000 booking records from city and resort hotels, this project delivers actionable insights through **three interactive Power BI dashboards**.

The dashboards empower hotel managers to move from reactive management toward **data-driven strategic decisions**, improving occupancy, increasing profitability, and building long-term guest loyalty.

---

## Tech Stack Used

| Technology | Description |
|-------------|-------------|
| ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black) | Interactive dashboard development and visualization |
| ![Microsoft Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white) | Data validation and initial analysis |
| ![Power Query](https://img.shields.io/badge/Power%20Query-217346?style=for-the-badge&logo=microsoftpowerpoint&logoColor=white) | Data transformation and model building |
| ![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white) | Version control and documentation management |

---

## Executive Summary
This BI-driven solution tackles three persistent challenges in the hospitality sector: **high cancellation rates**, **revenue optimization**, and **customer segmentation**.  
Using the Hotel Booking Demand dataset from Kaggle, over **119,000 booking records** were analyzed through three **Power BI dashboards** — Cancellations, Revenue, and Customer Targeting.  

**Key Findings:**
- **Cancellations:** Nearly **37% of bookings** were cancelled, primarily from transient guests and “no deposit” reservations. Repeat guests showed much lower cancellation rates.  
- **Revenue:** Online travel agents contributed **over half of total revenue**, while profitability varied across room types and seasons.  
- **Customer Behavior:** Guest segmentation revealed clear patterns by demographics and region, enabling more focused marketing and loyalty strategies.  

These dashboards create a unified decision-support system that enhances forecasting accuracy, improves marketing strategies, and strengthens financial resilience in the competitive hospitality landscape.

---

## Problem Statement
Hotels face persistent operational challenges due to fluctuating demand, high cancellations, and unpredictable booking patterns. This project highlights three specific issues:
1. **High Cancellation Rates** – Leading to lost revenue and inefficient occupancy management.  
2. **Revenue Optimization** – Difficulty balancing dynamic pricing with occupancy and profitability.  
3. **Customer Targeting** – Need for segmentation to prioritize high-value guests and improve retention.

**Guiding Questions:**
- Why are bookings being cancelled, and what factors drive this behavior?  
- Which customer segments contribute most to revenue and stability?  
- How can hotels optimize room utilization and pricing strategies?  

---

## Solution / Implementation

### Data Acquisition & Integration
- Source: **Hotel Booking Demand Dataset** from Kaggle (Mostipak, n.d.)  
- Data covers **City Hotel** and **Resort Hotel** bookings between 2015–2017.  
- Data fields include booking status, room type, stay duration, guest demographics, and deposit type.

### Data Cleaning & Preparation
- Null values handled; duplicates removed.  
- Derived new metrics: **Total Guests**, **Total Stay Nights**, and **Cancellation Rates**.  
- Modeled using one **Fact Table** and multiple **Dimension Tables** (snowflake schema).  

### Dashboards Developed
1. **Customer Segmentation Dashboard** – Analyzes demographics, repeat guests, and seasonal patterns.  
2. **Cancellations Dashboard** – Identifies cancellation drivers by booking type, lead time, and deposit policy.  
3. **Revenue Dashboard** – Monitors revenue by room type, booking channel, and geography.

Each dashboard provides managers with actionable insights to forecast demand, reduce risk, and improve profitability.

---

## Benefits

- **Customer Insights:** Analysis across 177 countries and 234,000 guests revealed low repeat bookings, suggesting opportunities for loyalty programs.  
- **Cancellation Reduction:** 37% cancellation rate driven by “no deposit” policies; insights guide stricter or flexible deposit strategies.  
- **Revenue Growth:** $25.9M total revenue identified, with online travel agents contributing over 50%.  
- **Room Profitability:** Month-by-month and room-level analysis enables smarter pricing.  
- **Unified Decision Support:** Integrates operations, finance, and marketing into a single analytical framework.

---

## Challenges

1. **Data Integration:** Hotel data from multiple systems (PMS, OTA, CRM) can be inconsistent.  
2. **Technical Complexity:** Requires advanced modeling and DAX for accurate forecasting.  
3. **User Adoption:** Transitioning from intuition to analytics-driven decisions needs training.  
4. **Market Volatility:** Unpredictable travel trends and external shocks can affect accuracy.

---

## Conclusion & Recommendations

This project demonstrates the transformative role of **Business Intelligence (BI)** in solving major hospitality challenges. The **three Power BI dashboards** — Cancellations, Revenue, and Customer Segmentation — provide a data-driven foundation for better forecasting, pricing, and customer engagement.

**Recommendations:**
- Prioritize rollout of the **Cancellations Dashboard** to minimize revenue leakage.  
- Expand analysis by integrating **competitor pricing**, **local events**, and **guest feedback** data.  
- Implement **machine learning models** for demand forecasting and promotion optimization.  
- Encourage organization-wide adoption through BI training and data literacy programs.

By adopting this BI framework, hotels can transition from reactive management to proactive strategy — improving occupancy, maximizing revenue, and fostering sustainable competitive advantage.

---

## Demo

- Customer
  ![Customer](https://github.com/user-attachments/assets/3faf0c73-9072-46a4-bd3b-f049f5d67b4c)

- Booking
  ![booking](https://github.com/user-attachments/assets/a0d6b0a5-6b4e-4f94-90ee-f7f678c523ae)

- Cancellation
  ![cancellation2](https://github.com/user-attachments/assets/309281da-9ba4-483e-bc89-0cec0ea6502c)

- Revenue
  ![Revenue](https://github.com/user-attachments/assets/078b7058-e208-430a-a4b8-16e9578c482f)

  
