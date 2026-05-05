# New York Minute: Evaluating Emergency Response Across Boroughs

📌 **Purpose of the Project**

This project analyzes NYC emergency response and 911 calls for service data to evaluate public safety and emergency service efficiency across the five boroughs. The main objectives are:

* To identify which borough reports the highest number of incidents.
* To compare average emergency response times across all five boroughs.
* To examine the correlation between incident frequency and response times.

---

🔍 **Analysis Performed**

1. Data Cleaning & Preparation (40.7M rows filtered to 2023)
2. Exploratory Data Analysis (EDA) by Borough
3. Incident Frequency Analysis (unnormalized and normalized by population)
4. Emergency Response Time Analysis
5. Geospatial Mapping of 911 Calls by Location
6. Correlation Analysis between Incidents and Response Times

---

📌 **Results**

* Manhattan has the highest number of incidents reported overall.
* After normalizing by population, Manhattan has the highest incident rate per capita.
* The average emergency response time is approximately 40 minutes, consistent across all five boroughs.
* Brooklyn has the most 911 calls and the highest daytime incident rate.
* Incidents and 911 calls are partially correlated in Manhattan and Brooklyn.
* The majority of calls across all boroughs are NON-CIP related, meaning incidents were reported after they occurred.

---

📌 **Data Sources**

* Emergency Response Incidents via NYC Open Data:
https://data.cityofnewyork.us/Public-Safety/Emergency-Response-Incidents/pasr-j7fb/about_data

* NYPD Calls for Service (911) via NYC Open Data:
https://data.cityofnewyork.us/Public-Safety/NYPD-Calls-for-Service-Year-to-Date-/n2zq-pubd/about_data

---

📌 **Technologies Used**

* R (ggplot2, dplyr, tidyverse)
* Geospatial Mapping (Leaflet)
* Git & GitHub
