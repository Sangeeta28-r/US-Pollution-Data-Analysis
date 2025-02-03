


![Us pollution1](https://github.com/user-attachments/assets/8f286ea9-d477-4800-bebd-a230ac858335)



![US pollution2](https://github.com/user-attachments/assets/2ba71ce2-e41b-435a-af24-8df2d742fbf6)



![US pollution3](https://github.com/user-attachments/assets/a432c33d-c610-4db2-a693-7dc31983429d)



![Us pollution4](https://github.com/user-attachments/assets/0647e252-bb6e-4e26-b875-fd7a794dedbc)



![US pollution5](https://github.com/user-attachments/assets/b252a26d-77a0-4c30-9067-4c16b2be9e34)


# U.S. Pollution Data Analysis - Power BI Dashboard

## 📌 Project Overview
This project analyzes U.S. air pollution data from 2006 to 2010, focusing on four major pollutants:
- **Carbon Monoxide (CO)**
- **Ozone (O3)**
- **Sulphur Dioxide (SO2)**
- **Nitrogen Dioxide (NO2)**

The dataset provides daily pollution levels for each pollutant across different states, counties, and cities. The aim is to build an **interactive Power BI dashboard** to visualize and derive insights into air pollution trends, affected regions, and pollutant severity.

## 📊 Data Description
The dataset includes the following fields:
- **State Name & Code**: Identifies U.S. states
- **County Code & Name**: Represents counties within each state
- **City Name**: Specifies cities where pollution was recorded
- **Site Number & Address**: Location details of monitoring stations
- **Date Local**: The date of pollution recording
- **Pollutant-Specific Columns**:
  - **NO2** (Parts Per Billion) - Mean, 1st Max Value, 1st Max Hour, AQI
  - **O3** (Parts Per Million) - Mean, 1st Max Value, 1st Max Hour, AQI
  - **SO2** (Parts Per Billion) - Mean, 1st Max Value, 1st Max Hour, AQI
  - **CO** (Parts Per Million) - Mean, 1st Max Value, 1st Max Hour, AQI

🚨 **Data Cleaning**: All null values were replaced with `0`.

## 📌 Dashboard Structure
The Power BI dashboard consists of **five pages** with interactive visuals:

### 🔹 Page 1: Overview
- Displays all four pollutants with navigation buttons.
- Interactive slicers for states, cities, counties, and years.
- A filled map visualizing pollution across U.S. states.
- A table showing county names with their respective codes.
- A quarterly breakdown of all four pollutants.

### 🔹 Page 2: **Carbon Monoxide (CO)**
- **Top 10 states** with the highest CO pollution.
- **Key Metrics**: 1st Max Hour, 1st Max Value, and CO Units.
- **AQI Table**: Highlights highest (🔴 red) and lowest (🟢 green) CO levels per state.
- **Bar Chart**: Displays maximum CO levels in each state.
- **Line Chart**: Shows yearly CO AQI trends.
- **Top Polluted City** based on CO levels.
- **Interactive Slicer**: Allows filtering by state and date range.

### 🔹 Page 3: **Ozone (O3)**
- **Top 10 states** with the highest O3 pollution.
- **Key Metrics**: 1st Max Hour, 1st Max Value, and O3 Units.
- **AQI Table**: Highlights highest (🔴 red) and lowest (🟢 green) O3 levels per state.
- **Bar Chart**: Displays maximum O3 levels in each state.
- **Line Chart**: Shows yearly O3 AQI trends.
- **Top Polluted City** based on O3 levels.
- **Interactive Slicer**: Allows filtering by state and date range.

### 🔹 Page 4: **Sulphur Dioxide (SO2)**
- **Top 10 states & cities** with the highest SO2 pollution.
- **Key Metrics**: 1st Max Hour, 1st Max Value, and SO2 Units.
- **AQI Table**: Highlights highest (🔴 red) and lowest (🟢 green) SO2 levels per state.
- **Bar Chart**: Displays maximum SO2 levels in each state.
- **Line Chart**: Shows yearly SO2 AQI trends.
- **Top Polluted City** based on SO2 levels.
- **Interactive Slicer**: Allows filtering by state and date range.

### 🔹 Page 5: **Nitrogen Dioxide (NO2)**
- **Top 10 states** with the highest NO2 pollution.
- **Key Metrics**: 1st Max Hour, 1st Max Value, and NO2 Units.
- **AQI Table**: Highlights highest (🔴 red) and lowest (🟢 green) NO2 levels per state.
- **Bar Chart**: Displays maximum NO2 levels in each state.
- **Line Chart**: Shows yearly NO2 AQI trends.
- **Interactive Slicer**: Allows filtering by state and date range.

## 📌 Features & Insights
✅ **Interactive Navigation** – Users can seamlessly switch between pollutant-specific pages.
✅ **Slicers for Filtering** – Enables filtering data by **state, county, city, and date**.
✅ **Heatmaps & Color Coding** – Easily identify high and low pollution zones.
✅ **Historical Trends** – Yearly and quarterly trends help analyze pollution over time.
✅ **Top Polluted Areas** – Identifies states and cities with maximum pollution levels.

## 🚀 How to Use
1. **Clone the Repository**
   ```sh
   git clone https://github.com/Sangeeta28-r/US-Pollution-Data-Analysis.git
   ```
2. **Open Power BI Desktop** and load the `.pbix` file.
3. **Explore Interactive Insights** using slicers and filters.

## 📂 Repository Structure
```
📁 US-Pollution-Data-Analysis/
│-- 📂 Data/               # Raw dataset (CSV, Excel)
│-- 📂 Reports/            # Power BI reports and visuals
│-- 📜 README.md          # Project documentation
│-- 📜 US_Pollution.pbix   # Power BI dashboard file
```

## 📌 Conclusion
This Power BI dashboard provides **detailed insights into air pollution levels** across the U.S., enabling stakeholders to:
- Identify **highly polluted states and cities**
- Track **pollution trends over time**
- Make **data-driven decisions for air quality improvements**

📢 **Contributions & Feedback**: Feel free to **raise issues**, **suggest enhancements**, or **contribute** to this project! 🚀

---
🔗 **GitHub Repository**: [US Pollution Data Analysis](https://github.com/Sangeeta28-r/US-Pollution-Data-Analysis)


