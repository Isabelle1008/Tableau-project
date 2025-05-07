# Final-Project-Tableau

This Tableau project analyzes 16 years of wildlife strike data reported to the FAA by U.S. airlines, airports, and pilots. The dashboards aim to uncover patterns in strike frequency, risk factors, and cost impacts—informing aviation safety improvements.

Dataset: faa_data_subset.xlsx

https://docs.google.com/spreadsheets/d/1V-tOmmtGtiY_3XMnYtVblDhlj_kzLBxa/edit?usp=sharing&ouid=108445376648788204707&rtpof=true&sd=true.

Years Covered: 2000 to 2015
Source: FAA Wildlife Strike Database
https://wildlife.faa.gov/

## Project/Goal
Explore trends in strike frequency over time

Identify high-risk animal species and airports

Understand strike conditions (altitude, time of day, season, flight phase)

Analyze damage severity and financial consequences

Detect clusters of high-cost or high-altitude events
## Process
Data question was "What factors influence the frequency and severity of wildlife strikes at U.S."" airports

Sub-questions were :
When do most wildlife strikes occur? (Time of day, season, year trend)

Where are strikes most frequent? (Airport, state, region)

Which wildlife species or categories cause the most damage? (Species, animal category, group)

What flight phases are most vulnerable to strikes? (Takeoff, climb, approach, landing)

What’s the financial impact of wildlife strikes? (Total cost by species, damage level, altitude)

### Visualization

Line Chart: Strikes by Year

Bar Charts:Strikes by Time of Day, Strikes by Phase of Flight

Symbol Map: Strikes by Airport

Clustering: Grouping by Cost and Altitude

Tables (via Show Me): Top 20 Species by Damage, cost distribution by damage

Story titled "Flight Risk: Exploring 15 Years of Wildlife Strikes in U.S. Aviation" containing two Dashboards; One exploring the strikes and another analyzing the cost incurred



## Results
Strikes Are Increasing

Wildlife strikes have risen steadily since 2000, suggesting growing risk due to air traffic volume, better reporting, or ecological changes. However there was a sharp reduction in 2015.

Timing Matters

Most strikes occur during takeoff or landing, and are concentrated around dawn and dusk.

Spring and fall show the highest strike frequencies—linked to bird migration seasons.

Large Birds Cause the Most Damage

Species like Canada Geese and Turkey Vultures are responsible for the most costly and damaging strikes.

Strikes from large-bodied animals result in substantial or destructive damage and higher repair costs.

High-Risk Airports and States Identified

Airports in Texas, Florida, Colorado, and Illinois report the highest numbers of strikes.

Larger airports show greater frequency, potentially due to traffic volume and regional habitats.


## Challenges
Data Cleaning & Standardization

The raw data had missing or inconsistent entries, especially in fields like species names, costs, and damage types. Some values needed manual correction or filtering to ensure accuracy.

Clustering Interpretation

Tableau's clustering algorithm grouped strikes based on altitude and cost only

Skewed Cost Data

A small number of high-cost events skewed the overall cost distribution, making it hard to interpret averages

## Future Goals
Integrate External Data

Bring in external data sets like bird migration patterns, airport traffic volume, or weather data to better understand the context around high-risk strikes.

Predictive Modeling

Build a predictive model to estimate the likelihood of a strike or expected cost based on time, location, species, and flight phase.


## Conclusion:
Wildlife strikes are a growing and seasonal threat to aviation safety. Most occur at lower altitudes and during key migratory periods. Larger species and high-traffic airports represent the greatest risks. These insights can guide targeted prevention strategies and resource planning.

My dashboards are available on this link below

https://public.tableau.com/app/profile/isabelle.uwanyirigira/viz/Tableauprojectdash2/Flightrisk?publish=yes