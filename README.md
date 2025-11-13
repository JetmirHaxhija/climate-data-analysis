# Analysis of Heat Days and Tropical Nights (2019–2024)

This project analyzes the occurrence of heat days (Tmax ≥ 30 °C) and tropical nights (Tmin ≥ 20 °C) in Germany from 2019 to 2024 using publicly available data from the German Weather Service (DWD).  
It includes full data acquisition, preprocessing, analysis, and visualization.

## Project Structure

- `get_climate_data.ipynb`: Downloads, processes, and prepares the climate data from DWD.
- `Abbildungen_DS_Projekt.ipynb`: Performs data exploration and visualizes trends in heat days and tropical nights.
- `/images`: Contains exported plots and visual summaries for reporting.

## Methodology

- Data source: Open Data from DWD (Deutscher Wetterdienst)
- Criteria:
  - Heat day: Daily maximum temperature ≥ 30 °C
  - Tropical night: Daily minimum temperature ≥ 20 °C
- Steps:
  1. Download and filter weather station data for Germany
  2. Merge datasets and clean missing values
  3. Count and analyze the frequency of events per station and year
  4. Visualize regional and temporal trends

## Tools and Libraries

- Python (Pandas, NumPy)
- Matplotlib and Seaborn
- Jupyter Notebooks
- Requests (for downloading data)

## Visualizations

Visualizations include:
- Number of heat days per year
- Frequency of tropical nights by region
- Heatmaps for missing data

## Motivation

Due to increasing concern about local effects of climate change, this project aims to highlight how extreme heat events have developed in recent years, especially at the regional level.

## Projektbeschreibung (Deutsch)

In diesem Projekt werden Hitzetage (Tmax ≥ 30 °C) und Tropennächte (Tmin ≥ 20 °C) in Deutschland im Zeitraum 2019–2024 analysiert.  
Datenquelle ist der Deutsche Wetterdienst (DWD), öffentlich zugänglich über dessen Open Data Server.

### Vorgehen

- Herunterladen und Vorverarbeiten von Klimadaten
- Zusammenführen mehrerer Datensätze
- Identifikation und Zählung relevanter Extremereignisse
- Visualisierung der Entwicklung über die Jahre und Regionen

## Lizenz

This project is published under the MIT License.
