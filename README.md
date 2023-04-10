# subway_analysis

Mapping subway delays in NYC (all 5 boroughs) beginning in 2020

Less delays vs. More delays 

Time series data? 

Data: https://data.ny.gov/Transportation/MTA-Subway-Trains-Delayed-Beginning-2020/wx2t-qtaz

Variables: 

month: The time period in which the delay metrics are being calculated (month and year).

subdivision: Represents the A Division (numbered subway lines), B Division (lettered subway lines) and systemwide.

line: Represents each subway line (1, 2, 3, 4, 5, 6, 7, A, C, E, B, D, F, M, G, J, Z, L, N, Q, R, W, S 42nd, S Rock, S Fkln).

day_type: Represents weekday as 1 and weekend as 2.

reporting_category: The six categories that delays are reported under: Infrastructure & equipment, Crew availability, Police & medical, External Factors, Operating conditions, Planned ROW work.

subcategory: The sub-categories that fall under the definition of Delays: Braking; Door-Related; Fire, Smoke, Debris; Inclement Weather; Crew Availability; Insufficient Supplement Schedule; Propulsion; Public Conduct, Crime, Police Response; Rail and Roadbed; Persons on Roadbed; Service Delivery; Sick/Injured Customer; Train Brake Activation - Cause Unknown; Subways Maintenance; Work Equipment; Capital Work - Other Planned ROW; External Debris on Roadbed; External Agency or Utility; Capital Work - Other Planned ROW; Other – CE; Other – Sig; Other Infrastructure; Other Internal Disruptions.

delays: The number of train delays per category and time period.