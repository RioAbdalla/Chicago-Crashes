# Chicago Traffic Crash Analysis (2019–2024)

## 📌 Project Overview
This project analyzes **Chicago traffic crash data (2019–2024)** to uncover patterns, high-risk areas, and contributing factors. Using exploratory data analysis (EDA), machine learning models, and interactive dashboards, the project provides actionable insights to improve urban safety, guide city planning, and support public awareness.

---

## 📊 Methodology
1. **Data Exploration**  
   - Analyzed crash types, contributing causes, speed limits, weather conditions, and device conditions.  
   - Identified high-risk streets and neighborhoods in Chicago.  

2. **Temporal Analysis**  
   - Crash distribution by **hour, day, and month**.  
   - Peak times: weekday evenings, Friday nights, and summer months.  

3. **High-Risk Areas**  
   - Downtown Chicago showed the highest crash density.  
   - Streets with most crashes: **Western Ave, Pulaski Rd, Cicero Ave, Ashland Ave, Halsted St**.  

4. **Weather & Road Conditions**  
   - Majority of crashes occurred in **clear/dry conditions**, highlighting human factors.  
   - Fatalities higher in clear weather compared to adverse conditions.  

5. **Machine Learning Models**  
   - Target: Predicting **fatal crashes** (`Injuries_Fatal`).  
   - Features: Weather condition, road defects, roadway surface, trafficway type, device condition, posted speed limit.  
   - Models: **Logistic Regression, Random Forest** to estimate fatality likelihood.  

---

## 📈 Key Insights
- **Common causes**: failure to yield, following too closely, improper overtaking.  
- **Crash types**: parked vehicles and rear-end collisions dominate.  
- **Temporal trends**: crashes peak on Fridays, late nights, and during summer.  
- **Weather**: Clear weather had the highest fatalities despite lower risk perception.  
- **Prediction models**: Random Forest outperformed logistic regression in identifying fatal crash risk.  

---

## 🛠️ Tech Stack
- **Python** (EDA & ML): `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`  
- **Visualization**: Tableau/Power BI dashboards  
- **Notebook**: Jupyter  

---

## 📂 Repository Structure
```
├── Chicago_Crash_EDA_areas_high_risk.ipynb   # Jupyter Notebook with analysis
├── Group 16_ Bilal, Agha, Malik, Abdalla, Tan.pdf   # Final report
├── Chicago Crashes Dashboard.pdf             # Dashboard export
└── README.md                                 # Project documentation
```

---

## 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/chicago-crash-analysis.git
   cd chicago-crash-analysis
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Chicago_Crash_EDA_areas_high_risk.ipynb
   ```

---

## 🤝 Contributors
- Bilal  
- Agha  
- Malik  
- Damario Abdalla  
- Tan  

---

## 📜 License
Add your chosen license here (MIT recommended if open-source).  
