# Turkish Banking Peer Comparison & Scenario-Based Risk Analysis

## Overview

This project presents a comparative financial analysis of three major Turkish private banks:

- Akbank
- Garanti BBVA
- İşbank

The analysis evaluates financial performance and risk resilience using publicly available financial disclosures from **FY2023–FY2025**.

The objective of the project is to determine:

- Which bank performs best under **normal economic conditions**
- Which bank remains **most resilient under funding stress**
- Which bank is **least sensitive to interest rate shocks**

The analysis combines **peer benchmarking, financial ratio analysis, and scenario-based evaluation** to produce structured insights.

---

# Key Analytical Dimensions

The banks are evaluated across **seven analytical dimensions**:

1. Credit Growth  
2. Balance Sheet Composition  
3. Profitability  
4. Credit Portfolio Quality  
5. Capital Adequacy  
6. Liquidity  
7. Interest Rate Risk (IRRBB)

Each dimension captures a different aspect of financial performance and stability.

---

# Data Sources

All data was collected from **public investor relations disclosures** of the respective banks.

Key financial metrics used in the analysis include:

- Total Assets  
- Total Loans  
- Total Deposits  
- Equity  
- Net Profit  
- Return on Equity (ROE)  
- Return on Assets (ROA)  
- Net Interest Margin (NIM)  
- Non-Performing Loan Ratio (NPL)  
- Stage 3 Coverage  
- Cost of Risk  
- CET1 Ratio  
- Capital Adequacy Ratio (CAR)  
- Interest Rate Risk in the Banking Book (IRRBB)  
- Loan-to-Deposit Ratio (LDR)  
- Loan Growth (YoY)

The raw datasets were validated and standardized to ensure comparability across banks.

---

# Analytical Methodology

The analysis follows a structured workflow:

Raw Data → Data Validation → Processed Dataset → Scoring Model → Visualizations → Presentation


### Step 1 — Data Validation

Financial metrics were reviewed and standardized across banks to ensure consistent definitions.

### Step 2 — Peer Comparison Framework

A master **FY2025 peer comparison table** was created to align the key financial metrics across banks.

### Step 3 — Multi-Dimensional Analysis

Each bank was evaluated across the seven analytical dimensions described above.

### Step 4 — Scoring Model

A scoring framework was constructed using four composite indicators:

- **Profitability Score**  
- **Credit Risk Score**  
- **Resilience Score**  
- **Liquidity Score**

Additional supporting indicators:

- **Risk Adjusted Return (RAR)** = ROE / Cost of Risk  
- **Capital Efficiency** = ROE / CET1

### Step 5 — Scenario Analysis

Banks were evaluated under three different macroeconomic scenarios:

1. **Base Case Scenario** – normal economic conditions  
2. **Funding Stress Scenario** – liquidity pressure in the banking system  
3. **Interest Rate Shock Scenario** – sensitivity to interest rate changes

---

# Key Results

### Base Case Winner
**Garanti BBVA**

Strong profitability metrics combined with relatively low credit risk and lower IRRBB exposure.

### Funding Stress Winner
**İşbank**

Lower Loan-to-Deposit Ratio provides stronger liquidity headroom under funding pressure.

### Interest Rate Shock Winner
**Garanti BBVA**

Lowest IRRBB exposure among the peer group.

---

# Repository Structure

Turkish-Bank-Peer-Analysis
│
├── data
│ ├── raw
│ └── processed
│
├── models
├── visuals
├── presentation
└── docs


### data/raw
Original financial datasets collected from investor disclosures.

### data/processed
Cleaned datasets and peer comparison tables used in the analysis.

### models
Scoring frameworks and analytical workbooks.

### visuals
Charts and figures used in the analysis and presentation.

### presentation
Final case study presentation.

### docs
Supporting documentation including methodology and metric definitions.

---

# Skills Demonstrated

This project demonstrates capabilities in:

- Financial statement analysis  
- Banking KPI interpretation  
- Data validation and standardization  
- Peer benchmarking  
- Scenario-based risk analysis  
- Analytical framework design  
- Data visualization  
- Decision-oriented financial analysis

---

# Author

**Ahmet Özbey**  
Mathematical Engineering Student – Istanbul Technical University
