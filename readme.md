# FEMA Applicants and Precipitation in Western North Carolina

This project maps FEMA Individual Assistance applicants and precipitation totals in Western North Carolina during Hurricane Helene (September 24–28, 2024). The goal is to show where people applied for help and how that relates to rainfall levels during the storm. ZIP Code Tabulation Areas (ZCTAs) are shaded based on average precipitation, and yellow circles represent the number of applicants per 1,000 people.

The map uses Leaflet for interactivity, with additional libraries like Leaflet AJAX for loading GeoJSON and Chroma.js for color scales. Custom legends, popups, and a short description are included to help explain the data.

Data Sources:
- PRISM Climate Data: https://prism.oregonstate.edu/
- FEMA IHP Valid Registrations: https://www.fema.gov/openfema-data-page/individuals-and-households-program-valid-registrations-v1
