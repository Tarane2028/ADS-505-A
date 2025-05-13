# Electric Vehicle Population Dashboard

This repository contains the Tableau dashboard and associated assets for the ADS 505 Assignment 7.1: **Electric Vehicle Population** analysis.

---

## Table of Contents

1. [Business Problem](#business-problem)
2. [Data Source](#data-source)
3. [Analytic Approach](#analytic-approach)
4. [Dashboard Overview](#dashboard-overview)
5. [Viewing the Dashboard](#viewing-the-dashboard)
6. [Repository Structure](#repository-structure)
7. [How to Reproduce](#how-to-reproduce)

---

## Business Problem

The objective of this dashboard is to understand the adoption and distribution of electric vehicles (EVs) across various regions. Key goals include:

* Identifying temporal trends in EV adoption.
* Highlighting the most popular vehicle makes and models.
* Examining geographic preferences and regional distribution.

These insights support infrastructure planning and help pinpoint market growth opportunities. citeturn0file0

## Data Source

Data was obtained from [Catalog.Data.gov](https://catalog.data.gov/) using the **Electric\_Vehicle\_Population** dataset. It includes:

* Vehicle make and model
* Year of manufacture
* Vehicle type
* Geographic location (city, state) citeturn0file0

## Analytic Approach

1. **Data Preparation**: Filter and clean records by year, make, model, and location.
2. **Calculated Fields**: Compute metrics such as total vehicles by year or city.
3. **Visualizations**: Create bar charts for popular makes/models and a map for geographic distribution.
4. **Interactivity**: Add filters, tooltips, and highlight actions for user exploration. citeturn0file0

## Dashboard Overview

Use the filters on the right side of the dashboard to select specific years, makes, or regions. Key views include:

* **Time Series**: Number of EVs by year.
* **Make & Model Rankings**: Top vehicle brands and models.
* **Geographic Map**: Distribution of EVs across cities.

![EV Dashboard Preview](assets/tableau/ev_dashboard.png)

## Viewing the Dashboard

* **Interactive**: Click the image above or visit the Tableau Public link below to explore the live dashboard.

  * [https://public.tableau.com/app/profile/tarane.javaherpour1002/viz/ADS505\_Tjavaherpour\_Electric\_Vehicle\_Population/Sheet1?publish=yes](https://public.tableau.com/app/profile/tarane.javaherpour1002/viz/ADS505_Tjavaherpour_Electric_Vehicle_Population/Sheet1?publish=yes)
* **Workbook**: The `.twbx` file is stored in `assets/tableau` if you wish to open it locally in Tableau Desktop.

## Repository Structure

```
ADS-505-A/
├── README.md                # Project overview and instructions
└── assets/
    └── tableau/
        ├── ADS505_Tjavaherpour_Electric_Vehicle_Population.twbx  # Tableau workbook
        └── ev_dashboard.png                                      # Static preview image
```

## How to Reproduce

1. Clone this repo:

   ```bash
   git clone https://github.com/Tarane2028/ADS-505-A.git
   ```
2. Open `assets/tableau/ADS505_Tjavaherpour_Electric_Vehicle_Population.twbx` in Tableau Desktop.
3. Use the filters within the dashboard for interactive exploration.

---

*Created by Tarane Javaherpour for ADS 505, University of San Diego.*
