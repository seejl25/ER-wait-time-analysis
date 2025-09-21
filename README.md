# ER-wait-time-analysis

## 🏥 Emergency Room Wait Time Analysis
### 📌 Project Overview

This project analyzes Emergency Room (ER) wait times across hospitals, with the goal of finding ways to reduce waiting times while ensuring quality of care.

Using Tableau, I built an interactive dashboard to explore how wait times vary by hospital characteristics, staffing levels, urgency levels, time of visit, and patient demographics. A presentation was later created in Canva to summarize insights and recommendations.

### 🎯 Key Objectives

1. Measure average ER wait times and patient satisfaction across hospitals

2. Identify bottlenecks (days, seasons, or times with the longest delays)

3. Explore hospital-level factors (facility size, nurse-to-patient ratio, specialist availability)

4. Provide actionable recommendations to improve efficiency without compromising care quality

### 📂 Dataset

Source: [ER Wait Time Dataset](https://www.kaggle.com/datasets/rivalytics/er-wait-time/data) (Kaggle)

### Key Features Used:

- Hospital Data: Hospital Name, Region, Facility Size (beds)

- Visit Data: Day of Week, Season, Time of Day

- Operational Metrics: Urgency Level, Nurse-to-Patient Ratio

- Performance Metrics: Total Wait Time

- Outcomes: Patient Satisfaction

### 🔄 Workflow
#### 1. Data Exploration (Tableau)

The dashboard was divided into multiple components for clear storytelling:

KPI Cards

- Average Total Wait Time

- Average Patient Satisfaction

Hospital-Level Analysis

- Pie chart of facility size (beds) by hospital

- Bar chart of patient volume per hospital

Wait Time Analysis (Box Plots)

- By Day of Week → identify busiest days

- By Region (Urban vs Rural) → compare accessibility

- By Season → check seasonal trends 

- By Time of Day → early morning, late morning, afternoon, evening, night

- By Urgency Level → low, medium, high, critical cases

- Staffing Impact

- Distribution of wait times by Nurse-to-Patient Ratio (1:1 to 1:5)

#### 2. Visualization (Dashboard Features)

- Box plots used to highlight variability and outliers in wait times

- Distribution charts to explore nurse-to-patient staffing effects

#### 3. Presentation (Canva)

- A presentation slide deck summarized insights and recommendations for decision-makers. Each chart was paired with key findings and improvement suggestions.

### 📈 Key Insights

- Some hospitals have smaller facility sizes (more beds) which would worsen wait times

- Certain days of the week and seasons (e.g. Mondays, Winter season) showed significantly longer wait times

- Nighttime and early morning shifts had longer delays, possibly due to limited staffing

- A lower nurse-to-patient ratio (1:1 or 1:2) was strongly associated with shorter wait times and higher patient satisfaction

### 💡 Recommendations

- Increase staffing (especially nurses and specialists) during high-demand periods (certain weekdays, summer and winter season, evenings)

- Expand facilities in hospitals to accommodate patient loads

- Adopt flexible nurse-to-patient ratio policies to ensure quality care 

- Use real-time monitoring dashboards to dynamically allocate resources when patient inflow spikes

### 📂 Deliverables

- er_wait_time.twbx → Tableau interactive dashboard

- er_wait_presentation.pdf → Canva presentation slides (exported)

- README.md → Project documentation (this file)
