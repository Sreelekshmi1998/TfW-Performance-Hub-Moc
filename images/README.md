# README.md - Images Folder

This folder contains all the figures used in the TfW Performance Hub Power BI mock dashboard, with **fictional/anonymised data**.

> **Note:** The examples below use the **Drivers** tab for demonstration purposes.

## Figures

- **Fig 0: overview.png**  
  General overview of the dashboard layout and available pages.

- **Fig 1: KPI.png**  
  KPI Overview page showing TINS, MINS, CAPES across periods with performance vs targets.  
  - KPI Overview cards summarise major KPIs.  
  - TINS, MINS, CAPES bar chart shows performance vs targets (green = target met, red = target not met).  
  - Primary Delay Minutes pie chart shows distribution by duration (0-3 mins, 4-5 mins, etc.) with top causes in tooltips.  
  - Area charts compare current period with same period last year.

- **Fig 1.1: Beyond Last 14 periods.png**  
  Historical trends beyond the last 14 periods for MINS, TINS, CAPES.  
  - Includes buttons for each subfunction under Drivers, allowing users to see actual vs target per subfunction.

- **Fig 1.2: tooltip_mins.png**  
  Example of tooltips showing major incident causes per period.

- **Fig 2: Current Period.png**  
  Current period performance page including KPI cards, daily trends, and incident location map.  
  - Daily target calculated as Period Target ÷ 28.  
  - Tooltip shows major incident causes per day.  
  - Bottom section shows TINS, MINS, CAPES across subfunctions.  
  - Incident location map with bubble size indicating number of TINS.

- **Fig 3: Incident Analysis.png**  
  Root cause table with drill-through options, TINS by Line of Route, and incident location map.    
  - Drill-through to detailed incident table with Incident No, Date, Delay minutes, Cancellations, Location, Memo.  
  - Major Incident Locations map; bubble size = number of TINS.

- **Fig 3.1: Drillthrough Root cause.png**  
  Detailed incident information after clicking a root cause.

- **Fig 3.1.1: Inc Val drillthrough.png**  
  Incident-level drill-through showing delay details per incident.

- **Fig 4: Dept Analysis.png**  
  Department-level analysis of major root causes, headcodes, and payees with highest TINS.  
  - Filters: Subfunction, Bugle Manager Title.  
  - Drill-through to payee-level details to monitor recurring issues.  
  - Maps and bar charts show major incident locations and patterns.

- **Fig 5: Null Report.png**  
  Matrix and KPI cards highlighting NULL reports and overdue delay investigations.  
  - Shows 7-day attribution window.  
  - KPI cards show Overdue, 1 Day Left, 2+ Days Left.  
  - Bar charts visualize incidents by area and frequency by days left.  
  - Detailed info button shows TRUST code, memo, date, and current status.

## Notes

- All figures are **mock visuals** for demonstration purposes.  
- Data protection: No real data is included; all values are anonymised.  
- Use these figures as reference for understanding the dashboard layout and analysis flow.

