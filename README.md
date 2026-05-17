# **Energy system analytics — France 2022**



A data analytics project exploring the French electricity grid using Python, SQL, and Power BI. Built from real RTE (Réseau de Transport d'Électricité) half-hourly data for the year 2022.



## **Project Overview**



This project analyzes the performance of the French electricity system across four dimensions: data handling, SQL analytics, performance indicators, and digital twin logic. It moves from raw data to actionable insights, identifying structural vulnerabilities in a nuclear-dependent grid.



1. **Notebooks:** 



|**Number**|**Notebook**|**Focus**|**Tools**|
|-|-|-|-|
|1|01\_context\_and\_system.ipynb|System perimeter, components, inputs/outputs, constraints|Markdown|
|2|02\_python\_data\_handling.ipynb|Data loading, cleaning, variable creation, visualization|Python, Pandas, Matplotlib|
|3|03\_sql\_energy\_analysis.ipynb|Temporal patterns, peak analysis, energy mix, exchanges|SQL (SQLite), Seaborn, Plotly|
|4|04\_performance\_indicators.ipynb|KPI interpretation, critical analysis, takeaways|Markdown (Power BI companion)|
|5|05\_digital\_twin\_logic.ipynb|System states, evolution rules, scenarios, assumptions|Markdown|



2\. **Dashboard:**



An interactive Power BI dashboard (05\_performance\_dashboard.pbix) tracks 7 KPIs:



* System reliability: Self-Sufficiency rate, Peak-to-Average ratio
* Energy transition: Nuclear availability, Renewable share, Import dependence
* Operational quality: CO₂ emission intensity, Forecast accuracy
* Includes interactive slicers by season, month, and hour.



**3. Key Findings:**



* France was a net importer of electricity in 2022, driven by nuclear outages (corrosion issues at Civaux 1, delayed Covid maintenance).
* Nuclear availability dropped below 50% during certain periods, causing simultaneous degradation of self-sufficiency, CO₂ intensity, and import dependence.
* Renewable share remains roughly 24%, intermittent sources complement but cannot replace nuclear baseload yet.
* Peak-to-average ratio of 1.4x reveals significant system stress during winter evenings.





**4. Data Source:**



RTE — eCO2mix annual definitive data (2022) : https://www.rte-france.com/donnees-publications/eco2mix-donnees-temps-reel/telecharger-indicateurs



**5. Tech Stack:**



* Python
* Pandas
* Matplotlib
* Seaborn
* Plotly
* SQL (SQLite)
* Power BI
* DAX































