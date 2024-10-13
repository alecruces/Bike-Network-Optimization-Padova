# Data Driven Prediction of Missing Links in Padova's Bike Lane Network

This project is part of my Master’s thesis for Data Science.

## Abstract
Cycling infrastructure is crucial for urban mobility, yet many cities struggle to meet the increasing demand for well-connected bike paths. This research focuses on Padova, Italy, proposing a data-driven method to identify and prioritize new bike routes. By integrating data from the RideMovi bike-sharing system and modifying traditional centrality measures, a novel weighted benefit metric is introduced. Grounded in stress centrality, this metric considers both cyclist demand and the strategic importance of network components to prioritize infrastructure improvements effectively.

The analysis reveals that central areas of Padova, especially around the train station and city center, require substantial upgrades. Key routes connecting the university and hospital are prioritized, while peripheral areas are considered lower priority. This study provides actionable recommendations for enhancing bike network connectivity in high-demand zones. The Component approach identifies broad infrastructure gaps, while the Routing approach offers a more efficient solution by adding fewer kilometers of new paths, better aligning with actual cyclist demand.

<p align="center">
<img src="link-to-your-map-image.png" alt="Bike Network Map" style="width:400px;height:auto;"/>
</p>

## Keywords
Bike infrastructure, urban mobility, centrality measures, data-driven analysis

## Data
* RideMovi bike-sharing dataset: Provides real-world bike trip data for analysis.
* OpenStreetMap: Geographic data for bike path mapping.

## Key Findings
- **Central Areas Needing Upgrades:** The analysis reveals that central areas of Padova, particularly around the train station and city center, require substantial upgrades.
- **Prioritized Routes:** Key routes connecting the university and hospital are highlighted, while peripheral areas are deemed lower priority.
- **Methodology Comparison:** The Component approach identifies broad infrastructure gaps, while the Routing approach offers a more efficient solution by adding fewer kilometers of new paths, better aligning with actual cyclist demand.

## Methods
* Data-driven approaches: Utilizing metrics such as weighted benefit metric and edge stress centrality to assess bike infrastructure.
* Component and Routing approaches: Identifying components in the bike network and optimizing routes for improved connectivity.
* Flow analysis: Assessing bike traffic demands to inform infrastructure improvements.

## Software
* Python
* NetworkX
* Geopandas
* Matplotlib
