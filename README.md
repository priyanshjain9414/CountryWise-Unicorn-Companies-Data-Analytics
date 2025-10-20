#  Unicorn Data Analytics Project

##  Overview
The **Unicorn Data Analytics Project** focuses on analyzing global startup companies that have achieved **unicorn status** — privately held startups valued at **over $1 billion**.  
Using Python for **Exploratory Data Analysis (EDA)** and **Power BI** for visualization, this project aims to uncover insights into investment trends, valuation growth, industry distribution, and geographic dominance in the startup ecosystem.

---

##  Objective
The goal of this project is to:
- Analyze trends in unicorn startups based on valuation, funding, and founding year.
- Identify which **industries, countries, and investors** dominate the unicorn landscape.
- Visualize key metrics and growth patterns through **interactive dashboards**.
- Gain insights into how the startup ecosystem has evolved over time.

---

##  Tools & Technologies Used
###  **Python (for EDA)**
- **Libraries:**  
  `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`
- **Tasks Performed:**  
  - Data cleaning and transformation  
  - Handling missing and inconsistent values  
  - Exploratory data analysis (EDA)  
  - Statistical summary and data visualization  

###  **Power BI (for Dashboard)**
- Created an **interactive dashboard** to visualize:  
  -  Industry-wise unicorn distribution  
  -  Country and continent-wise analysis  
  -  Top-valued unicorn companies  
  -  Trends by founding year and funding type  
  -  Top investors contributing to unicorn growth  

---

##  Data Source
The dataset was obtained from **public startup datasets** available on platforms like:
- [Kaggle – Unicorn Companies Dataset](https://www.kaggle.com/datasets)  

The dataset includes attributes such as:
- Company name  
- Country and city of origin  
- Industry sector  
- Date joined the unicorn list  
- Valuation (in billions)  
- Funding amount and investors  
- Year founded  

---

##  Exploratory Data Analysis (EDA)
The EDA was performed using **Python** to identify patterns, relationships, and anomalies within the dataset.

###  Key Steps
1. **Data Cleaning** – Removing duplicates, handling missing values, and formatting dates.  
2. **Feature Engineering** – Creating derived features like company age, funding-to-valuation ratio, etc.  
3. **Descriptive Analysis** – Summarizing data with statistics and group-wise insights.  
4. **Visualization** – Using Seaborn, Matplotlib, and Plotly to create:
   - Bar and Pie charts for industry and country breakdown  
   - Line charts for unicorn growth trends over the years  
   - Scatter plots to visualize valuation vs funding correlation  
   - Heatmaps for identifying data relationships  

---

##  Power BI Dashboard Highlights
The **Power BI dashboard** provides a dynamic and interactive overview of the unicorn dataset.

###  Dashboard Features
-  **Global Unicorn Map:** Distribution of unicorns across the world  
-  **Industry Insights:** Top-performing industries and valuation comparisons  
-  **Timeline View:** Year-wise growth of unicorn companies  
-  **Top Investors:** Key investors contributing to multiple unicorns  
-  **Valuation Metrics:** Total valuation and average valuation per region  

###  Dashboard Preview

**Home(Page 1)**
![Home(Page 1)](Dashboard%20Images/Home%20(Page%201).JPG)

**Global View(Page 2)**
![Global View(Page 2)](Dashboard%20Images/Global%20View%20(Page%202).JPG)

**Company View(Page 3)**
![Company View(Page 3)](Dashboard%20Images/Company%20View%20(Page%203).JPG)

**City View(Page 4)**
![City View(Page 4)](Dashboard%20Images/City%20View%20(Page%204).JPG)

**Induustry View(Page 5)**
![Induustry View(Page 5)](Dashboard%20Images/Industry%20View%20(Page%205).JPG)

**Summary(Page 6)**
![Summary(Page 6)](Dashboard%20Images/Summary%20(Page%206).JPG)

---

##  Project Structure
```
COVID19-Data-Analytics/
├── Unicorn_Companies_data.csv
├── Unicorn_Dashboard.pbix
├── Unicorn_eda.ipynb
├── Unicorn_Report.pdf
├── icons.jpg
├── Dashboard Images/
├   ├── Home(Page 1)
├   ├── Global View(Page 2)
├   ├── Company View(Page 3)
├   ├── City View(Page 4)
├   ├── Induustry View(Page 5)
├   ├── Summary(Page 6)
├── README.md
```

---

##  How to Run the EDA Notebook

Clone this repository:
```bash
git clone https://github.com/your-username/Unicorn-Data-Analytics.git
```

Navigate to the project directory:
```bash
cd Unicorn-Data-Analytics
```

Open the Jupyter Notebook:
```bash
jupyter notebook notebooks/unicorn_data_eda.ipynb
```
Run all cells to view the analysis and visualizations.

---

##  Key Insights
- 🇺🇸 The **United States**, **China**, and **India** lead in the number of unicorns.  
-  The **FinTech** and **E-commerce** sectors dominate in terms of valuation.  
-  The number of unicorns has grown exponentially since 2015.  
-  A small group of investors have funded multiple unicorn companies.  
-  The average unicorn valuation continues to rise, driven by strong venture capital activity.  

---

##  Future Enhancements
- Integrate real-time data through APIs (e.g., Crunchbase or CB Insights).  
- Build a web dashboard using **Plotly Dash** or **Streamlit** for broader accessibility.  
- Add predictive modeling to estimate future unicorn valuations.  
- Include funding stage analysis to track investment trends.  

---

##  Author
**Priyansh Jain**  

 [GitHub: @priyanshjain9414](https://github.com/priyanshjain9414)  
 [Email: priyanshjain903@gmail.com](mailto:priyanshjain903@gmail.com)


---

##  Conclusion
This project provides a comprehensive analysis of unicorn companies worldwide, highlighting investment trends, regional dominance, and industry dynamics.  
By combining **Python EDA** with **Power BI Dashboards**, it transforms raw data into actionable business insights — a great example of data analytics in the startup ecosystem.
