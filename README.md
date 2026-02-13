# Post-Disaster Health Outcomes of Flood Control Infrastructure Spending

## Features

## Dataset

This repository utilizes a multi-sourced approach to bridge the historical data gap and capture real-time trends:

    Tropical Cyclone Impact Data (2010–2020): A validated, province-level impact dataset curated for disaster risk reduction (DRR) applications. It provides the baseline for mortality, affected population, and housing damage.

        Source: Figshare - Tropical Cyclone Impact Data

    NDRRMC Situational Reports (2020–2025): Used for contemporary casualty counts, specifically to retrieve both death and injury statistics for the most recent typhoon seasons.

        Source: National Disaster Risk Reduction and Management Council (NDRRMC)

    Flood Control Infrastructure Data (2022–2024): Publicly available data on regional flood control projects, used as the primary independent variable.

        Source: Sumbong sa Pangulo

## How to run

Clone the repository

```
git@github.com:alecbnono/flood-control-health-outcomes.git
```

Execute the following commands to install the dependencies

```
python -m venv venv       # create their own virtualenv
source venv/bin/activate  # activate it (Linux/macOS)
venv\Scripts\activate     # activate it (Windows)
pip install -r requirements.txt
```
