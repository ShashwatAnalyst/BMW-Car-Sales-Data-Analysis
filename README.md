# BMW Car Sales  Analysis  <a href="https://public.tableau.com/app/profile/shashwat.sungh/viz/BMWModelSalesPerformanceDashboard/Dashboard1?publish=yes" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/mrankitgupta/mrankitgupta/a768d6bf0a001f03327578ae12f8867e4056cbaf/tableau-software.svg" alt="tableau" width="55" height="40"/></a>  <a href="notebook/BMW-Car-Sales-Data-Analysis.ipynb" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="45" height="50"/></a>    <a href="https://www.kaggle.com/datasets/y0ussefkandil/bmw-sales2010-2024" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/kaggle/kaggle-original.svg" alt="python" width="45" height="50"/></a>

## About This Project  
This project dives into the analysis of BMW car sales data from **2010 to 2024**, covering multiple models, regions, and segmentation factors. The aim is to uncover performance trends, model rankings, regional revenue distribution, and behavioral insights through an **interactive Tableau dashboard**.  

The dataset simulates BMW sales transactions, including attributes like model details, paint color, fuel type, transmission, region, and performance metrics. The project is ideal for practicing feature engineering, exploratory analysis, and dashboard design for automotive sales.  

---

## About Data  

The dataset was sourced from **Kaggle** and already came clean. No wrangling was required. However, I added new features like **Revenue** and **Model Age Segment** for deeper analysis.  

### Dataset Columns  

| Column Name            | Description                                      |  
|------------------------|--------------------------------------------------|  
| **Model**              | BMW model name (e.g., X5, i8, 3 Series)         |  
| **Year**               | Sales year (2010–2024)                          |  
| **Region**             | Sales region (e.g., Asia, Europe, North America)|  
| **Color**              | Paint color of the car                          |  
| **Fuel_Type**          | Petrol, Diesel, Electric, Hybrid                |  
| **Transmission**       | Automatic or Manual                             |  
| **Engine_Size_L**      | Engine size in liters                           |  
| **Mileage_KM**         | Mileage performance (in kilometers)             |  
| **Price_USD**          | Price of the car in USD                         |  
| **Sales_Volume**       | Number of units sold                            |  
| **Sales_Classification** | Classification of sales (e.g., High/Medium/Low)|  

---

## Purposes of the Project  
The primary goal is to analyze **BMW sales data by model, region, and segmentation factors** and present findings interactively.  

By evaluating sales and revenue trends, model performance, and segmentation breakdowns, this project helps identify growth opportunities, optimize strategies, and understand customer preferences.  

---

## Approach Used  

***1. Feature Engineering***  
- Added **Revenue** (Sales_Volume × Price_USD).  
- Added **Model Age Segment** (based on Year) for trend comparison.  

***2. Exploratory Data Analysis (EDA) – Jupyter Notebook***  
- Focused on **overall sales and revenue** across all available dimensions (region, fuel type, transmission, color, mileage, engine size).  
- Conducted segmentation-based insights to understand buyer preferences.  

***3. Dashboard Creation (Tableau)***  
- Entirely focused on **sales and revenue analysis per model**.  
- Made the dashboard **dynamic** with:  
  - Interactive filters (Year, Region, Fuel Type, Transmission, Color).  
  - Car images per model with price ranges.  
  - Visuals for segmentation (paint color, fuel type, transmission).  
  - Performance factors (mileage, engine size).  
  - Global revenue distribution map.  

---

## Business Questions to Answer  

### Model Sales & Performance  
1. Which BMW models generated the highest revenue and sales over the years?  
2. How do sales trends vary by model and year?  
3. What is the price range for key BMW models?  
4. How does model performance (mileage, engine size) relate to sales?  

### Segmentation & Regional Analysis  
1. Which paint colors, fuel types, and transmissions are most popular among buyers?  
2. Which regions contribute the most to overall revenue and sales?  
3. How does regional revenue distribution change over time?  
4. What segmentation factors drive higher sales or revenue?  

---

## Dashboard Screenshots  

### BMW Model Sales Dashboard (2010–2024)  
![BMW Model Sales Dashboard](https://github.com/ShashwatAnalyst/BMW-Car-Sales-Data-Analysis/blob/main/dashboard/Screenshot%202025-09-16%20140013.png?raw=true)  
![BMW Model Sales Dashboard](https://github.com/ShashwatAnalyst/BMW-Car-Sales-Data-Analysis/blob/main/dashboard/Screenshot%202025-09-16%20140046.png?raw=true)  

---

## Insights from Dashboard  
- Identified **top BMW models** by revenue and units sold.  
- Segmented sales by **paint color, fuel type, and transmission**, spotting preferences and market trends.  
- Mapped **regional revenue**, highlighting top-performing markets (South America, Asia, Europe).  
- Analyzed **sales by performance** (mileage and engine size), uncovering buyer priorities.  
- Used **interactive filtering** to compare models, years, and segmentation breakdowns.  

---

## Important Links  
- [View Live Tableau Dashboard](https://public.tableau.com/app/profile/shashwat.sungh/viz/BMWModelSalesPerformanceDashboard/Dashboard1?publish=yes)  
- [Open Main Jupyter Notebook](notebook/BMW-Car-Sales-Data-Analysis.ipynb)  
- [Kaggle Dataset: BMW Sales (2010–2024)](https://www.kaggle.com/datasets/y0ussefkandil/bmw-sales2010-2024)  


---

## Project Structure  

```
├── data
|   └── BMW sales data (2010-2024).csv
│
├── notebook
│   ├── BMW-Car-Sales-Data-Analysis.ipynb
|   ├── final.csv
|   └── report.csv  
│
├── dashboard
│   ├── BMW Model Sales Performance Dashboard.twbx # Tableau dashboard file
|   └── dashboard_image_1.png
│
└── README.md
```

## Author
**Shashwat Singh**  
Passionate about **Data Analytics, Visualization, and Storytelling with Data**.<br>
| 💼 [LinkedIn](https://www.linkedin.com/in/shashwat-singh-bb2730357/)  | 👤 [Portfolio](https://www.shashwatanalyst.online/)  
