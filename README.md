# QSAR Data Curation Using ChEMBL

**Course:** AI and Drug Discovery (2026)  
**Program:** AI and Biotechnology / Bioinformatics  

---

## Overview
This repository presents a QSAR bioactivity data curation workflow using the ChEMBL database. The workflow demonstrates how bioactivity data can be retrieved, evaluated, and preprocessed using Python in Google Colab to generate curated datasets suitable for QSAR modeling.

The focus of this work is on filtering and cleaning IC50 bioactivity measurements for a selected molecular target and preparing the data for downstream machine learning applications.

---

## Selected Target
- **Target name:** PREB (Prolactin Regulatory Element Binding protein)
- **Database:** ChEMBL
- **Bioactivity endpoint:** IC50 (nanomolar units)

PREB was selected based on the availability of bioactivity data in ChEMBL and the suitability of the dataset for QSAR data curation and analysis.

---

## Bioactivity Records
- **Number of retrieved IC50 bioactivity records:** **<5391>**

Bioactivity records were evaluated to ensure sufficient data quality and a manageable dataset size for QSAR modeling after preprocessing.

---

## Data Curation Workflow
The following data curation steps were performed:

1. Connection of Google Colab to Google Drive for data storage
2. Retrieval of PREB-related bioactivity data from ChEMBL using `chembl_webresource_client`
3. Filtering of bioactivity records to retain IC50 measurements only
4. Removal of missing, invalid, or inconsistent bioactivity values
5. Classification of compounds into active, intermediate, and inactive classes based on IC50 thresholds
6. Export of curated bioactivity datasets in CSV format

---

## Repository Contents
- `Assignment_2_QSAR_data_curation.ipynb`  
  Jupyter notebook containing the complete QSAR data curation workflow

- `data/`  
  Curated bioactivity datasets saved as CSV files

---

## Tools and Libraries
- Python
- Google Colab
- pandas
- chembl_webresource_client

---

## Author
Anupama Satyarthi
