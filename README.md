# Project Title: Spatial Inequality in Healthcare Accessibility in Leeds
## Project Overview

This project investigates the spatial relationship between deprivation levels, health environment accessibility, and the distribution of healthcare facilities across Leeds, UK. The analysis aims to explore how access to health-promoting environments and healthcare services varies across areas with different levels of deprivation. This insight supports public health planners and policymakers in identifying underserved communities and improving resource allocation to promote health equity.
## Data Sources

1. **imd_2019.csv: Index of Multiple Deprivation (IMD) 2019**  
   - Source: Source: UK Government. English indices of deprivation 2019.
[Available at: https://www.gov.uk/government/statistics/english-indices-of-deprivation-2019]
   - Date Accessed: 2025-05-11  
   - Description: Area-level deprivation scores at the 2011 LSOA level, higher scores indicate greater deprivation.

2. **ahah_v3.csv: Access to Healthy Assets & Hazards (AHAH) v3**  
   - Source: Consumer Data Research Centre (CDRC). Access to Healthy Assets & Hazards (AHAH) (Previous Versions).
[Available at: https://data.cdrc.ac.uk/dataset/access-healthy-assets-hazards-ahah-previous-versions]  
   - Date Accessed: 2025-05-11  
   - Description: Scores representing accessibility to health-promoting environments, including GPs, hospitals, pharmacies, dentists, leisure services.

3. **leeds_health_facilities.geojson: Healthcare Facilities Locations**  
   - Source: Open Street Map. [Available at:https://www.openstreetmap.org/#map=19/53.810222/-1.516950)] 
   - Date Accessed: 2025-05-11  
   - Description: Geographic locations of hospitals, general practitioners (GPs), dentists, and pharmacies.

4. **Leeds_LSOA.geojson: Leeds Boundary Shapefile (2011 LSOA Geography)**  
   - Source: Office for National Statistics (ONS). Lower layer Super Output Areas (December 2011) Boundaries EW BGC (V3).
[Available at: https://geoportal.statistics.gov.uk/datasets/02e8d336d6804fbeabe6c972e5a27b16_0/explore?location=52.723753%2C-2.489527%2C6.70] 
   - Date Accessed: 2025-05-11  
   - Description: Administrative boundary data for Leeds, aligned with the 2011 LSOA geography used in other datasets.
# Project Outcomes
1. Non-Spatial Visualization:
   A scatter plot showing the relationship between deprivation scores and health environment accessibility, providing insight into spatial inequalities in access to health-promoting environments.

2. Spatial Visualization:
   A choropleth map illustrating the distribution of deprivation levels and healthcare facility locations across Leeds, helping identify areas with both high deprivation and varying levels of healthcare service accessibility.
# Key Findings
Some highly deprived areas demonstrate surprisingly good accessibility to health-promoting environments, likely due to their proximity to city centers and public amenities.

However, higher physical accessibility does not necessarily translate into improved health outcomes, emphasizing the need for further research on actual service utilization and social barriers.
