# Boston Police Incidents by Census Tract

## Overview
This project examines the geographic distribution of reported police incidents across Boston census tracts, normalized by residential population. The goal is to contextualize police activity relative to neighborhood size and socioeconomic conditions.

## Data
- Boston Police Department Incident Reports (2024)
- American Community Survey (ACS) 5-year estimates:
- Poverty rate by census tract
- Total population by census tract

## Methods
Police incident records were spatially joined to census tracts and aggregated to the tract level. Incident counts were normalized by tract population to calculate incidents per 1,000 residents.

Tracts with very small residential populations were excluded to reduce instability from small denominators. Extreme per-capita values were winsorized to limit the influence of outliers.

Analysis is descriptive and does not attempt to establish causal relationships.

## Results
Per-capita police incident rates vary substantially across Boston census tracts. Higher-poverty tracts tend to exhibit higher rates of police incidents per resident, though the relationship is not perfectly linear.

## Key Takeaway
Differences in police activity across neighborhoods are more apparent when accounting for population size. Per-capita normalization provides a clearer view of how police presence varies spatially across Boston and highlights the importance of neighborhood-level context in public safety analysis.
