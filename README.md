# 🚴‍♂️ Adventure Works Bike shop Data Analytics Project

The dashboard was built using the following tools and technologies:<br>
•	📊 Power BI Desktop – Main data visualization platform used for report creation.<br>
•	📂 Power Query – Data transformation and cleaning layer for reshaping and preparing the data.<br>
•	🧠 DAX (Data Analysis Expressions) – Used for calculated measures, dynamic visuals, and conditional logic.<br>
•	📁 File Format – .pbix for development and .png for dashboard previews.

> **The Problem It Solves:** It is often tough for retail managers to keep an eye on the big picture while also catching micro-level issues or understanding their core demographic. I designed this multi-page interactive dashboard to bridge that gap, providing a unified tool that flows seamlessly from high-level executive summaries down to granular product details and customer profiles.

---

## 1. What's this all about?
I built this comprehensive Adventure Works Power BI project to demonstrate how stakeholders can get a 360-degree view of a company's financial health, customer base, and product performance. Instead of digging through disconnected spreadsheets, managers can use this report to track macro-level sales trends, analyze customer demographics, and use **drill-through functionality** to investigate specific product performance and run "what-if" pricing scenarios.

## 2. The Data Behind the Scenes
**Source:** Adventure Works Sample multi-table dataset from the Maven Analytics platform. 

To clarify, this is a pre-existing sample dataset that I found online to showcase my analytical and visualization skills, not data that I generated myself.

---

## 3. Walkthrough of the Dashboards

### 📊 Page 1: Executive Dashboard
The landing page provides an immediate snapshot of overall business health and highlights top-performing (and underperforming) areas.

| Metric | Value | Quick Insight |
| :--- | :--- | :--- |
| **Revenue** | **24.9M** | Sustained growth, accelerating rapidly in Q4. |
| **Orders** | **25.2K** | High volume driven heavily by Accessories (**17K**). |
| **Profit** | **10.5M** | Strong overall margins across core categories. |
| **Return Rate** | **2.2%** | Generally healthy, but specific items (e.g., Sport-100 Helmets at **>3.3%**) need review. |

* **Interactive Drill-Through:** Users can right-click on any item in the "Top 10 Product" matrix and drill through directly to the Product Details Dashboard to investigate its specific performance metrics.
* **Recent Momentum:** Bottom cards track month-over-month performance, revealing that despite a slight dip in monthly orders (**-0.88%**), revenue actually increased (**+3.31%**).

### 🔍 Page 2: Product Details Dashboard (Drill-Through Target)
Accessed via the Executive Dashboard, this page allows for deep-dive analysis on specific inventory items.
* **Target Tracking:** Gauge charts instantly show how the selected product is performing against monthly targets for Orders, Revenue, and Profit.
* **Dynamic Metric Selection:** A slicer allows users to toggle the bottom trend lines between Orders, Revenue, Profit, Returns, and Return %.
* **"What-If" Price Adjustments:** Features an interactive slider parameter that lets users model how hypothetical price adjustments (e.g., a 20% increase) would impact Total vs. Adjusted Profit over time.

### 👥 Page 3: Customer Details Dashboard
This page shifts the focus to the people buying the products, helping marketing and sales understand their audience.
* **The Customer Base:** Highlights **17.4K** unique customers and an average revenue of **₹1,431** per customer.
* **Demographic Segmentation:** Clean donut charts break down the customer base by Income Level and Occupation, showing strong traction among "Professional" and "Skilled Manual" roles.
* **Top Customer Spotlight:** A dynamic section highlights the absolute best customers (e.g., Mr. Maurice Shan with 6 orders and **12.4K** in revenue), alongside a Top 100 Customer matrix for VIP targeting.

---

## 4. Business Impact & Insights
If deployed in a real retail environment, this tool would drive immediate action:
* **Targeted Marketing:** By knowing the bulk of high-value orders come from the "Professional" occupation bracket, marketing teams can tailor their ad spend and messaging accordingly.
* **Strategic Pricing:** Sales leadership can use the "What-If" parameter on the Product page to test the elasticity of top-selling items like "Tires and Tubes" before officially rolling out price hikes.
* **Fixing Quality Issues:** Operations can spot the high return rates of Shorts and specific Helmets on the Executive page, drill through to see exactly *when* the return spikes happened on the Product page, and investigate manufacturing defects.

---

## 5. Screenshots
**Executive Overview**
![Executive Dashboard](https://github.com/jitenlm10/Adventure-Works-Bike-Shop-Dashboard/blob/121d2ed8780a800726cbac52d8b66189b8e6cce6/Adventure%20Works%20Bike%20Shop%20Executive%20Dashboard.png)

**Product Details (Drill-Through)**
![Product Details Dashboard](https://github.com/jitenlm10/Adventure-Works-Bike-Shop-Dashboard/blob/121d2ed8780a800726cbac52d8b66189b8e6cce6/Adventure%20Works%20Bike%20Shop%20Product%20Details%20Dashboard.png)

**Customer Details**
![Customer Details Dashboard](https://github.com/jitenlm10/Adventure-Works-Bike-Shop-Dashboard/blob/121d2ed8780a800726cbac52d8b66189b8e6cce6/Adventure%20Works%20Bike%20Shop%20Customer%20Details%20Dashboard.png)

