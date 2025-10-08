# 📘 Guidance Notes - TfW Performance Hub (Power BI)

This document describes how each page of the dashboard is used, matching the live report structure while using **fictional/anonymised** visuals.

---

## 🔹 Glossary
- **MINS** - Total delay minutes  
- **CAPES** - Total Cancellations (Full Cancellations + 0.5 × Part Cancellations)  
- **TINS** - Total number of incidents  
- **PRIM:REACT** - Ratio of primary delay minutes to reactionary delay minutes  
- **MINS (Not Investigated %)** - Percentage of delay minutes left uninvestigated  
- **CAPES (Not Investigated %)** - Percentage of cancellations left uninvestigated  

---

## 🧭 Navigation & Controls
**Global Filter Pane (top/side):**
- Subfunction (for each function)
- Period, Date, Weekdays

Actions:  
- Click **Filter** icon to open the filter panel; **X** to close.

**PAST Trend Button:**  
- Access historical trends for **MINS, TINS, CAPES** beyond the last 14 periods.

---

## 📈 KPI Page (KPI Overview)
**KPI Overview cards** - summary of major KPIs listed in the glossary.  

**TINS, MINS, CAPES bar chart** - performance vs targets across periods.  
- 🟩 Green = Target met  
- 🟥 Red = Target not met  
- Target line: customised per subfunction (except FLEET)  
- Tooltip: major reasons for TINS, MINS, CANCS per period

**Primary Delay Minutes pie chart** - distribution by duration:  
- 0-3 mins, 4-5 mins, 6-10 mins, etc.  
- Hover: top causes within each duration (e.g., Defensive Driving prominent in 0-3 mins)

**Area charts** - compare current period with same period last year.

---

## 📘 Current Period Page
**KPI Overview (left)** - key KPIs for the current period.  

**Daily performance trends for MINS and CAPES** - target calculated as:  
> **Daily Target = Period Target ÷ 28**  

**Tooltip** - hover to view major incident causes per day (bar).  

**Bottom section** - TINS, MINS, CAPES across subfunctions.  

**Incident Location Map** - bubble size indicates number of TINS.

---

## 📘 Incident Analysis Page
**Root Cause Table** (sortable; default by MINS):  
- Root Cause, MINS, Primary/Reactionary Mins, CAPES, Full/Part Cancels, TINS  

**Drill‑through:**  
- Click a root cause → *“Click here to get detailed info on incidents”* → detailed incident table:  
  - Incident No, Date, Total/Primary/Reactionary Mins, Cancellations (full/part), Location, Memo  
  - Click Incident No → page showing impact by delay location

**TINS by Line of Route (LOR)** - filterable by selected root causes.  
**Major Incident Locations (Map)** - bubble size = number of TINS.

---

## 📘 Department Analysis Page
**Filters** - Subfunction; **Bugle Manager Title** (e.g., Drivers South → Valley Drivers, etc.).  

**Major Root Causes by TINS** (bar chart):  
- Drill‑through: *“Click to get detailed info about payee”* → Payee Name, Train Description, Date, Memo  
- Page filterable by Payee Name  
- Use to monitor patterns (e.g., recurring Cab Setup Issues) for targeted training

**Headcode by TINS** (bar)  
**Payees with Highest TINS** (bar; hover reveals major associated root causes)  
**Major Incident Locations** (map; bubble size = number of TINS)

---

## 📘 NULL Report Page
**Purpose** - Identify functions with **NULL reports** in the last 7 days and enforce investigations within the attribution window.

**7-day Attribution Window** - Delay Attribution Team must annotate a root cause within 7 days.

**Visuals**  
- **Matrix** - Rows: Bugle Manager Title; Columns: days left to attribute  
- **KPI Cards** - Overdue, 1 Day Left, 2+ Days Left  
- **Incidents by Area & Days Left** (bar)  
- **Frequency of Incidents by Days Left** (bar)  
- **Detailed Info Button** - TRUST code, Memo, date, current status, etc.

---

## 🔒 Data Protection
Confidentiality Notice: All screenshots in this repository contain no real data. All values have been completely erased - only the figure structures are shown for demonstration purposes.

