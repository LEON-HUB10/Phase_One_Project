# Aviation Accident Analysis

## Project Overview

This project analyzes aviation accident data from the NTSB (National Transportation Safety Board) database, covering incidents from 1962 up to the year 2023. The goal is to extract meaningful insights into the causes, patterns, and consequences of aviation accidents in the United States and international waters, using data science and exploratory data analysis (EDA) techniques.

The analysis includes:

• Data cleaning and preprocessing, including handling of missing values and inconsistent entries.

• Univariate analysis to understand the distribution of individual variables such as aircraft type, accident severity, engine type, and more.

• Bivariate and multivariate analysis to examine relationships between variables such as aircraft damage vs. number of injuries, engine type vs. accident count and much more

• Visualizations using tools like Matplotlib, Seaborn, and Tableau for interactive dashboards.

• Key insights and recommendations to inform aviation safety measures and guide future investigations.

This project follows the CRISP-DM methodology, ensuring a structured approach from business understanding to deployment and documentation.


## Business Understanding

Air travel is considered one of the safest modes of transportation, yet aviation accidents, though rare, can have devastating consequences. The goal of this project is to support data-driven improvements in aviation safety by analyzing historical accident data from the NTSB Aviation Accident Dataset (1962–2023).

The key business questions driving this analysis are:

* What are the most common causes and patterns associated with aviation accidents?

* How do factors such as aircraft type, engine type and weather conditions influence accident severity?

* Which combinations of variables for example aircraft damage, engine type or number of engines are most associated with fatalities or injuries?

By answering these questions, the project aims to:

* Help aviation stakeholders for example airlines, regulators and pilots identify high-risk areas.

* Inform preventive strategies and training programs.

* Support policy recommendations for improving aviation safety.



## Data Understanding and Analysis

The dataset used in this project is the NTSB Aviation Accident Database & Synopses, covering accidents and incidents in the United States and International waters from the year 1962 to 2023. Each row represents a single aviation event and includes information on:

* Event date and location

* Aircraft details such as make, model, engine type, aircraft damage level

* Injury information such as total fatal, serious,uninjured and minor injuries

* Flight purpose such as personal, instructional, business and much more

* Weather conditions
* probable causes such as report status and broad phase of flight

The Data Analysis steps included:
1. Initial Exploration

* Inspected data types, shape, and summary statistics

* Identified key columns such as Engine type Aircraft Damage, Injury Severity and weather conditions

* Assessed missing values and inconsistencies.

2. Data Cleaning
* Filtered out rows with missing critical data

* Filling missing values by looking for matching pairs in the data

* Standardized categorical entries

* Checking and removing outliers

3. Univariate Analysis
* Distribution of accident counts overtime

* Summary statistics for numeric variables

4. Bivaraite and Multivariate Analysis
* Relationships between fatal inuries and serious injuries, fatal inuries and aircraft categories and more

* Cross-tabs for injury severity vs. engine_type and weather_conditions

* Correlation heatmaps and boxplots for deeper patterns

## Conclusion and Recommendation

The key findings were:
1. Single-engine aircrafts are the most prone to accidents.

Recommendation: Implement more rigorous safety inspections, pilot training, and maintenance protocols specifically targeting single-engine aircraft, which represent the highest accident frequency.

2. Aircraft with reciprocating engines are involved in the most incidents, but they rarely result in fatal outcomes.

Recommendation: Maintain current engine standards, but enhance early failure detection and monitoring systems to further reduce incident rates for reciprocating-engine aircraft.

3. Visual Meteorological Conditions (VMC) account for most accidents including high-fatality ones.

Recommendation: Strengthen air traffic management, situational awareness, and standard operating procedures during VMC conditions, where complacency and exposure may lead to avoidable incidents.

4. Aircraft categorized as “Destroyed” are linked to the highest number of fatalities and serious injuries.

Recommendation: Invest in crash-absorbing structural designs, improved aircraft materials, and survivability systems for example emergency exits, fire suppression for aircraft more likely to experience full structural failure.

5. Airplanes and helicopters show wider variation in fatality counts, while gliders, balloons, and ultralights have consistently low or no fatalities.

Recommendation: Focus targeted safety audits, pilot licensing standards, and design reviews on airplane and helicopter operations, especially in high-traffic regions or commercial use cases.


Tableau Dashboard link - https://public.tableau.com/app/profile/leon.karanja/viz/PhaseOneProjectTableau/Dashboard1?publish=yes





