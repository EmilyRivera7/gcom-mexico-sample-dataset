# Data Management Plan (DMP)
**Project Title:** Sample Dataset on GCoM Adoption in Mexican Municipalities 
**Researcher:** Emily Rivera Mondragon 
**Institution:** University of California, Merced  
**Project Type:** Open Science – Sample Dataset Publication  
**Date:** 2025
**License:** CC BY 4.0  


## 1. Overview of the Data
This project generates a small, cleaned dataset used to explore factors that influence the adoption of the Global Covenant of Mayors for Climate and Energy (GCoM) among Mexican municipalities. The dataset contains **15 variables** representing demographic, socioeconomic, educational, and civic engagement indicators.

### Data Sources
- **INEGI, 2010 (public)**
- **CONEVAL, 2010 (public)**
- **Public protest datasets, 2010 (public)**
- **PEMEX, 2010 (not included; sensitive and excluded)**

Only **non-sensitive public data** are published in the final open dataset.


## 2. Data Types and Formats
The following files are included in the repository:

- **sample_dataset.csv** — the cleaned sample dataset  
- **metadata.json** — machine-readable metadata describing all variables  
- **README.md** — documentation and project description  
- **DMP.md** — this Data Management Plan  
- **LICENSE** — CC-BY 4.0 license  

All files use open, universally readable formats (CSV, JSON, MD).


## 3. Documentation and Metadata
Documentation is provided in:

- **README.md**, which includes dataset description, purpose, variables summary, and usage guidelines.
- **metadata.json**, which includes detailed variable-level metadata following FAIR principles:  
  - variable names  
  - definitions  
  - measurement units  
  - coding structure  
  - data sources  

These files support interoperability and reuse.


## 4. Storage and Backup Strategy
During the research phase, the data are stored in:

- Local encrypted computer storage (password-protected)
- Cloud backup through UC Merced OneDrive
- GitHub repository (public copy with only non-sensitive data)

Backups occur automatically via OneDrive sync.



## 5. Ethical and Legal Considerations
- Only **public, non-sensitive** data are included.
- No personal or identifiable data are shared.
- Sensitive data obtained from PEMEX **are NOT uploaded**.
- The dataset is published under the **CC-BY 4.0 License**, allowing reuse with attribution.
- No Indigenous-related or restricted community data are included, so CARE principles are not triggered.
- Ethical handling of public data follows UC Merced guidelines.



## 6. Data Sharing and Access
The dataset is openly accessible through:
- **Public GitHub repository (open access)**

Anyone can:
- Download  
- Reuse  
- Transform  
- Cite the data  

as long as attribution is provided.

No access restrictions apply to the shared dataset.



## 7. Long-Term Preservation
The dataset and documentation will be preserved in:

1. **GitHub repository (public and persistent)**  
2. Optionally uploaded later to a more permanent repository such as:  
   - Zenodo  
   - OSF  
   (GitHub can be linked to Zenodo for DOI generation.)

The dataset is simple (CSV + JSON), ensuring long-term readability.



## 8. Responsibilities
- **Emily Rivera** is responsible for:
  - Creating and cleaning the dataset  
  - Ensuring no sensitive data are published  
  - Preparing metadata and documentation  
  - Uploading and maintaining the repository  

No additional collaborators are involved.


## 9. Risk Management
### Potential Risks  
| Risk | Mitigation |
|------|------------|
| Accidental publication of sensitive PEMEX (oil company in Mexico)data | Only public data included; careful manual cleaning performed |
| Loss of local files | Automatic OneDrive cloud backup |
| Repository deletion or corruption | Public GitHub copy ensures redundancy |
| Metadata inconsistencies | Both README and JSON provide documentation |

Risks are minimal due to dataset simplicity.



## 10. Final Compliance with FAIR Principles
- **Findable:** Structured metadata, clear variable names, GitHub repository.  
- **Accessible:** Public access without authentication.  
- **Interoperable:** Open formats (CSV/JSON), standard variable naming.  
- **Reusable:** Clear licensing, documentation, and provenance.

This DMP ensures sustainable, ethical, and transparent handling of the dataset.

