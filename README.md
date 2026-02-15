# Post-Disaster Health Outcomes of Flood Control Infrastructure Spending

This research examines the efficacy of Philippine flood control investments by analyzing the correlation between regional public infrastructure spending and post-disaster health metrics—specifically mortality and morbidity rates—during tropical cyclone events from 2019 to 2025. By controlling for meteorological intensity (24-hour peak rainfall and maximum wind gusts), the study quantifies how infrastructure spending serves as a protective factor against environmental hazards.

## Research Rationale

Despite significant annual budget allocations for flood control infrastructure, regional disparities in post-disaster casualties persist. This project seeks to audit the "human return on investment" for infrastructure spending. By cross-referencing meteorological intensity with casualty counts, we aim to identify where spending is effectively saving lives and where there is a concerning disconnect between budget execution and public safety.

## Features

**Integrated Disaster-Financial Dataset:** Combines multi-year meteorological data (rainfall and wind speeds) with regional infrastructure project spending and NDRRMC health impact statistics.

**Station-to-Region Normalization:** Implements a robust mapping system that translates localized weather station data into standardized administrative regions for macro-level analysis.

**Statistical Data Imputation:** Utilizes advanced data cleaning techniques to maintain dataset integrity, ensuring that gaps in weather reporting during extreme events do not bias the final research outcomes.

**Automated Data Pipeline:** Features a modular Python-based pipeline for ingesting, cleaning, and consolidating heterogeneous data sources into a research-ready format.

**Trend & Correlation Analysis:** Provides a framework for analyzing the efficacy of public spending in reducing disaster-related casualties over a seven-year period.

## Dataset

The research utilizes these primary data sources to investigate the link between infrastructure and health:

1. **Tropical Cyclone Meteorological Data (2019–2025):** Meteorological data, including 24-hour peak rainfall and maximum sustained wind gusts, was extracted from official PAGASA preliminary and annual reports.

   Annual Reports (2019–2022): Comprehensive technical data for historical cyclones.
   Source: [PAGASA Official Portal - Annual Report on Philippine Tropical Cyclones ](https://bagong.pagasa.dost.gov.ph/tropical-cyclone/publications/annual-report)

   Preliminary Reports (2023–2025): Recent data for contemporary event analysis.
   Source: [PAGASA Official Portal - Tropical Cyclone Preliminary Report](https://bagong.pagasa.dost.gov.ph/tropical-cyclone/publications/preliminary-report)

2. **NDRRMC Situational Reports (2019–2025):** Official reports from the National Disaster Risk Reduction and Management Council used for contemporary death and injury counts.
   - **Source:** [NDRRMC Official Portal](https://ndrrmc.gov.ph/)
3. **Flood Control Infrastructure Projects (2018–2025):** Regional project data used as the primary independent variable.
   - **Source:** [Sumbong sa Pangulo](https://sumbongsapangulo.ph/)

## How to run

Clone the repository

```
git clone git@github.com:alecbnono/flood-control-health-outcomes.git
```

Execute the following commands to install the dependencies

```
python -m venv venv       # create their own virtualenv
source venv/bin/activate  # activate it (Linux/macOS)
venv\Scripts\activate     # activate it (Windows)
pip install -r requirements.txt
```
