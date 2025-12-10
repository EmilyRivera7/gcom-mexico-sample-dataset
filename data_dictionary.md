# Data Dictionary  
**Dataset:** Sample Dataset on GCoM Adoption in Mexican Municipalities 
**Author:** Emily Rivera Mondragón  
**Last updated:** December 2025  
**License:** CC BY 4.0  



## Overview  
This data dictionary describes all variables included in the sample dataset of Mexican municipalities used to analyze determinants of adoption of the **Global Covenant of Mayors for Climate & Energy (GCoM)**.  

The dataset compiles demographic, socioeconomic, educational, institutional, and civic engagement variables from publicly available sources (INEGI 2010, CONEVAL 2010, and open civic-mobilization records). All sensitive or restricted fields have been removed.



## Variable List  

| Variable Name       | Type | Description | Units / Coding | Source |
|--------------------|------|-------------|----------------|--------|
| **State** | Categorical (string) | Name of each state in Mexico. | — | INEGI 2010 |
| **City/Mun** | Categorical (string) | Name of the municipality. | — | INEGI 2010 |
| **CoM** | Binary (0/1) | Indicates whether the municipality is a member of the Global Covenant of Mayors. | 1 = Member; 0 = Non-member | GCoM Registry |
| **pop_2010** | Numeric (integer) | Total population in 2010. | Number of inhabitants | INEGI 2010 |
| **pop_2010_LOG10** | Numeric (float) | Logarithm base 10 of the 2010 population. | log10(pop_2010) | Computed |
| **Join_Year_GCoM** | Numeric (integer) | Year the municipality joined GCoM. | YYYY (or NA if not a member) | GCoM Registry |
| **AdultsBD2010** | Numeric (integer) | Number of adults with a Bachelor's degree (2010). | People | INEGI 2010 |
| **PercAdultsBD2010** | Numeric (float, %) | Percentage of adult population with a Bachelor's degree (2010). | 0–100 (%) | INEGI 2010 |
| **PercPov2010** | Numeric (float, %) | Percentage of population living in poverty (2010). | 0–100 (%) | CONEVAL 2010 |
| **PubUniv** | Numeric (integer) | Number of public universities in the municipality. | Count | SEP, 2010 (Open data) |
| **PubUnivSt** | Numeric (integer) | Number of public universities in the state. | Count | SEP, 2010 (Open data) |
| **ProtestCities** | Binary (0/1) | Indicates whether at least one climate protest occurred in the city (based on civic mobilization datasets). | 1 = Yes; 0 = No | Global protest databases (open civic data) |
| **SocAssociations** | Binary (0/1) | Whether any social association (NGO, civic group) exists in the municipality. | 1 = Yes; 0 = No | Open civic association registry |
| **SocAssNum** | Numeric (integer) | Number of social associations present in the municipality. | Count | Civic association registry |
| **SocAssIn** | Categorical / Binary | Type of social association present. | 0 = International; 1 = Local | Civic association registry |

---

## Notes on Data Quality  
- All variables have been cleaned and standardized to ensure interoperability.  
- No personal or sensitive individual-level data are included.  
- Missing values (e.g., for non-member join years) are coded as `NA`.  
- Data sources are publicly available and reproducible.

---

## Contact  
For questions or to request updates to the dataset:  
**Emily Rivera Mondragón — University of California, Merced**  
Email: eriveramondragon@ucmerced.edu  

