# Deloitte Data Analytics Virtual Job Simulation (Forage)

## Overview

This repository contains my completed Deloitte Data Analytics Virtual Job Simulation on Forage.

The simulation focuses on solving real-world business problems using Tableau and Microsoft Excel.

---

## Task 1 – Data Analysis

### Objective

Analyze telemetry data collected from multiple factories and identify downtime patterns.

### Work Completed

- Imported JSON telemetry data into Tableau
- Created calculated field:
  - Unhealthy
- Built an interactive dashboard
- Visualized:
  - Down Time per Factory
  - Down Time per Device Type
- Applied dashboard filters

### Tools

- Tableau Public/Desktop

---

## Task 2 – Forensic Technology

### Objective

Investigate employee gender pay equality using Equality Scores.

### Work Completed

- Used Microsoft Excel
- Created Equality Class column
- Applied logical classification using Excel IF function

Classification Rules

- Fair (-10 to +10)
- Unfair (-20 to -11 and 11 to 20)
- Highly Discriminative (< -20 or > 20)

Formula Used

```excel
=IF(ABS(C2)<=10,"Fair",IF(ABS(C2)>20,"Highly Discriminative","Unfair"))
```

---

## Skills Demonstrated

- Data Analytics
- Data Cleaning
- Data Visualization
- Dashboard Development
- Tableau
- Microsoft Excel
- Calculated Fields
- Excel IF Function
- Business Analysis
- Forensic Data Analysis

---

## Repository Structure

```

Tableau/
Excel/
Certificate/
Screenshots/

```

---

## Certificate

Completed Deloitte Data Analytics Virtual Job Simulation on Forage.

---

## Author

Nasrin Khatoon

Aspiring Data Analyst
