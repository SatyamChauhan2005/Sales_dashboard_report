# 📊 Power BI Sales, Employee & Department Dashboard

Welcome to my **Power BI Dashboard Project**, where I combined data from **Sales**, **Employee**, and **Department** tables to create a fully interactive and insightful dashboard. This project is designed to provide a 360° view of performance across countries, employees, and departments.
# Dashboard 
<a href="https://github.com/SatyamChauhan2005/Sales_dashboard_report/blob/main/Sales_dashboardPNG.png"/a> 
![Dashboard Screenshot](https://github.com/SatyamChauhan2005/Sales_dashboard_report/blob/main/Sales_dashboardPNG.png)

---

## 🚀 Project Overview

This dashboard gives key insights into:
- 🌍 Country-wise sales & budget distribution
- 👩‍💼 Employee-wise salary breakdown
- 🗓️ Monthly joining trend of employees
- 📌 Real-time KPIs on sales & salaries

---

## 🧾 Data Sources
# Raw Data 
[Download Dept.xlsx](https://github.com/SatyamChauhan2005/Sales_dashboard_report/blob/main/Dept.xlsx)<br>
[Download Employee.xlsx](https://github.com/SatyamChauhan2005/Sales_dashboard_report/blob/main/Emp_data.xlsx)<br>
[Download Company.xlsx](https://github.com/SatyamChauhan2005/Sales_dashboard_report/blob/main/Company_data.xlsx)


The report is based on the following tables:

| Table Name     | Description |
|----------------|-------------|
| **Sales**      | Contains all transaction-level sales data |
| **Employee**   | Includes employee name, joining month, and department |
| **Department** | Holds department-level budget and info |

---

## 🔍 Key Features & Visuals

✨ **Visual Highlights**:
- **Donut Chart** showing total sales by country
- **Stacked Bar** for join month-wise employee count
- **Map Visual** for geo-distribution of budget
- **Column Chart** for budget counts & averages by country
- **Line & Area Chart** for salary trends by employee and country
- **Dynamic KPIs** for:
  - 🧾 **Total Salary**: `1.11M`
  - 💰 **Total Sales Count**: `1380` (+26.61%)
  - 📈 **Calculated Salary Metric**: `265.04K` growth

---

## 🧩 Data Model & Relationships

The model uses a **star schema** structure:

- **Fact Table**: `Sales`
- **Dimension Tables**:
  - `Employee` (linked via `EmployeeID`)
  - `Department` (linked via `DepartmentID`)
  
**Key Relationships**:
- Sales ➡️ Employee ➡️ Department

---

## 💡 Tools & Skills Used

- ✅ Power BI Desktop
- ✅ DAX (Data Analysis Expressions)
- ✅ Data Modeling & Relationships
- ✅ Interactive Visualizations
- ✅ Dashboard Design & UX

---

## 🖥️ How to Use

1. Clone/download this repository
2. Open the `.pbix` file in Power BI Desktop
3. Interact with filters, maps, and KPIs to explore insights

---

## 🛠 Future Enhancements

- Integrate real-time data from a SQL source
- Add forecasting metrics using DAX
- Include drill-through for department-level reports

---

## 🤝 Let's Connect!

If you liked this dashboard or have feedback, feel free to connect with me on [LinkedIn](#) or [GitHub](#).

---

## 📌 License

This project is for **educational and portfolio** purposes only.

---

> ✅ **Pro Tip**: Upload the `.pbix` file and the screenshot image in your GitHub repo. You can rename the image or adjust the path in the `README.md` accordingly.

