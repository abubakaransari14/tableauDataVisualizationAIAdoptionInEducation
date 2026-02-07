# AI Adoption in College Students (India, 2025)

## 📌 Project Overview
This project explores **Artificial Intelligence (AI) tool adoption among Indian college students** and analyses its perceived impact on academic performance, usage behaviour, and digital access. Using interactive dashboards built in **Tableau**, supported by **Excel-based data preparation**, the project demonstrates how data visualisation and storytelling can be used to communicate complex educational trends effectively.

The analysis is based on a 2025 survey of Indian college students and was developed as part of an MSc Data Analytics module on **Visualization and Storytelling using Tableau**.

---

## 🎯 Objectives
- Analyse AI adoption across academic streams and regions
- Examine the perceived impact of AI usage on student grades
- Explore relationships between usage intensity and academic outcomes
- Identify preferred AI tools among students
- Investigate the role of internet access in AI adoption
- Demonstrate best practices in data preparation, visualisation, and dashboard design

---

## 📊 Dataset Description
**Dataset:** AI Tool Usage by Indian College Students (2025)  
**Source:** Survey conducted in May 2025  (Kaggle)
**Records:** 3,614 students  
**Attributes:** 16 variables

### Key Variables
- `Stream` – Academic discipline (Engineering, Arts, Science, etc.)
- `Year_of_Study` – Year 1 to Year 4
- `AI_Tools_Used` – AI tools used by students
- `Daily_Usage_Hours` – Average daily AI usage
- `Impact_on_Grades` – Self-reported grade impact (-3 to +3)
- `Trust_in_AI_Tools` – Trust level (1–5)
- `Preferred_AI_Tool` – Most preferred AI tool
- `State` – Indian state
- `Internet_Access` – Quality of internet access (High / Medium / Poor)

---

## 🧹 Data Preparation
Data preparation was carried out using **Microsoft Excel** and **Tableau**:

- Missing values in the `State` column were replaced with **“State Not Disclosed”**
- Categorical variables such as `Stream` and `State` were reviewed for naming consistency
- Numeric fields (`Trust_in_AI_Tools`, `Awareness_Level`, `Impact_on_Grades`) were validated to ensure they fell within expected survey ranges
- A cleaned dataset (`Students_Cleaned.xlsx`) was used consistently for both Excel and Tableau analysis

---

## 📈 Excel Analysis
Excel was used for preliminary aggregation and advanced analysis:
- Pivot tables were created to calculate average grade impact and trust levels by academic stream
- A **combo chart** was developed:
  - Bar chart: Average impact on grades
  - Line chart: Average trust in AI tools

This Excel analysis complements the Tableau dashboards and supports data validation.

---

## 📊 Tableau Visualisations
The Tableau dashboard includes the following visual components:

### Key Charts
- **AI Tool Usage by Stream** – Bar chart comparing adoption across disciplines
- **Impact on Grades** – Diverging bar chart showing negative, neutral, and positive impacts
- **Usage vs Impact** – Scatter plot analysing daily usage hours against grade impact
- **Preferred AI Tools** – Treemap highlighting dominant AI platforms
- **AI Usage by State** – Geographic map showing regional distribution
- **Internet Access & AI Usage** – Stacked bar chart illustrating the digital divide

### Calculated Fields
- **Positive Impact Flag**
- **High Trust Indicator**

---

## 🖥️ Dashboard Design
Two interactive dashboards were created:
1. **AI Adoption Overview** – Adoption patterns by stream, state, and preferred tools
2. **AI Impact & Access** – Relationship between usage intensity, grade impact, and internet access

Interactive filters allow users to explore the data dynamically by stream, state, and AI tool.

---

## ⚖️ Ethical and Social Considerations
While AI tools appear to positively support learning outcomes, the analysis highlights:
- Unequal access to reliable internet infrastructure
- Potential over-reliance on AI tools
- The need for clear academic integrity guidelines

These findings emphasise the importance of responsible and equitable AI adoption in higher education.

---

## 🛠️ Tools Used
- **Tableau** – Interactive dashboards and storytelling
- **Microsoft Excel** – Data cleaning, pivot analysis, and advanced charts



