# 🏃 Fitness Data Analysis Project


# 📌 Project Overview

This project analyzes **fitness tracker data** to understand user activity patterns, calorie expenditure, and sleep behavior.

The analysis was performed using **SQL, Python (Pandas), and Power BI** to transform raw fitness data into meaningful insights and interactive dashboards.

The objective of this project is to demonstrate a **complete data analytics workflow from raw dataset to visualization**.

---

# 📊 Dataset Description

The dataset used in this project is the **Fitbit Fitness Tracker Dataset**, which contains activity and health-related metrics collected from wearable fitness devices.

### Dataset Files

📁 dailyActivity_merged.csv  
📁 dailySteps_merged.csv  
📁 dailyCalories_merged.csv  
📁 dailyIntensities_merged.csv  
📁 sleepDay_merged.csv  

### Key Attributes

✔ User ID  
✔ Activity Date  
✔ Total Steps  
✔ Calories Burned  
✔ Active Minutes  
✔ Sedentary Minutes  
✔ Sleep Duration  
✔ Time in Bed  

---

# 🛠 Tools & Technologies Used

| Tool | Purpose |
|-----|------|
| 💾 SQL (MySQL) | Data storage and querying |
| 🐍 Python (Pandas, Matplotlib) | Data cleaning and analysis |
| 📊 Power BI | Interactive dashboards and visualization |

---

# 🔄 Project Workflow

```
Raw Dataset
     ↓
SQL Database
     ↓
Python Data Analysis
     ↓
Power BI Dashboard
     ↓
Insights & Conclusions
```

---

# 🗄 SQL Data Analysis

SQL was used to create the database and perform analytical queries on the dataset.

### Key SQL Analysis

✔ Total steps taken by each user  
✔ Average calories burned by users  
✔ Activity intensity analysis  
✔ User activity distribution  

### Example SQL Query

```sql
SELECT Id, SUM(TotalSteps) AS TotalSteps
FROM daily_activity
GROUP BY Id
ORDER BY TotalSteps DESC;
```

---

# 🐍 Python Data Analysis

Python was used to perform **exploratory data analysis using Pandas**.

### Tasks Performed

✔ Dataset loading  
✔ Data preprocessing  
✔ Feature engineering  
✔ Correlation analysis  
✔ Data visualization  

### Visualizations Created

📊 Steps by Weekday  
📊 Activity Intensity Distribution  
📊 Correlation Heatmap  
📊 Steps vs Calories Scatter Plot  

---

# 📈 Power BI Dashboards

Two interactive dashboards were created.

---

## 📊 Activity Dashboard

This dashboard analyzes **user activity patterns**.

### Visualizations

✔ Average Steps  
✔ Average Calories Burned  
✔ Average Active Minutes  
✔ Steps by Weekday  
✔ Calories by Weekday  
✔ Activity Intensity Distribution  
✔ Steps vs Calories Scatter Plot  

---

## 😴 Sleep Dashboard

This dashboard analyzes **user sleep behavior**.

### Visualizations

✔ Average Sleep Minutes  
✔ Average Time in Bed  
✔ Sleep Efficiency  
✔ Sleep Duration by Weekday  
✔ Sleep Distribution  
✔ Sleep vs Steps Analysis  

---

# 🔍 Key Insights

📌 Average daily steps are approximately **7000–8000 steps**

📌 Most users spend more time in **lightly active activities**

📌 There is a **strong positive correlation between steps and calories burned**

📌 Average sleep duration is approximately **7 hours**

---

# 📂 Project Structure

```
Fitness_Data_Analysis_Project
│
├── fitness_project.sql
├── Bellabeat_Pandas_Analysis.ipynb
├── fitness_dashboard.pbix
├── Fitness_Data_Analysis_Project_Report.pdf
└── Project_Demo_Video.mp4
```

---

# 🎯 Conclusion

This project demonstrates how **SQL, Python, and Power BI can be combined to analyze real-world fitness data and generate meaningful insights**.

The dashboards provide clear visualization of activity and sleep patterns, helping understand lifestyle behavior.

---

# 👨‍💻 Author

**Ankit Yadav**  
🎓 Master of Computer Applications (MCA) 

---

⭐ If you like this project, feel free to give it a **star on GitHub**.
