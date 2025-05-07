
# 💼 Smart Hiring Analytics Dashboard

Empowering Recruitment Decisions Through Data Insights in Cybersecurity.

---

## 📌 1. Project Overview
The Smart Hiring Analytics Dashboard is a comprehensive Power BI-based application designed to help HR professionals, hiring managers, and workforce planners make informed decisions in the cybersecurity job market. This dashboard visualizes trends in salary, job listings, gender representation, skill requirements, certifications, and remote work to deliver actionable insights for strategic hiring.

---

## 📊 2. Key Features
- Role-wise average, median, and mode salary comparison
- Job trends over time by experience level and employment type
- Remote job flexibility insights
- Most requested cybersecurity skills
- Top certifications by job roles
- Gender-based analysis in employment distribution
- Region-based job listings visualization
- Forecasted salary trends and hiring projections
- Employment type and experience filters
- Interactive slicers for job title, year, and industry demand

---

## 🧑‍🤝‍🧑 3. Team Members and Contributions
| Name | Role | Contribution |
|------|------|--------------|
| |  Sai Krishna Teja| Dashboard Design, Data Integration, Traceability Matrix |
| Sujan Buddha  | Data Analyst | Skill and Certification Mapping, Data Cleaning |
|  Pavan Kumar | Visualization Specialist | Map and Salary Visualizations, UX Feedback |
| Vikas Reddy  | Data Engineer | DAX Calculations, CSV Preprocessing |
| Suneel Kumar  | Documentation Lead | README, PPT, Traceability Validation |

---

## 🗃️ 4. Project Structure

```
Smart-Hiring-Analytics-Dashboard/
├── Cyber_Industry_Analytics_Dashboard.pbix
├── cyber_salary_dataset.csv
├── traceability_matrix.docx
├── README.md
├── Cyber_Industry_Analytics.pptx
├── Final-Report-Structure.docx
├── Preliminary_Design_Document.docx
├── Assignment-1-MRP.docx
├── Week6_Group_17.pdf
├── Smart_Hiring_Dashboard_README.md
```

---

## 🧾 5. Data Source
- **Original Dataset**: [Cybersecurity Salary Dataset (Kaggle)](https://www.kaggle.com/datasets/dannyrevaldo/salary-cyber-security-jobs)
- Format: CSV
- Preprocessing: Cleaning, deduplication, mapping of abbreviations (e.g., job roles, company size)
- Validation: Handled in Power BI and Excel

---

## 🛠️ 6. Tools and Technologies
- Power BI (Main application)
- Microsoft Excel (For data prep and validation)
- GitHub (Version control and final submission)
- DAX (Data Analysis Expressions for calculations)

---

## 📥 7. Installation Guide
1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/)
2. Clone this repository
3. Open the file `Cyber_Industry_Analytics_Dashboard.pbix` using Power BI Desktop
4. Use the interactive slicers and explore visualizations

---

## 🧩 8. Dashboard Pages and Components

### Page 1: **Job Market Overview**
- Line graph of job listings over years by experience level
- Area chart of employment type trends
- Salary forecast line chart

<img width="1238" alt="Screenshot 2025-05-06 at 12 09 36 AM" src="https://github.com/user-attachments/assets/296592ca-26c6-428f-abd2-c1d2dddf3aa5" />


### Page 2: **Job Roles & Salary Trends**
- Treemap of top job roles
- Radar chart showing average salary per job
- Horizontal stacked chart showing salary by remote flexibility

<img width="1238" alt="Screenshot 2025-05-06 at 12 09 55 AM" src="https://github.com/user-attachments/assets/c28b6fa4-bd77-4b6e-ab3c-a16be22f3c81" />


### Page 3: **Skills & Certifications**
- Word cloud of most requested skills
- Table of top certifications and their salaries
- Pie chart showing optional vs required skills

<img width="1238" alt="Screenshot 2025-05-06 at 12 10 10 AM" src="https://github.com/user-attachments/assets/e5a30e24-1bce-490e-b7c9-2e9d86747a92" />


### Page 4: **Gender & Employment Insights**
- Clustered bar: Job listings by gender & employment type
- Donut chart: Gender ratio
- Map: Job listings by region and experience

<img width="1238" alt="Screenshot 2025-05-06 at 12 10 27 AM" src="https://github.com/user-attachments/assets/931b064f-6536-459e-a945-27ab3ad79db0" />


---

## 📍 9. Geographic Visualization
- Added custom region and location columns (Midwest, South, etc.)
- Bing Map visualization based on U.S. city distribution
- Visualized demand trends per region

---

## 🧮 10. DAX Highlights
- Measures: `Avg Salary`, `Total Job Listings`, `RemoteRatioSplit`, etc.
- Calculated Columns: Gender simulation, skill categorization, region mapping

---

## ✅ 11. Validation and Accuracy
- Cross-checked calculated fields with Excel formulas
- Used slicers to verify visual filtering
- Applied traceability matrix for functional validation

---

## 📋 12. Traceability Matrix
- Created as a Word document
- Aligns project charter requirements with information output, visual delivery, and validation methods
- [📄 View Traceability Matrix](./traceability_matrix.docx)

---

## 🎥 13. Video Walkthrough
A 5-minute video presentation walks through all dashboard pages, slicers, and validations.
Includes:
- Functional demo
- Highlighting how requirements are met
- Explained filters and decision points
  
👉 [Watch the video](https://drive.google.com/file/d/1Jsa8RzmN7aRRRrh_7a_NrNG5FPhrsvW6/view?usp=drive_link)

---

## 📁 14. Supporting Files
- Power BI Dashboard `.pbix`
- CSV Dataset
- All Word/PDF project documents
- GitHub-hosted README and PPT files


---

## 📜 15. License
MIT License. This dashboard is open-source and available for academic, personal, and professional adaptation.

---

## 🙌 16. Acknowledgements
- Faculty mentors
- Class peers for feedback
- Kaggle contributors for dataset
