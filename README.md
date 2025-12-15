# The Economic Impact of Open Data Policy: An Empirical Analysis Using State-Level Panel Data

## Overview
This repository contains the replication code and data for the final project analyzing the causal effect of Open Data Portals on State Real GDP (2010–2022) using a Difference-in-Differences (DiD) framework with Two-Way Fixed Effects.

## Repository Contents

### Main Code
*   `2512014_finalproject_Takehisa.qmd`
*   `STATS_506_finalproject.Rproj`

### Data Files (Must be in the root folder)

**1. Policy & Economic Data (BEA)**
*   `state_open_data.csv`: Policy intervention dates.
*   `SAGDP1__ALL_AREAS_1997_2024.csv`: State GDP data.
*   `SAGDP2__ALL_AREAS_1997_2024.csv`: Industry GDP share data.
*   `Section1All_xls.xlsx`: Fixed Assets data.

**2. Labor Force Data (Census ACS)**
*   `ACSDT1Y2010.B01003-Data.csv`
*   `ACSDT1Y2011.B01003-Data.csv`
*   `ACSDT1Y2012.B01003-Data.csv`
*   `ACSDT1Y2013.B01003-Data.csv`
*   `ACSDT1Y2014.B01003-Data.csv`
*   `ACSDT1Y2015.B01003-Data.csv`
*   `ACSDT1Y2016.B01003-Data.csv`
*   `ACSDT1Y2017.B01003-Data.csv`
*   `ACSDT1Y2018.B01003-Data.csv`
*   `ACSDT1Y2019.B01003-Data.csv`
*   `ACSDT1Y2021.B01003-Data.csv`
*   `ACSDT1Y2022.B01003-Data.csv`
*(Note: 2020 data is excluded due to pandemic-related data quality issues.)*

**3. Capital Expenditure Data (Census ACES for PIM)**
*   `table4b_2010.xlsx`
*   `table4b_2011.xlsx`
*   `table4b_2012.xlsx`
*   `table4b_2013.xlsx`
*   `table4b_2014.xlsx`
*   `table4b_2015.xlsx`
*   `table4b_2016.xlsx`
*   `table4b_2017.xlsx`
*   `table4b_2018.xlsx`
*   `table4b_2019.xlsx`
*   `table4b_2020.xlsx`
*   `table4b_2021.xlsx`
*   `table4a_2022.xlsx`

### R Packages Used
*   **pacman**
*   **tidyverse**
*   **readxl**
*   **fixest**
*   **modelsummary**
*   **kableExtra**
*   **stringr**
*   **lubridate**
*   **scales**
*   **patchwork**
*   **zoo**
*   **TinyTeX**
