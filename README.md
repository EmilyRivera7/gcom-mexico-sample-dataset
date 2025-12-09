# Sample Dataset: Factors Influencing GCoM Adoption in Mexican Municipalities

This repository contains a small open-access dataset created for an Open Science project.  
The dataset includes public socioeconomic and civic indicators for a sample of Mexican municipalities, used to explore the factors associated with participation in the Global Covenant of Mayors for Climate and Energy (GCoM).

The purpose of this repository is to demonstrate good open science practices by sharing data, documentation, and metadata in a transparent and reproducible manner.

---

## Dataset Description

File: `gcom-mexico-sample-dataset.csv`  
This dataset includes a small sample of municipalities (not the full research dataset) and contains only publicly available information.

The variables included are:

| Variable | Description |
|---------|-------------|
| `State` | Name of each state in Mexico |
| `City/Mun` | Name of the municipality in Mexico |
| `CoM` | 1 = municipality belongs to the Global Covenant of Mayors, 0 = municipality does not belong to the Global Covenant of Mayors |
| `pop_2010` | Total population in 2010 |
| `pop_2010_LOG10` | Base-10 logarithm of the total population in 2010 |
| `Join_Year_GCoM` | Year in which the municipality adopted the Global Covenant of Mayors |
| `AdultsBD2010` | Adult population with a Bachelor's degree in 2010 (INEGI 2010) |
| `PercAdultsBD2010` | Percentage of adult population with a Bachelor's degree in 2010 |
| `PercPov2010` | Percentage of the population living in poverty in 2010 |
| `PubUniv` | Number of public universities in the municipality |
| `PubUnivSt` | Number of public universities in the state |
| `ProtestCities` | Cities where climate protests occurred |
| `SocAssociations` | 1 = municipality had a protest, 0 = municipality did not have a protest |
| `SocAssNum` | Total number of social associations in the municipality |
| `SocAssIn` | Social association type: 0 = International, 1 = Local |



This dataset is meant for demonstration and educational purposes.  
It does not include sensitive, restricted, or confidential data.

---

## Purpose of the Dataset

The goal of this sample dataset is to:

- Illustrate how socioeconomic and civic factors may influence the likelihood of municipalities joining GCoM.
- Provide an example of a clean, documented open-access dataset following open science standards.
- Serve as supporting material for the Open Science final project.

---

## Data Sources

All data included in the sample comes from public and openly accessible sources:

- **National Institute of Statistics and Geography (INEGI):** Population data  
- **National Council for the Evaluation of Social Development Policy (CONEVAL):** Poverty measurements  
- **Public protest/event records:** Aggregated indicators on civic climate mobilization  

No restricted or sensitive data (such as PEMEX (oil company in Mexico) employment data) is included in this repository.

---

## Metadata

Additional dataset metadata is provided in the `metadata.json` file, including:

- Title  
- Creator  
- Description  
- Keywords  
- License  
- Sources  
- Date of creation  

This reduces ambiguity and facilitates reuse.


## Relevance to My Research
This dataset directly supports my dissertation research on understanding the socioeconomic, civic, and institutional factors that influence the adoption of the Global Covenant of Mayors for Climate and Energy (GCoM) among Mexican municipalities.
Sharing this sample openly provides transparency in my research design and allows others to explore the structure and variables used in my broader analysis of local climate governance.

## • FAIR Principles Applied

Findable:
The dataset includes structured metadata, a descriptive file name, and a stable DOI-ready GitHub repository for long-term accessibility.

Accessible:
All files are openly accessible without restrictions, passwords, or institutional affiliation. The data is provided in universally readable formats (CSV and JSON).

Interoperable:
Variables follow conventional data formats, use standard naming practices, and can be imported into statistical software (R, Python, STATA, Excel).

Reusable:
The dataset includes complete documentation, variable definitions, sources, limitations, and a CC-BY 4.0 license that explicitly allows reuse with attribution.

CARE Principles Statement:
The CARE principles do not apply to this dataset because it does not contain Indigenous data, community knowledge, culturally sensitive information, or tribal-level identifiers.

## • Ethical & Legal Considerations

This dataset is ethically sharable because it relies exclusively on publicly accessible information from national institutions such as INEGI and CONEVAL. 
No personal, confidential, or restricted data is included. Although my full research dataset contains sensitive information acquired through formal requests (e.g., PEMEX, oil company in Mexico, employment data), those variables are not included in this open-access version to comply with legal and ethical constraints.

All data remains the intellectual property of their original institutions. This repository redistributes them in cleaned and aggregated form under fair use for academic and scientific purposes.
The dataset is released under a CC BY 4.0 License, allowing reuse and adaptation provided appropriate credit is given.

---

## License

This dataset and all files in this repository are shared under the Creative Commons Attribution 4.0 International License (CC BY 4.0).

This means you are free to:

- Share — copy and redistribute the material  
- Adapt — remix, transform, and build upon it  

As long as proper credit is given.

---

##  Contact

For questions, suggestions, or collaboration, please contact:

**Emily Rivera Mondragon**  
PhD Student, University of California, Merced  
Open Science Project – 2025
eriveramondragon@ucmerced.edu
emilyrivera281@gmail.com

---

##  Citation

If you use this dataset, please cite it as:

> Rivera-Mondragon, E. (2025). Sample Dataset: Factors Influencing GCoM Adoption in Mexican Municipalities. GitHub Repository.
