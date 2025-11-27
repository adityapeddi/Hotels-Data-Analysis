# Hotels-Data-Analysis
This analysis provides an end-to-end ad-hoc analytics workflow for the hospitality domain. It explores, cleans, and analyzes hotel booking data from multiple datasets.

## 📌 Overview
This repository contains an end-to-end **ad-hoc analytics project** for the hospitality domain.  
It focuses on exploring, cleaning, merging, and analyzing hotel booking datasets to uncover insights about:

- Booking trends  
- Platform performance  
- Hotel capacity utilization  
- Customer ratings  
- Revenue patterns  

All analysis is performed in the Jupyter Notebook:

**`exercise_solution.ipynb`**

---

## 📂 Datasets

The project uses multiple CSV files that represent both dimension and fact tables.

### **Dimension Tables**
| File | Description |
|------|-------------|
| `dim_date.csv` | Calendar metadata for booking dates |
| `dim_hotels.csv` | Hotel information (city, category, etc.) |
| `dim_rooms.csv` | Room-level details including capacity |

### **Fact Tables**
| File | Description |
|------|-------------|
| `fact_bookings.csv` | Individual booking details |
| `fact_aggregated_bookings.csv` | Daily aggregated bookings and capacity |

These datasets collectively support detailed ad-hoc analytics.

---

## 🧭 Project Workflow

### **1. Data Import & Exploration**
- Loaded datasets into Pandas  
- Reviewed schema, summary statistics, and sample data  
- Explored booking platform distribution  
- Visualized trends such as bookings per day and capacity usage  

### **2. Data Cleaning**
Key steps included:
- Removing invalid/negative guest counts  
- Handling null and duplicate entries  
- Validating rating ranges  
- Standardizing date and categorical fields  

### **3. Data Merging & Feature Engineering**
- Joined fact and dimension tables  
- Created derived metrics such as:  
  - `revenue_realized`  
  - Booking capacity indicators  
  - Date-based attributes  

### **4. Analysis & Insights**
Some insights derived in the notebook:
- Identification of days where bookings exceeded capacity  
- Hotels with highest cumulative room capacity  
- Platform-wise contribution to total revenue  
- Average customer ratings per city  

### **5. Visualizations**
The notebook includes multiple charts:
- Bar chart: booking platform distribution  
- Pie chart: revenue share by booking platform  
- Trend lines and exploratory plots  

---

## 💡 Tech Stack

- **Python 3.x**  
- **Pandas** – data manipulation  
- **Matplotlib** – visualizations  
- **Jupyter Notebook** – interactive analytics  
