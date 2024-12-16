<img src="https://github.com/canikhil12/HealthCare/blob/main/Screenshot%202024-12-15%20204751.png"/>

# Power BI Summary Dashboard

## Overview
This Power BI dashboard provides a summary of waitlist data across different case types and time bands. It offers valuable insights into the number of cases, their distribution over time, and key performance indicators such as average or median waitlists.

![Power BI Dashboard](image_path_here)

---

## Key Features

### 1. **Summary Metrics**
- **679K**: Latest Month Wait List
- **620K**: Previous Year (PY) Latest Month Wait List

These figures give an immediate overview of the overall waitlist changes.

---

### 2. **Case Type Distribution**
A donut chart visualizes the proportion of case types:
- **Outpatient**: 72.32% (80 cases)
- **Day Case**: 17.01% (19 cases)
- **Inpatient**: 10.67% (12 cases)

The total cases: **54 Overall**.

---

### 3. **Avg/Med Wait List by Time Bands and Age Profiles**
A bar chart breaks down the waitlists by:
- **Time Bands**: 0-3 months, 3-6 months, etc., up to 18+ months.
- **Age Profiles**:
   - 0-15 (Blue)
   - 16-64 (Orange)
   - 65+ (Pink)

The chart shows a significantly higher waitlist in the **18+ months** time band compared to other periods.

---

### 4. **Specialty-Specific Insights**
A list of specialties and their respective average or median waitlists:
- **Paediatric Dermatology**: 164 cases
- **Paediatric ENT**: 155 cases
- **Paediatric Orthopaedic**: 113 cases
- **Accident & Emergency**: 111 cases
- **Paediatric Cardiology**: 105 cases

---

### 5. **Trends Over Time**
Two line charts display trends for different case types:
1. **Day Case and Inpatient**:
   - Trends remain relatively stable over the time range (Jan 2018 to Jan 2021), with Day Cases consistently higher.
2. **Outpatient**:
   - Steady growth over the same period, peaking after Jan 2020 with significant increases.

---

## Filters and Controls
- **Case_Type Filter**: Allows filtering the visuals by case type (e.g., Outpatient, Day Case, Inpatient, or All).
- **Specialty_N Filter**: Allows filtering by specialty names.
- **Archive_Date Slider**: Adjust the date range to view historical or recent trends.
- **Average/Median Toggle**: Switch between average and median waitlist values.

---

## Data Sources
The dashboard uses archived waitlist data, grouped by:
- Case Types
- Age Profiles
- Time Bands
- Specialty Names

---

## Usage
1. Use filters to focus on specific **case types** or **specialties**.
2. Toggle between **Average** and **Median** metrics for comparative insights.
3. Analyze trends in the line charts to identify growth or declines in waitlists over time.
4. Study bar charts to pinpoint areas with high wait times and identify which age groups are most impacted.

---

## Insights
- **Waitlist Growth**: Overall waitlists have increased from the previous year (620K) to the latest month (679K).
- **18+ Months Impact**: Most waitlists fall into the 18+ months time band, especially for older age profiles.
- **Outpatient Cases**: Outpatients dominate the case type distribution (72.32%).

---

## Future Improvements
- Add drill-through functionality for deeper insights into each specialty.
- Include predictive analytics to forecast waitlist trends.
- Integrate additional filters for regional analysis.

---

## Dashboard Usage Example
1. View the summary statistics to understand high-level waitlist trends.
2. Use the line charts to see how cases change over time.
3. Analyze specific specialties, like **Paediatric Dermatology**, to identify opportunities for improvement.

---

## Contact
For questions or improvements regarding this dashboard, please reach out to the developer or data analytics team.

