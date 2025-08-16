# 🍽️ Restaurant Rating Prediction Web App  

A machine learning web application that analyzes restaurant data and predicts ratings with **interactive visualizations** and **real-time predictions**.  

---

## 🌟 Features  

### 📊 Interactive Analysis Dashboard  
- Distribution of ratings, costs, and votes  
- Top restaurant locations and categories  
- Online ordering & table booking availability  
- Cost vs Rating analysis  
- Correlation heatmap of features  

### 🔮 Prediction Engine  
- **Machine Learning Model** (Random Forest / XGBoost)  
- **Neural Network Model** with confidence scoring  
- Real-time predictions based on restaurant details  
- Confidence breakdown for each prediction  

---
 
---

## 🚀 Quick Start  

### Run Locally  
```bash
git clone https://github.com/Dai-ELsayed/Resturants-Analysis-Prediction-app.git
cd Resturants-Analysis-Prediction-app
pip install -r requirements.txt
streamlit run app.py

```


## 📊 Dataset Overview

The dataset includes the following information:

Location Data: Geographic distribution and areas

Service Features: Online ordering, table booking availability

Restaurant Categories: Types, cuisines, service modes

Financial Data: Cost for two people, price analysis

Performance Metrics: Ratings, votes

Service Types: Delivery, Dine-out, Cafes, etc.

##  Models
Architecture

Traditional ML: Random Forest / XGBoost

Neural Network: Multi-layer deep learning with dropout regularization

Feature Engineering: OneHot encoding, ordinal encoding, scaling

Prediction Categories

Poor: 0 – 2.5

Good: 2.5 – 4.0

Excellent: 4.0 – 5.0

##

 ### 📁 Project Structure
📂 zomato_resturants_Analysis & Prediction/
│── 📄 app.py
│── 📄 requirements.txt
│── 📄 README.md
│
├── 📂 notebooks/
│ └── eda_and_models.ipynb
│
├── 📂 models/
│ └── best_ml_model.pkl 
│ └── my_model.keras
│ └── scaler.pkl 
│ └── ord_enc.pkl 
│ └── encoder.pkl 
│
├── 📂 data/
│ └── zomato_sample.csv


