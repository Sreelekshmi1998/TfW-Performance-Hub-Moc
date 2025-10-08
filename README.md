# 🚆 Transport for Wales - All‑Function Performance Hub (Power BI)

**Role:** Performance Reporting Analyst  
**Organisation:** Transport for Wales (TfW)  
**Period:** Nov 2024 - Present

> **Confidentiality Notice:** All screenshots in this repository have had all values erased. No operational, personal, or confidential data is included. Images are for demonstration purposes only.

---

## 📌 Overview
A centralised **Power BI** solution that integrates KPIs across multiple functions-Drivers, Conductors, Fleet, Train Planning, Resources, Control, and Station Operations. The hub enables leadership to track **TINS (incidents), MINS (delay minutes), CAPES (cancellations)**, investigate root causes, and compare performance against targets and prior periods.

---

## 🧭 Pages in the Report
1. **KPI Overview** - High‑level KPI cards, trend bars vs target, primary delay pie, year‑over‑year area charts.  
2. **Current Period** - Daily progression for MINS/CAPES, incident causes tooltips, incident location map.  
3. **Incident Analysis** - Root cause table with drill‑through to incident details; TINS by Line of Route; major locations.  
4. **Department Analysis** - Root causes by TINS, headcodes, top payees; drill‑through to payee detail for training focus.  
5. **NULL Report** - 7‑day attribution window monitoring; overdue/1‑day‑left/2+‑days‑left; matrix by manager.

See full Guidance Notes in [`docs/guidance_notes.md`](docs/guidance_notes.md).

---

## 📊 KPI Glossary
- **MINS** - Total delay minutes  
- **CAPES** - Total Cancellations (Full + 0.5 × Part)  
- **TINS** - Total number of incidents  
- **PRIM:REACT** - Ratio of primary to reactionary delay minutes  
- **MINS (Not Investigated %)** - % delay minutes not yet investigated  
- **CAPES (Not Investigated %)** - % cancellations not yet investigated  

---

## 🛠️ Tech & Methods
- **Power BI** (data modelling, DAX, drill‑through, bookmarks)  
- **SQL / CSV inputs** (extracts)  
- **Data Quality** (filter pane structure, slicers, cross‑page filters)  
- **Design** (accessible colour coding: 🟩 target met, 🟥 target not met)

---

## 📂 Repository Structure
```

├── README.md
├── images/
│   ├── overview.png
│   ├── KPI.png
│   ├── Beyond Last 14 periods.png
│   ├── tooltip_mins.png
│   ├── Current Period.png
│   ├── Incident Analysis.png
│   ├── Drillthrough Root cause.png
│   ├── Inc Val drillthrough.png
│   ├── Dept Analysis.png
│   ├── Null Report.png
│   └── README.md
│
├── docs/
│   └── guidance_notes.md


```

## 🙋‍♀️ Contact
**Sreelekshmi Sreekumar** · Performance Reporting Analyst  
LinkedIn: https://www.linkedin.com/in/sreelekshmi-sreekumar-8a171a21b/  
Email: sreelekshmisk98@gmail.com
