# electricity-demand-forecasting-ml
End-to-end ML pipeline for ERCOT electricity demand
# ⚡ Electricity Demand Forecasting & Clustering Dashboard

## 🚀 Project Overview
- Cleans & aggregates 3 years of ERCOT load + multi-city weather data  
- Identifies daily-load archetypes via PCA, t-SNE & clustering  
- Benchmarks Linear Regression, Random Forest (best RMSE ≈ 3 149 MW, R²≈0.80) & Gradient Boosting  
- Deploys an interactive Gradio app for real-time forecasting & cluster visualization  

## 🔍 Key Features
- **Data Prep & Aggregation**  
- **Dimensionality Reduction**: PCA & t-SNE  
- **Clustering**:  
  - K-Means (k=5)  
  - DBSCAN (eps=0.3, min_samples=5)  
  - Hierarchical (Ward linkage)  
- **Forecasting Models**:  
  - Linear Regression  
  - Random Forest  
  - Gradient Boosting  
- **Web Interface**: Gradio Blocks API  


## ⚙️ Setup & Installation
```bash
git clone https://github.com/YOUR_USERNAME/electricity-demand-forecasting.git
cd electricity-demand-forecasting
pip install pandas numpy scikit-learn matplotlib gradio
