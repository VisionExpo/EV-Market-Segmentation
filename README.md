# 🚀 EV Market & Booking Segmentation – India 2025

## 📌 Project Overview
This project presents a comprehensive analysis of the Indian Electric Vehicle (EV) market and online vehicle booking trends.  
The goal is to identify optimal geographic and customer segments for launching EV-based products and services (such as rentals, shared rides, and B2B delivery), supported by sales trends, infrastructure availability, and booking demand data.

---

## 🧠 Problem Statement
- **EV Startup Goal**: Identify the most feasible vehicle/customer/B2B segment for EV product development and rollout.
- **Booking Platform Goal**: Discover untapped booking market segments beyond Ola/Uber by analyzing demand and infrastructure readiness.

---

## 📊 Key Features
- 📈 EV sales trend analysis (2001–2024)  
- ⚡ EV manufacturer market share & top brands  
- 🗺️ State-wise charging infrastructure mapping  
- 🚗 Registration stats by vehicle class  
- 🧠 KMeans-based market segmentation by demand & infra  
- 📎 Strategic insights and visuals stored in `/output/`  

---

## 📁 Project Structure

📦 EV-Market-Segmentation/
├── data/
│   └── raw/                       # Original datasets
├── notebooks/
│   └── segmentation_analysis.ipynb
├── output/                       # All plots and visualizations
├── reports/
│   └── EV_Market_Booking_Report.pdf
├── README.md                     # This file
└── requirements.txt              # Python libraries

---

## 📂 Datasets Used

| Dataset                               | Purpose                                  | Source                     |
|---------------------------------------|------------------------------------------|----------------------------|
| `ev_cat_01-24.csv`                    | Monthly EV sales by class                | Kaggle (India EV Market)   |
| `ev_sales_by_makers_and_cat_15-24.csv`| Sales by brand & vehicle category        | Kaggle                     |
| `Operational PC.csv`                  | Public charging stations by state        | Kaggle                     |
| `Vehicle Class.csv`                   | Total registered vehicles by class       | Kaggle                     |
| `EV Maker by Place.csv`               | Location of EV manufacturers             | Kaggle                     |
| `train.csv` (Ola)                     | Ride demand simulation                   | Kaggle (Competition)       |
| Google Trends                         | Interest by geography & topic            | Google Trends              |

---

## 🛠️ Tools & Libraries
- Python 3, Pandas, NumPy  
- Scikit-learn (KMeans)  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---

## 📈 Visual Insights  
Saved in `/output/` folder:
- `ev_makers_by_state.png`
- `opc_by_state.png`
- `top10_ev_makers.png`
- `ev_sales_by_category.png`
- `category_trends.png`
- `total_reg_by_class.png`
- `kmeans_cluster_plot.png`

---

## 🔍 Key Findings
- 🔌 Charging infra density varies sharply by state  
- 🏍️ 2W segment dominates all other EV classes  
- 🏙️ Tier-1 cities like Delhi, Bangalore, and Pune show strong EV & booking readiness  
- 📦 Tier-2 cities ideal for delivery/logistics EV fleet deployment  

---

## 💼 Business Model Suggestions
- EV rental or ride-hailing (2W/3W) for city commuters  
- B2B EV leasing for logistics/delivery platforms  
- Rent-to-own subscription model in underserved regions  

---

## 👨‍💻 Contributors
- Vishal Gorule

---

## 📄 Final Report & Repository
- 📘 [Full Report PDF](./reports/EV Market Segmentation.pdf)  
- 📁 [GitHub Repo](https://github.com/VisionExpo/EV-Market-Segmentation)

---

## 📜 License
MIT License – Open source for academic and project use with attribution.

> 🔍 For implementation, see: `/notebooks/segmentation_analysis.ipynb`  
> 📊 For figures and charts, see: `/output/`
