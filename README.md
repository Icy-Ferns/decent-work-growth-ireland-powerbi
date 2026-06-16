# SDG 8 Dashboard (Power BI Dashboard)
**Power BI Dashboard | SDG 8 Analysis | ETL + Data Modeling + Insights Storytelling**

An interactive Power BI dashboard analyzing SDG 8 indicators for India, New Zealand, and Ireland from 2000 to 2020 using World Bank data. The project uses ETL to transform country-level indicator files into a comparison-ready model that reveals trends in GDP growth, unemployment, youth labor conditions, and sectoral employment.. This dashboard was built to compare long-term labor market and economic growth patterns, highlight cross-country differences, and turn raw indicator data into clear business-friendly insights through an ETL workflow and interactive reporting.

## Project overview
The project focuses on how three countries performed against selected SDG 8 themes over two decades, with Ireland used as a key benchmark against India and New Zealand in the report narrative. The dashboard combines employment structure, GDP growth, unemployment, and youth labor indicators to show how economic growth and workforce conditions evolved over time.

## Business problem

Economic growth alone does not fully explain whether a country is progressing on decent work. A country may grow quickly while still facing high youth unemployment, labor market imbalance, or uneven sectoral employment.
This project addresses that gap by comparing multiple SDG 8 indicators together so viewers can assess growth quality, labor market resilience, and structural differences between developing and developed economies.

## Objectives

- Compare India, New Zealand, and Ireland across selected SDG 8 indicators from 2000 to 2020.
- Build an interactive Power BI dashboard that supports country-vs-country historical analysis.
- Use ETL to clean, reshape, and model country-level World Bank data into dashboard-ready tables.
- Present insights on GDP growth, youth unemployment, unemployment averages, and employment by sector.

## ETL process

### 1. Extract
- Imported three country CSV files for India, Ireland, and New Zealand from the World Bank WDI source.
- Selected indicators relevant to SDG 8, including GDP growth, unemployment, youth unemployment, employment by sector, and related labor-force measures.

### 2. Transform
- Cleaned wide-format indicator data and reshaped year columns into an analysis-friendly structure for time-series reporting.
- Standardized country names, indicator labels, and year fields so the measures could be compared consistently across countries.
- Filtered the dataset to the 2000–2020 period used in the dashboard story.

### 3. Load
- Loaded the transformed tables into Power BI.
- Built visuals, slicers, KPI cards, and comparison pages to help users move from raw data to insight quickly.

## Key insights

### 1. Ireland and New Zealand show lower average unemployment than India
The dashboard visuals indicate that New Zealand records the lowest average unemployment among the compared countries, while India remains higher on average than both developed peers.

This makes the comparison useful for showing how labor-market maturity and economic structure can affect SDG 8 outcomes beyond headline growth.

### 2. India shows stronger growth swings but not always stronger labor outcomes
The GDP growth trend comparison suggests India often posts relatively strong annual growth, but that does not automatically translate into better unemployment performance.

That contrast is important because it shows the difference between growth quantity and inclusive employment quality, which is central to SDG 8.

### 3. Ireland experienced clear labor market stress around the global crisis period
The Ireland comparison visuals show youth unemployment rising sharply around the late-2000s to early-2010s period before easing later, signaling a period of labor-market disruption and recovery.

This gives the dashboard a historical storytelling angle rather than just a static KPI view.

### 4. Service sectors dominate employment in Ireland and New Zealand
The employment-by-sector visuals show service-sector employment taking the largest share in Ireland and New Zealand, while India displays a more mixed profile with stronger agriculture representation.

This helps explain structural differences in productivity, labor transitions, and economic maturity across the three countries.

### 5. SDG 8 performance should be viewed as a balance of growth and workforce inclusion
Across the dashboard, the strongest message is that GDP growth, unemployment, and sectoral employment need to be read together to understand decent work and economic growth properly.

## Portfolio value

This project demonstrates practical data analytics skills across the full BI workflow: data sourcing, ETL, data modeling, dashboard design, and insight communication. It is especially useful as a portfolio project because it combines public policy context, cross-country benchmarking, time-series analysis, and business intelligence storytelling in one deliverable.
## What’s included
- WDI country extracts (CSV):
  - `API_IRL_DS2_en_csv_v2_1810.csv` (Ireland) [file:2]
  - `API_IND_DS2_en_csv_v2_134.csv` (India) [file:1]
  - `API_NZL_DS2_en_csv_v2_20206.csv` (New Zealand) [file:3]
- Power BI dashboard (PBIX).

## Data source
World Bank — *World Development Indicators (WDI)*: https://data.worldbank.org/ [web:54]

## Snapshots of Dashboard.

![IrelandVsIndia](images/SDG8%20-%20Ireland%20vs%20India%20vs%20New%20zealand_page-0001.jpg)

![IrelandVSNew zealand](images/SDG8%20-%20Ireland%20vs%20India%20vs%20New%20zealand_page-0002.jpg)

![IrelandVSnz](images/SDG8%20-%20Ireland%20vs%20India%20vs%20New%20zealand_page-0003.jpg)

![Description](images/SDG8%20-%20Ireland%20vs%20India%20vs%20New%20zealand_page-0004.jpg)
