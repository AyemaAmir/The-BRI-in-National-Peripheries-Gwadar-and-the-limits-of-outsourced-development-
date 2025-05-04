# The BRI in National Peripheries: Gwadar and the Limits of Outsourced Development

A Power BI project exploring the structure, funding, and execution of over 900 development projects across Balochistan and Gwadar, offering a deep dive into public sector spending under the Belt and Road Initiative (BRI) framework.

---

## 🎯 Purpose

This project was built to analyze how development funds are actually used in some of Pakistan's most remote and strategically important regions. It converts raw government data into meaningful insights to answer critical questions like:

- Are funds reaching the right regions?
- Which ministries are efficient in utilizing their budgets?
- What role does foreign aid play in project execution?
- Are promises of development being fulfilled on the ground?


---
## 🔧 Tech Stack

- 🐍 Python – Data preprocessing, normalization, key generation
- 📊 Power BI – Data modeling, dashboard creation
- 🧠 DAX – Advanced metrics, time intelligence, calculated tables

---

## 📁 Project Structure

- **Raw Data**: Data was collected from multiple websites in a Multi-sheet Excel file (unstructured)
- **Python Scripts**: Clean and consolidate data
- **Power BI Model**:
  - Normalized Tables (Financial, Project Details, Year)
  - Bridge Table for many-to-many handling
  - DAX Measures (Utilization, Coverage, Aid Flags)
  - Derived Tables (Sectoral & Regional Trends)

---

## 📊 Dashboard Pages & Features

### 1. **Overview**
- Total 905 projects analyzed
- 755 projects in Balochistan, 156 in Gwadar
- Total cost: 7.01 Million | Expenditure: 1.93 Million
- Utilization Rate: 299.25% — shows over-expenditure patterns
- Top 5 most expensive projects listed
- Expenditure trends shown over time with foreign aid indicators
  
  ![image](https://github.com/user-attachments/assets/828d1945-2495-4099-9c6e-d879ba2327a2)


### 2. **Budget Allocation Analysis**
- Line charts showing allocation and expenditure trends (2013–2022)
- Gap between planned and actual utilization highlighted
- Budget Coverage at 90.8% (target: 80%)
- Local vs. Foreign Aid allocation trends by year

  ![image](https://github.com/user-attachments/assets/887b896a-d513-4f38-acad-015e606d032e)


### 3. **Sectoral Analysis**
- Communications Division gets the highest share of funding
- Establishment Division shows highest utilization rate
- Underperforming ministries identified (e.g., Commerce, Culture)
- Time-series of budget trends per ministry

![image](https://github.com/user-attachments/assets/087b208e-554a-43e4-84b6-c9541572ee93)

### 4. **Regional Analysis**
- Gwadar has fewer projects but higher utilization
- Balochistan receives far more funding overall
- Domestic funding dominates both regions, foreign aid fluctuates
- Regional allocation and aid trends visualized by year

  ![image](https://github.com/user-attachments/assets/56cf7291-7e78-42bf-892f-93ae2c34fecb)


### 5. **Project Category & Foreign Aid Impact**
- Development projects dominate both funding and foreign aid
- Security sector gets funding but minimal foreign aid
- Category-wise comparison of cost, aid, and utilization over time

![image](https://github.com/user-attachments/assets/924a92e3-7091-4498-b0ae-59012b79d64b)


---

## 🔑 Key Insights

- Projects in Gwadar show better utilization than those in wider Balochistan.
- Many projects have expenditures far exceeding their allocations.
- Ministries vary greatly in efficiency, with some severely under-utilizing funds.
- Foreign aid is heavily skewed towards development and social sectors.
- Budget allocation continues to rise, but expenditure lags in some years.
- A clear gap exists between policy intention and implementation, especially in underdeveloped regions.

---

## 💡 What Makes It Special?

- 🧠 Designed from scratch, using real raw data sources.
- 📐 Solved complex data relationships using bridge and dimension tables.
- 📊 Custom DAX measures for KPIs like Budget Coverage and Utilization %.
- 🔄 Year-wise and category-wise slicing using time intelligence.
- 🎯 Strong focus on regional equity and real-world implications.
- 🔍 Insight-driven visuals: every chart answers a specific policy question.

---

## 🧰 Tools Used

- **Power BI** (Data Modeling, DAX, Power Query)
- **Python** (Data cleaning and preprocessing)
- Government Planning & Development Data (2013–2022)

---

## 👥 Target Audience

- **Policymakers** looking to re-prioritize allocations based on utilization.
- **Researchers** interested in regional development and aid effectiveness.
- **Journalists** covering infrastructure and economic equity.
- **Civil Society & Citizens** tracking progress of publicly funded projects.

---

## 🤝 Contributions
| Name | Role |
|------|------|
| **Muhammad Talha Qureshi** | 📦 Data Collection, Contextual Research |
| **Ayema Amir** | 🧹 Data Cleaning, 🔧 Data Modeling, 🧠 DAX Calculations, 📊 Dashboard Design & Insights |

---
## 🛡 License

This work is licensed for academic demonstration only.  
🚫 **Reproduction or reuse without permission is prohibited.**

