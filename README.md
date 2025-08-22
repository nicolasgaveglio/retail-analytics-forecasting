# 🛒  Retail Analytics & Sales Forecasting

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://python.org) [![XGBoost](https://img.shields.io/badge/XGBoost-Latest-green.svg)](https://xgboost.readthedocs.io) [![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Latest-orange.svg)](https://scikit-learn.org) [![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow.svg)](https://powerbi.microsoft.com)

> **Master's Thesis Project** - End-to-end ML solution for retail demand forecasting and product clustering. Digital transformation case study simulating real-world business impact for a retail company transitioning from analog to digital operations.

## 🎯 What This Project Delivers

- **Sales Forecasting**: XGBoost model for 4-week demand prediction
- **Product Clustering**: Customer segmentation using K-means and PCA  
- **Business Intelligence**: Interactive Power BI dashboards
- **MLOps Pipeline**: Production-ready forecasting system

## 🚀 Key Results

| Metric | Achievement |
|--------|------------|
| **Forecast Accuracy** | RMSE optimization with time-series validation |
| **Product Segments** | 5 distinct clusters with business interpretation |
| **Data Integration** | 3 complex datasets unified with custom logic |
| **Automation** | Weekly batch forecasting pipeline |

## 💡 Quick Demo

### 1. Explore the Analysis
```bash
# Main notebooks - ready to run
01_data_integration_eda.ipynb              # Data exploration & integration
01_eda_preprocessing.ipynb                 # Data preprocessing pipeline
02_product_clustering.ipynb               # Customer segmentation  
03_sales_forecasting.ipynb                # ML forecasting model
```

### 2. Core Features

**🔍 Smart Data Integration**
- Custom yearweek logic (Saturday-Friday cycles)
- Intelligent outlier detection using Z-score methodology
- Multi-source data fusion from 3+ retail datasets

**🤖 ML Models**
- **XGBoost Forecasting**: Non-linear time series prediction
- **K-means Clustering**: Silhouette-optimized product segmentation
- **Feature Engineering**: Seasonality, pricing, and event variables

**📊 Business Impact**
- Demand-driven inventory optimization
- Customer behavior insights
- Strategic decision support dashboards

## 🛠️ Tech Stack

**ML & Analytics**
- `Python` • `Pandas` • `NumPy` • `Scikit-Learn` • `XGBoost`
- `Matplotlib` • `Seaborn` • `PCA` • `Time Series Analysis`

**Infrastructure & Deployment**
- `Apache Airflow` • `Google Cloud Platform` • `Power BI`

## 📁 Project Structure

```
├── notebooks/
│   ├── 01_data_integration_eda.ipynb
│   ├── 02_product_clustering.ipynb
│   └── 03_sales_forecasting.ipynb
├── TFM_Academic_Memory.pdf
└── README.md
```

## 👥 Team & Academic Context

**Program**: Data Science & AI Master  
**Authors**: Nicolás Gaveglio, José Luengo, Marina Sallent

---

⭐ **Ready to explore?** Start with the notebooks to see the complete ML pipeline in action!

> **Note**: This is an academic simulation. Sample data structure and complete methodology are documented in `TFM_Academic_Memory.pdf`
