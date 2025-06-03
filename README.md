# 📊 HR Analytics Dashboard – Power BI Project

This Power BI project was built to create an **interactive HR performance and attrition dashboard** for a fictitious company, **Atlas Labs**, a growing tech firm. The goal is to empower the HR team with actionable insights into employee performance and factors influencing turnover, enabling smarter talent management decisions.

---

## 🧠 Objective

To design and implement a structured HR analytics solution that:
- Monitors **employee performance ratings**
- Identifies **key drivers of attrition**
- Helps HR professionals make **data-informed decisions**

---

## 🏗️ Data Model Design

The project uses a **Kimball dimensional modeling approach** with a **snowflake schema**, designed for scalability and analytical clarity.

### 🧾 Fact Table:
- **PerformanceRatings**: Captures multiple performance reviews per employee  
  *(11 columns, including rating date, rating level, satisfaction level, and employee ID)*

### 🧱 Dimension Tables:
- **Employee** – Employee demographic and ID info  
- **EducationLevel** – Formal education background  
- **RatingLevel** – Describes performance rating scale  
- **SatisfiedLevel** – Maps to employee satisfaction classifications  
- **Date** *(planned enhancement)* – Enables filtering by year, quarter, month, and day  

---

## 📈 Key Features of the Dashboard

- Visual summary of **performance distribution** across teams and departments  
- Drill-through filters by **satisfaction level, education, and rating**  
- Identification of **patterns in attrition vs. performance**  
- Structured and modular report navigation, suitable for **HR executives and managers**

---

## 🛠️ Tools & Techniques

- **Power BI** – For report development and data visualization  
- **Data Modeling** – Snowflake schema, relationship design  
- **DAX** – For calculated measures and advanced filters  
- **Kimball Methodology** – Applied to structure fact and dimension tables

---

## 📎 Report Sample

View full report (PDF): [HR_Analytics.pdf](https://github.com/user-attachments/files/20560959/HR_Analytics.1.pdf)

### 🔍 Report Snapshots

![HR Page 1](https://github.com/user-attachments/assets/c5bed3d3-1db2-4e49-acc0-43e8f6d0ae47)  
![HR Page 2](https://github.com/user-attachments/assets/ed719fb7-31b9-4625-9dd0-5d3e9ca29270)  
![HR Page 3](https://github.com/user-attachments/assets/37d75e44-3992-4539-92a6-62263aec8408)  
![HR Page 4](https://github.com/user-attachments/assets/9d9ddc44-f3af-4d11-945e-4346564baf11)

---

## 📌 Key Takeaway

This project showcases how structured data modeling in Power BI can turn raw performance data into **actionable HR insights**. By leveraging fact/dimension modeling and DAX measures, HR teams can proactively identify risk areas, promote high performers, and reduce turnover.

---

## 📬 Feedback & Future Improvements

- Adding **date intelligence** to enable time-series analysis  
- Incorporating **predictive modeling** using Power BI or Azure ML integration  
- Expanding dimension granularity (e.g., department-level attrition trends)

---

