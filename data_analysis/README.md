## Data analysis notebooks for COMM3180 Group Data Project

* This folder should contain the a series of Jupyter notebooks you create to do the data analysis.

# California Voting Patterns Project

## Project Overview

This project explores how political preferences vary across California counties and asks a central question:

**How blue is California, really?**

Although California is widely viewed as a Democratic stronghold, county-level voting patterns reveal substantial regional variation. Using election returns, proposition results, and demographic data, this project investigates how geography, demographics, income, education, and local economies shape political behavior across the state.

---

## Notebooks

### `general_election_data_exploration.ipynb`

Initial data cleaning and extraction of California proposition voting results from raw election files.  
Creates a county-level dataset for all 58 counties containing Yes/No vote totals for 10 statewide propositions.

**Main outputs:**
- Clean proposition vote totals by county
- Structured CSV for later analysis

---

### `clean_proposition_analysis.ipynb`

Analyzes county voting patterns on statewide ballot propositions.

This notebook:
- Removes unnecessary totals rows
- Calculates support percentages for each proposition
- Determines county-level winners (Yes / No)
- Compares propositions by issue area
- Identifies counties with strongest and weakest support
- Produces summary tables and visualizations

**Focus propositions:**
- Prop 3: Constitutional right to marriage  
- Prop 32: Raise minimum wage  
- Prop 36: Tougher drug and theft penalties

---

### `CA_counties_mapping.ipynb`

Introduces geographic mapping tools for California counties using GeoJSON boundary files.

This notebook demonstrates:
- Loading county shapefiles / GeoJSON data
- Merging election datasets with county boundaries
- Creating choropleth maps of county-level voting patterns

Used to visualize proposition support and regional political divides.

---

### `ACS Data Analysis.ipynb`

Explores county-level demographic and socioeconomic data from the American Community Survey (ACS).

Variables may include:
- Median age
- Race / ethnicity composition
- Education levels
- Employment
- Industry sectors
- Income

Used to examine relationships between demographics and political outcomes.

---

### `ACS_election.ipynb`

Combines ACS demographic data with election results to test how county characteristics relate to voting behavior.

Potential analyses include:
- Education vs Democratic vote share
- Income vs proposition support
- Racial composition vs party preference
- Employment sector vs political alignment

---

### `election_dataset.ipynb`

Works with historical election data across multiple years.

Used to study:
- County trends over time
- Counties that consistently vote Democratic or Republican
- Competitive / swing counties
- Changes in partisan margins from 2000–2024

---

## Key Research Questions

1. Is California uniformly Democratic, or does county-level variation tell a different story?  
2. Which counties consistently vote blue or red?  
3. Do counties change depending on the issue (social, economic, criminal justice)?  
4. How do education, race, income, and industry help explain voting patterns?  
5. Which counties are politically competitive or shifting over time?

---

## Preliminary Findings

- Coastal urban counties lean strongly Democratic.
- Inland and rural counties lean more Republican.
- Proposition voting shows counties do **not** behave identically across issues.
- Social, economic, and crime policy questions create different county coalitions.

---

## Authors

- Nina Lawson  
- Noah Sebhatleab  
- Sose Hovannisian
