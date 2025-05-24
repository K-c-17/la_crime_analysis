# LA Crime Analysis Project

## 📊 Overview

This project explores crime trends in Los Angeles using data visualization techniques powered by **Tableau**. It provides stakeholders—including law enforcement, city officials, and community advocates—with clear, data-driven insights into crime patterns from **2020 to 2024**, emphasizing the impact of the COVID-19 pandemic, demographic patterns, and geographic distribution.

---

## 🧭 Objectives

The primary goals of this project were to:

* **Identify temporal trends**: Understand how crime rates changed during and after the COVID-19 pandemic.
* **Map geographical patterns**: Locate high-crime zones and uncover spatial trends in criminal activity.
* **Analyze demographic disparities**: Examine crime victimization by age, gender, and ethnicity.
* **Evaluate weapon usage**: Discover which crimes most frequently involve weapons.
* **Investigate neighborhood correlations**: Assess if certain types of crime are prevalent in specific areas and whether socioeconomic conditions play a role.

---

## 📁 Dataset Information

* **Source**: [LAPD Crime Data](https://catalog.data.gov/dataset/crime-data-from-2020-to-present) via Los Angeles Open Data Portal
* **Period Covered**: January 2020 – Present (regularly updated)
* **Size**: \~979,000 records; 28 variables
* **Fields Used**: Date, Location, Area, Weapon Type, Victim Age, Gender, Ethnicity, Crime Description, Resolution Status
* **Geographical Scope**: Greater Los Angeles Area
* **Privacy**: All incident addresses anonymized to the nearest 100-block

---

## 📌 Visualizations

### 1. **Crime Trends and Demographics Dashboard**

* Filters: Crime type, year, area, weapon type, etc.
* Key Findings:

  * Most victims aged 20–50
  * Handguns and strong-arm weapons most common
  * Hispanic/Latino and Black communities most affected
  * Central LA is a major hotspot

### 2. **Crime Distribution by Month/Year (Line Chart)**

* Shows monthly crime trends from 2021–2024
* Sharp decline post-March 2024; unclear seasonality trends

### 3. **Crime Hotspot Map (Gender Overlay)**

* Color-coded by victim gender
* Highlights clustering of male victimization in central/southern LA; female victimization more dispersed

### 4. **Crime by Victim Age (Histogram)**

* Highest crime incidence in the 25–35 age group
* Different age groups disproportionately affected by specific crimes

### 5. **Day & Time Analysis (Heatmap)**

* Peak crimes between 4 PM – 8 PM, especially Fridays
* Burglary and sexual assaults spike near midnight

### 6. **Gender-Based Crime Patterns (Treemap & Table)**

* Males: Battery/simple assault and vehicle burglary dominate
* Females: Identity theft and intimate partner violence prominent
* Localized gender disparities in victimization (e.g., N Hollywood has higher female victim rates)

---

## 🧠 Insights & Implications

* **Resource Allocation**: High-crime time slots and neighborhoods can guide targeted patrolling and deployment
* **Policy Development**: Age- and gender-specific patterns can influence public awareness campaigns and prevention strategies
* **Social Equity**: Recognition of demographic disparities aids in justice-oriented interventions

---

## 📚 References

1. [LAPD Crime Data](https://catalog.data.gov/dataset/crime-data-from-2020-to-present)
2. [Tableau Documentation](https://help.tableau.com/current/pro/desktop/en-us/gettingstarted_overview.htm)
3. Brett, C. (2016). *Impact of Technology on Policing Strategies*. NIJ.
4. Kirk, A. (2016). *Data Visualization: A Handbook for Data-Driven Design*. Sage.
5. Leitner, M. (2013). *Crime Mapping Using Geospatial Tech*. Springer.
6. FBI (2023). *Crime in the U.S.: 2022 Report*.
7. Rosés et al. (2021). *Agent-Based Simulation to Predict Crime Patterns*. CEUS.
