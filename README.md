# Post-Acute Care Cost Analysis

A data-driven decision support tool leveraging CMS Medicare data to assist patients and families in selecting suitable post-acute care (PAC) services.

## 🔍 Objective
Identify and predict key cost, quality, and access factors influencing Medicare payments for PAC facilities using:

- 📊 PCA (Principal Component Analysis)
- 📈 Regression Modeling
- 🧪 Exploratory Data Analysis (EDA)
- 💻 Tools: Python, R, Jupyter, RMarkdown

## 🗂️ Dataset

- **Source**: [CMS Medicare Post-Acute Care and Hospice - by Geography & Provider](https://data.cms.gov/provider-summary-by-type-of-service/medicare-post-acute-care-hospice/medicare-post-acute-care-and-hospice-by-geography-provider)

- **Description**:  
  The dataset contains approximately 89,393 rows and 88 columns, covering provider-level, state-level, and national-level data for various PAC settings—home health, hospice, SNFs, IRFs, and LTCHs.  
  It includes:
  - Beneficiary demographics and service utilization
  - Diagnoses and dual eligibility indicators
  - Medicare charges, payments, therapy minutes
  - Rural/urban classification and geography breakdown

## 📊 Key Findings
- Total service days and number of beneficiaries positively impact Medicare payment.
- Nursing visits and physical therapy minutes have a negative correlation.
- PCA helped reduce dimensionality and highlight top influencing features.

