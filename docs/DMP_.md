# Data Management Plan (DMP)  
**Project:** Determinants of Adoption of the Global Covenant of Mayors (GCoM) in Mexican Municipalities  
**Author:** Emily Rivera Mondragon  
**Affiliation:** University of California, Merced  
**Date:** December 2025  
**License:** CC BY 4.0  



## 1. Data Description

**Dataset:**  
- Municipal-level dataset (~360 municipalities in Mexico)  
- Sample dataset for open science purposes  
- Variables: socioeconomic indicators, population, education, civic engagement, GCoM membership, public universities, and protest activity

**Data Type:**  
- Quantitative (continuous, binary, categorical)  
- No personal or sensitive individual-level data included  

**Purpose:**  
- To examine factors influencing adoption of GCoM in Mexican municipalities  
- Support reproducible research and open science



## 2. Data Storage & Access

**Primary storage:** GitHub repository  
- Public access to CSV, JSON metadata, and documentation files  
- Version-controlled for reproducibility  

**Backup / Preservation:**  
- Zenodo upload (assign DOI for long-term preservation)  
- Local backup on secure university storage  

**Access conditions:**  
- Open-access for all public datasets  
- Sensitive data (e.g., restricted Pemex employment data) are excluded


## 3. Roles & Responsibilities

| Role | Responsibility |
|------|----------------|
| **Emily Rivera Mondragon** | Principal investigator, dataset compilation, cleaning, documentation, version control, and GitHub maintenance |
| **Advisor / Reviewer** | Feedback on data quality, methodology, and FAIR compliance |
| **Users / Contributors** | Can access dataset, cite properly, and suggest updates via GitHub pull requests |



## 4. Data Documentation & Metadata

**Files included in repository:**  
- `mexico_gcom_sample.csv` — dataset  
- `metadata.json` — dataset metadata  
- `data_dictionary.md` — description of variables and coding  
- `DMP_.md` — this data management plan  
- `methodology_notes.md` — optional workflow / analysis notes  
- `reflection.pdf` — optional reflection on open science

**FAIR Compliance:**  
- Findable: clear metadata and README  
- Accessible: CSV and JSON in public GitHub repo  
- Interoperable: open file formats (.csv, .md, .json)  
- Reusable: CC-BY license, variable descriptions, documentation



## 5. Data Preservation

**Long-term storage:**  
- GitHub repository + Zenodo (DOI)  
- Backups on secure university servers  
- Documentation ensures dataset can be reused for at least 5–10 years


## 6. Data Sharing & Licensing

**License:**  
- CC BY 4.0 (users must cite dataset)  

**Sharing:**  
- Public dataset available via GitHub  
- Metadata JSON and documentation files included  
- No restricted or sensitive data included



## 7. Risks & Mitigation

| Risk | Mitigation |
|------|------------|
| Loss of files | Version control in GitHub + Zenodo backup |
| Misuse of data | Clear licensing (CC-BY) and public README instructions |
| Sensitive data exposure | Exclude restricted datasets from public release |
| Documentation gaps | Complete metadata.json, data_dictionary.md, and DMP.md |


## 8. Ethical Considerations

- Only publicly available and non-sensitive data included  
- CARE principles do not apply (no Indigenous or culturally sensitive data)  
- Analysis and sharing comply with open science standards



## 9. Review & Updates

- Dataset and documentation will be reviewed periodically  
- Updates or corrections will be reflected via GitHub commits and Zenodo DOI versioning
