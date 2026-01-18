# 📊 Customer Analytics: RFM Segmentation & Clustering

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-2.0+-green.svg)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.3+-orange.svg)
![Status](https://img.shields.io/badge/Status-Complete-success.svg)

**A comprehensive customer analytics project using RFM analysis and K-Means clustering to identify behavioral patterns and develop targeted retention strategies for a specialty coffee subscription business.**

---

## 🎯 Project Overview

This project analyzes **10,000 customers** from BrewCraft Coffee Subscription (2021-2023) to:
- Segment customers using RFM (Recency, Frequency, Monetary) methodology
- Identify behavioral clusters using K-Means machine learning
- Quantify revenue at risk from customer churn
- Develop targeted marketing strategies for each segment
- Create actionable CRM automation recommendations

---

## 📈 Key Results

| Metric | Value |
|--------|-------|
| **Total Customers Analyzed** | 10,000 |
| **Total Revenue** | $5.8M |
| **Customer Segments Identified** | 8 distinct clusters |
| **Revenue at Risk** | $700K+ |
| **Projected Annual Recovery** | $280K (12% recovery rate) |
| **Expected ROI** | 211% |

---

## 🔍 Analysis Approach

### **Phase 1: Feature Engineering & RFM Analysis**
- Created customer behavior features from 133K+ transactions
- Calculated RFM scores (Recency, Frequency, Monetary)
- Identified customer segments: Champions, Loyal, At-Risk, Lost, etc.
- Analyzed purchase patterns and product preferences

### **Phase 2: K-Means Clustering**
- Applied unsupervised machine learning for behavioral segmentation
- Used Elbow Method and Silhouette Score for optimal cluster selection
- Profiled clusters based on spending patterns, engagement, and churn risk
- Compared ML clusters with traditional RFM segments

### **Phase 3: Business Impact & Recommendations**
- Quantified revenue opportunities for each segment
- Developed segment-specific marketing strategies
- Created Klaviyo automation flow recommendations
- Calculated ROI projections for retention campaigns

---

## 📂 Project Structure
```
customer-analytics-rfm-clustering/
├── notebooks/
│   ├── 01_Feature_Engineering.ipynb          # Data preparation & RFM analysis
│   ├── 02_Clustering_Analysis.ipynb          # K-Means clustering & profiling
│   └── 03_Business_Impact_Recommendations.ipynb  # Marketing strategies & ROI
├── data/
│   ├── brewcraft_transactions.csv            # Raw transaction data
│   ├── brewcraft_customers.csv               # Customer master data
│   ├── customer_features_engineered.csv      # Engineered features
│   ├── customer_features_with_clusters.csv   # Final dataset with clusters
│   ├── executive_summary.csv                 # Key metrics summary
│   └── segment_strategies.csv                # Marketing recommendations
├── README.md
└── requirements.txt
```

---

## 🎨 Key Visualizations

- **Customer Segmentation Dashboard**: Distribution of customers across RFM segments
- **Churn Analysis**: Churn rates by segment with revenue impact
- **Cluster Profiling**: Behavioral patterns and characteristics
- **Revenue Analysis**: Contribution by segment and at-risk revenue
- **Executive Dashboard**: Comprehensive business metrics overview

---

## 💼 Business Recommendations

### **High-Priority Segments:**

1. **Champions** (35% of revenue)
   - Launch VIP loyalty program
   - Early access to new products
   - Personalized recommendations

2. **At-Risk Customers** ($300K revenue at risk)
   - Aggressive re-engagement campaigns
   - Personalized win-back offers
   - Account manager outreach

3. **New/Promising** (High growth potential)
   - Onboarding email series
   - 2nd purchase incentives
   - Subscription conversion flow

### **CRM Implementation:**
- 5 Klaviyo automation flows designed
- Estimated 12% revenue recovery from at-risk customers
- 211% ROI on $90K annual marketing investment

---

## 🛠️ Technologies Used

**Languages & Libraries:**
- Python 3.8+
- Pandas, NumPy (data manipulation)
- Scikit-learn (K-Means clustering)
- Matplotlib, Seaborn (visualization)
- Jupyter Notebook

**Analysis Techniques:**
- RFM Segmentation
- K-Means Clustering
- Customer Lifetime Value Analysis
- Churn Prediction
- ROI Modeling

---

### **Run Notebooks in Order:**
1. `01_Feature_Engineering.ipynb`
2. `02_Clustering_Analysis.ipynb`
3. `03_Business_Impact_Recommendations.ipynb`

---

## 📊 Skills Demonstrated

### **Technical:**
- Data cleaning and feature engineering
- Machine learning (unsupervised clustering)
- Statistical analysis
- Data visualization
- Python programming

### **Business:**
- Customer segmentation strategies
- Churn analysis and retention planning
- Marketing campaign design
- ROI calculation and business case development
- CRM automation strategy

---

## 📧 Contact

**Rishi Dhandi**  
Marketing/Growth Data Analyst  
[LinkedIn]([https://www.linkedin.com/](https://www.linkedin.com/in/rishi-dhandi/)

---

## 📄 License

This project is for portfolio demonstration purposes.

---

## 🙏 Acknowledgments

- Dataset: Synthetic data created for BrewCraft Coffee Subscription case study
- Inspired by real-world e-commerce subscription analytics challenges
- Built as part of professional portfolio development for marketing analytics roles
