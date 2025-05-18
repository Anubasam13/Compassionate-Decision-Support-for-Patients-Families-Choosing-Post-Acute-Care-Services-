# Post-Acute Care Cost Analysis

A data-driven decision support tool leveraging CMS Medicare data to assist patients and families in selecting suitable post-acute care (PAC) services.

## 🔍 Objective
Identify and predict key cost, quality, and access factors influencing Medicare payments for PAC facilities using:

- 📊 PCA (Principal Component Analysis)
- 📈 Regression Modeling
- 🧪 Exploratory Data Analysis (EDA)
- 💻 Tools: Python, R, Jupyter, RMarkdown

## 🗂️ Dataset
**📎 Data source link**: [CMS PAC Dataset](https://data.cms.gov/provider-data/)

**📘 Data Description**:  
The dataset contains ~89,393 rows and 88 columns, including provider-level, state-level, and national-level data for various post-acute care (PAC) settings—home health, hospice, SNFs, IRFs, and LTCHs.  
It covers:
- Beneficiary demographics, service utilization, diagnoses
- Medicare payments, total stays, charges, therapy minutes
- Dual eligibility, rural classifications, and more

## 📊 Key Findings
- Total service days and number of beneficiaries positively impact Medicare payment.
- Nursing visits and physical therapy minutes have a negative correlation.
- PCA helped reduce dimensionality and highlight top influencing features.

