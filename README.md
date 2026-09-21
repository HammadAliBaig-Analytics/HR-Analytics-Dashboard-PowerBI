# 👥 HR People Analytics Dashboard — Power BI

An interactive, four-page Power BI dashboard that gives HR and business leaders a clear view of workforce composition, employee attrition, and how pay and performance vary across the organization.

📄 A PDF export of all four pages is available in [`HR_dashboard.pdf`](HR_dashboard.pdf).

---

## 🎯 Project Objective

Help HR teams answer questions like:

- How big is the workforce, and how is it made up (age, gender, marital status, education, org level)?
- What is the attrition rate, and which roles, age groups and departments are losing the most people?
- How do pay, salary hikes and performance ratings differ across job levels and departments?
- Who are the high performers, and how long do employees typically stay?

---

## 🗂️ Dashboard Pages

The report has **4 pages**, each with a shared header, a KPI strip, a slicer panel and a side navigation menu.

| # | Page | What it shows |
|---|------|---------------|
| 1 | **Executive Overview** | Headline KPIs plus departmental headcount with attrition split (Yes/No), workforce composition by job role, total employees by department and gender distribution. |
| 2 | **Workforce Analytics** | Age demographics, marital status, headcount by organizational level, educational background, travel frequency and tenure segmentation (0–2, 3–5, 6–10, 10+ years). |
| 3 | **Attrition Analytics** | Top job roles by attrition count, attrition by age group, attrition share by gender, and work-life balance vs. attrition. |
| 4 | **Compensation & Performance** | Monthly income by job level, average salary hike % by department, and performance rating contribution vs. total workforce. |

---

## 📐 KPIs

The same six KPI cards appear at the top of every page:

| KPI | Value |
|-----|-------|
| **Total Employees** | 4.4K |
| **Active Employees** | 3.7K |
| **Attrition Rate** | 16.1% |
| **Avg. Tenure** | 7.01 years |
| **Avg. Age** | 37 |
| **High Performers** | 678 |

---

## 🎛️ Interactivity

- **Slicers** on every page: Gender, Department, Education Field and Job Role
- **Side navigation menu** to move between the four pages
- **Cross-filtering** between visuals, so every chart and KPI responds to the slicers

---

## 🛠️ Tools & Techniques

- **Power BI Desktop** — data modelling and report design
- **Power Query** — data preparation
- **DAX** — measures for headcount, attrition rate, tenure, age and high performers
- **Design** — dark navy sidebar with an orange/blue palette, KPI cards and a consistent layout across all pages

---

## 📁 Repository Structure

```
├── HR_Dashboard.pbix         # Power BI report file
├── HR_dashboard.pdf          # PDF export of all 4 pages
└── README.md
```

---

## 🚀 How to Use

1. Download or clone this repository
2. Open the `.pbix` file in **Power BI Desktop**
3. Use the slicers and the side menu to explore the dashboard

---

## 💡 Key Insights

- **Headline numbers:** About 4.4K employees, of whom 3.7K are still active, giving a **16.1% attrition rate** (roughly 711 leavers). Average age is 37 and average tenure is 7.01 years.
- **Attrition is concentrated in a few roles:** Sales Executive (165), Research Scientist (159) and Laboratory Technician (126) together account for about 63% of all leavers.
- **Age matters:** Employees aged 26–35 account for the most attrition (348, close to half of all leavers), and they are also the largest age group in the workforce (1,818 employees).
- **Gender split of attrition:** Roughly 60% of leavers are male and 40% female.
- **Departments:** Research & Development has the most leavers (453), followed by Sales (201).
- **Workforce structure:** About 73% of employees sit at organizational levels 1 and 2, and 45.8% are married.
- **Compensation:** Average salary hikes are similar across departments (R&D 15.29%, Sales 15.10%, HR 14.76%). Job level 4 has the highest average monthly income (77.9K), while the other levels sit between about 62K and 66K.
- **Travel:** Around 71% of employees travel rarely.

---

## 👤 Author

**Hammad**

- LinkedIn: [linkedin.com/in/hammad-ali-baig](https://www.linkedin.com/in/hammad-ali-baig)
- GitHub: [github.com/HammadAliBaig-Analytics](https://github.com/HammadAliBaig-Analytics)

Feedback and suggestions are welcome!
