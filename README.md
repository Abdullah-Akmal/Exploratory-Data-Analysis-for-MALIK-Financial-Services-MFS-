# Exploratory-Data-Analysis-for-MALIK-Financial-Services-MFS-

## Problem Statement

This project addresses the need to analyze loan approval patterns and customer behavior for MALIK Financial Services (MFS). It explores key questions such as:

- What are the loan approval rates across demographics?
- How do income, employment status, and loan amount influence approvals?
- What patterns exist in loan terms and customer profiles?

The primary goal is to derive actionable insights that optimize MFS’s loan approval processes and customer risk assessment strategies.

---

## Tools & Technologies

- **Python Libraries**: pandas, numpy, matplotlib, seaborn, pdfplumber
- **Data Sources**: 
  - MALIK_Loans_Database_Table.pdf
  - MALIK Loan Data.xlsx
- **Environment**: Jupyter Notebook

---

## Process Breakdown

### 1. Data Extraction & Integration

- Extracted tabular data from PDFs using pdfplumber.
- Loaded Excel data using pandas.
- Merged both datasets into a unified DataFrame for consolidated analysis.

### 2. Data Cleaning & Transformation

- Verified no missing or duplicate values.
- Converted relevant fields (e.g., LoanAmount, ApplicantIncome) to numeric types.
- Mapped categorical codes to human-readable labels for interpretability.

### 3. Exploratory Data Analysis (EDA)

#### Descriptive Statistics

- **Total loaned amount**: £95,557  
- **Average loan amount**: £148.15  
- **Average loan term**: 335 months

#### Loan Approval Insights

- Only **5.18%** of approved loans were granted to self-employed applicants.
- Significant gender gap in approvals — visualized via gender-wise approval rates.

#### Income Analysis

- **Mean income**: £5,365.59  
- **Standard deviation**: £6,021.94 (indicates high variability)

#### Loan Distribution

- **Min loan amount**: £9  
- **Max loan amount**: £700  
- Distribution visualized using box plots.

### 4. Visualization & Reporting

- Created the following plots using matplotlib and seaborn:
  - Loan approval rates by gender.
  - Income distribution histograms.
  - Loan amount box plots.
- Designed visuals to be report-ready and reusable.

---

## Business Insights

1. **Gender Disparity**  
   Male applicants had higher approval rates than females.

2. **Self-Employment Hurdle**  
   Only 5.18% of approved applicants were self-employed, indicating stricter criteria.

3. **Income Variability**  
   High standard deviation suggests a diverse applicant base.

4. **Loan Size Patterns**  
   Most loans ranged from £9 to £700, with a few high-value outliers.

---

## Actionable Recommendations

- **Risk Strategy Refinement**: Re-evaluate approval criteria for self-employed applicants.
- **Gender-Inclusive Policies**: Investigate and address approval gaps for female applicants.
- **Loan Product Optimization**: Align offerings with small-loan demand trends.

---

## Technical Contributions

- Developed an automated pipeline to merge and process PDF and Excel-based datasets.
- Built a modular EDA framework for scalable future analysis.

---

## Key Takeaway

This project uncovered key demographic and financial trends that can guide MFS in refining its risk models and promoting fair, data-driven loan approvals.

---


