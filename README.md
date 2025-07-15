# MSRP-predictive-Analysis

````markdown
# 🚗 Car Pricing & Product Strategy Analysis for Manufacturers

**Optimize pricing, identify consumer trends, and design profitable vehicles using data-driven insights.**

---

## 📌 Project Overview

With increasing competition and the rise of electric/hybrid technology, car manufacturers must understand what drives **consumer demand** and **profitability**. This project analyzes a real-world car dataset to:

- Predict pricing (MSRP) using car features
- Group vehicles by market segments
- Recommend an ideal car for development and pricing

---

## 📈 Key Insights

🔹 **Fuel Trends**: Regular and Premium fuel still dominate, but Electric/Hybrid adoption is rising fast  
🔹 **Top Categories**: SUVs and Sedans are most popular with higher MSRP in luxury trims  
🔹 **Feature Impact**: Engine HP, Fuel Type, and Vehicle Style are top pricing influencers  
🔹 **Segments Identified**: Budget, Mid-range Family, and Luxury-Tech clusters revealed via KMeans  

---

## 🚀 Final Recommendation

> ✅ **Mid-sized Premium SUV**  
> 🔋 Plug-in Hybrid or Electric  
> ⚙️ 200–250 HP, 4–6 Cylinders  
> ⛽ High Avg MPG or electric range  
> 💰 MSRP: $30,000–$45,000  

Perfectly balances performance, efficiency, and modern consumer needs.

---

## 🧠 Analysis Process

1. **Data Cleaning**  
   - Imputed missing values using median/mode  
   - Dropped high-missing columns (e.g., `Market Category`)  

2. **Feature Engineering**  
   - Created `Avg MPG`  
   - Grouped `Engine Fuel Type` into categories  

3. **Exploratory Data Analysis (EDA)**  
   - Visualized MSRP distribution, fuel trends, and style impact  
   - Identified top-value vehicle combinations  

4. **Regression Modeling**  
   - Predicted MSRP using Linear Regression  
   - Evaluated with RMSE  

5. **Market Segmentation**  
   - Used KMeans to identify buyer personas  
   - Labeled 3 distinct market segments  

---

## 📊 Visual Examples

<p align="center">
  <img src="visuals/fuel_type_distribution.png" width="45%">
  <img src="visuals/msrp_by_style.png" width="45%">
</p>

---

## 🛠️ Tech Stack

- Python (Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib)
- Jupyter Notebook
- Excel (for initial data audit)
- KMeans Clustering
- Linear Regression

---

## 📁 Folder Structure

```bash
├── data/            # Dataset file
├── notebooks/       # Jupyter notebook for analysis
├── visuals/         # Charts and plots
├── README.md        # This file
├── requirements.txt # Python libraries
````

---

## 👤 Author

**Basu Narayan**
Data Analyst | Automotive Analytics Enthusiast

---

## ⭐ If you found this useful, please star this repo and share it with fellow data enthusiasts!

````

---

### 📦 requirements.txt (basic version)
```txt
pandas
numpy
matplotlib
seaborn
scikit-learn
openpyxl
````

---

Would you like me to generate:

* The actual `README.md` file?
* The `Car_Pricing_Analysis.ipynb` with full code and visuals?

Let me know how you'd like to finalize it — for GitHub or even Kaggle!
