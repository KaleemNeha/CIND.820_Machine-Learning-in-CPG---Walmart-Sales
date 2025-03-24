# Walmart Retail Analytics Project

## 📌 Project Overview
A comprehensive retail analytics solution combining demand forecasting, customer segmentation, and price optimization for Walmart's CPG division.

## 🔄 Project Workflow
1. **Data Preprocessing & EDA**  
2. **Time Series Analysis**  
   *Key finding:* SARIMAX model achieved **243,844 MAE** in weekly sales forecasting
3. **Customer Segmentation**  
4. **Price Optimization**  
   *Identified 12-18% margin improvement potential*
   
**These Files are Saved in notebooks"

graph TD
    A[Raw Walmart Sales Data] --> B[Data Preprocessing]
    B --> C{Analysis Phase}
    C --> D[Demand Forecasting]
    C --> E[Customer Segmentation]
    C --> F[Pricing Optimization]
    
    D --> D1[ARIMA/Prophet Models]
    D --> D2[Economic Factor Integration]
    D --> D3[Inventory Policy Recommendations]
    
    E --> E1[RFM Analysis]
    E --> E2[K-Means Clustering]
    E --> E3[Targeted Marketing Strategies]
    
    F --> F1[Price Elasticity Modeling]
    F --> F2[Promotion Impact Analysis]
    F --> F3[Revenue Optimization]
    
    D & E & F --> G[Ethical Validation]
    G --> H[Actionable Business Insights]
