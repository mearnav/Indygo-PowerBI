# IndyGo Ridership & On-Time Performance Analytics Dashboard

An interactive **Power BI analytics dashboard** developed to analyze IndyGo public transit operations using real operational data.  
The project focuses on transforming raw transportation data into actionable insights supporting **data-driven decision making, service transparency, and operational analysis**.

---

## Project Overview

Public transportation agencies generate large volumes of operational data, but extracting meaningful insights requires structured modeling and visualization.

This project analyzes **IndyGo transit performance (2022–2024)** at route and stop levels to understand:

- Ridership behavior
- Service coverage patterns
- On-time performance trends
- Geographic demand distribution
- Operational efficiency across routes

The dashboard enables stakeholders to explore system performance interactively instead of relying on static reports.

---

## Key Features

- Interactive Power BI dashboard with dynamic filtering
- Route-level and stop-level performance analysis
- Hourly ridership trend exploration
- Geospatial visualization of busiest stops
- Service coverage comparison across routes
- Cross-filtering and drill-down analytics

---

## Data Preparation & Transformation

Major data engineering steps included:

- Cleaning and validating multiple data tables
- Removing unnecessary columns and duplicates
- Handling missing and NULL values
- Standardizing numeric formats
- Validating **Route Key ↔ Coverage Group** alignment
- Creating derived attributes:
  - Depart Time Hour
  - Improved boarding metric using Departure Boards
  - Simplified route identifiers
- Filtering non-public operational routes (Deadhead/Special)

---

## Dashboard Pages

### Overview
High-level KPIs and system performance summary.

### Route Analysis
Compare operational performance across transit routes.

### Hourly Trends
Identify peak ridership periods using time-based aggregation.

### Geospatial Analysis
Interactive map highlighting busiest stops and demand clusters.

### Service Coverage
Evaluate coverage distribution and operational patterns.

---

## Tech Stack

- **Power BI Desktop**
- Data Modeling & DAX Measures
- Data Cleaning & Transformation
- Interactive Visualization Design

---

## Repository Structure
indygo-powerbi-dashboard/
│
├── dashboard/
│   └── IndyGo_Ridership_Dashboard.pbix
│
├── data/
│   └── DatasetStatistics.xlsx
│
├── docs/
│   ├── IndyGoReportFinal.pdf
│   ├── Project_Description.docx
│   └── Presentation.pptx
│
├── design/
│   └── Visualization Sketches
│
└── README.md

---

## How to Run

1. Clone repository
```bash
git clone https://github.com/YOURUSERNAME/indygo-powerbi-dashboard.git
```
2. Open the `.pbix` file using **Power BI Desktop**

3. If prompted, update local data source paths.

4. Refresh dataset.

---

## Screenshots

<img width="560" height="350" alt="image" src="https://github.com/user-attachments/assets/7f190f26-c163-4f15-9c52-7d4cc8503bf1" />

<img width="678" height="333" alt="image" src="https://github.com/user-attachments/assets/bf71a211-7235-44c7-80a1-f3c6b1f9ada3" />

<img width="468" height="263" alt="image" src="https://github.com/user-attachments/assets/d551d353-1484-4753-978f-6a4255cc419e" />

<img width="468" height="247" alt="image" src="https://github.com/user-attachments/assets/92893480-2082-4950-b69e-333583085e77" />



---

## Key Learnings

- Real-world data cleaning workflow
- Multi-table Power BI data modeling
- Stakeholder-focused dashboard design
- Translating transportation data into actionable insights

---

## License

Academic project created for Information Visualization coursework.  
Shared publicly for portfolio and learning purposes.
