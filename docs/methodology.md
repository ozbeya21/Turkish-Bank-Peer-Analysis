# Methodology

## Project Objective

This project analyzes the relative financial strength of three major Turkish private banks:

- Akbank
- Garanti BBVA
- Isbank

The analysis covers financial data from **FY2023 to FY2025** and aims to answer the following question:

> Which bank performs best under normal economic conditions and which bank remains more resilient under stress scenarios?

Instead of focusing solely on individual financial ratios, the study builds a **structured peer comparison framework combined with scenario-based risk analysis**.

---

# Data Sources

All data was collected from publicly available **Investor Relations disclosures** of each bank.

The dataset contains financial metrics structured as:

- Dimension
- Metric
- Unit
- FY2023
- FY2024
- FY2025

Key variables include:

- Total Assets
- Total Loans
- Total Deposits
- Equity
- Net Profit
- ROE
- ROA
- NIM
- NPL Ratio
- Stage 3 Coverage
- Cost of Risk
- CET1
- CAR
- IRRBB
- LDR
- Loan Growth

---

# Data Validation and Standardization

Since banks report some metrics under slightly different names or definitions, the first step was to standardize the dataset.

Examples include:

- Net Income → Net Profit
- Multiple LDR definitions → unified LDR metric
- Different naming conventions for Cost of Risk

Three important caveats were identified during the validation phase:

### 1. NIM Definition Differences

Some banks report **swap-adjusted NIM** while others include swap costs.  
Therefore NIM is used cautiously and not as the sole profitability indicator.

### 2. Cost of Risk Reporting Differences

Cost of Risk definitions may vary slightly across banks due to FX adjustments.  
It is interpreted comparatively rather than as an absolute metric.

### 3. IRRBB Availability

IRRBB data was available only for **FY2025**, therefore it is used as a **snapshot metric rather than a trend metric**.

---

# Peer Comparison Framework

The analysis evaluates banks across **seven analytical dimensions**:

1. Credit Growth  
2. Balance Sheet Composition  
3. Profitability  
4. Credit Portfolio Quality  
5. Capital Adequacy  
6. Liquidity  
7. Interest Rate Risk (IRRBB)

Each dimension captures a different aspect of bank performance and risk exposure.

---

# Dimension Metrics

## Credit Growth
Measures lending expansion.

Primary metric:
- Loan Growth (YoY)

Purpose:
- Evaluate growth strategy and potential risk buildup.

---

## Balance Sheet Composition

Key derived ratios:

- Loans / Assets
- Deposits / Assets
- Equity / Assets

Purpose:
- Understand structural balance sheet positioning.

---

## Profitability

Key indicators:

- Net Profit
- ROE
- ROA
- NIM

Purpose:
- Assess the strength and sustainability of earnings generation.

---

## Credit Portfolio Quality

Risk evaluation uses three complementary indicators:

- NPL Ratio (stock of problem loans)
- Stage 3 Coverage (loss buffer)
- Cost of Risk (flow of credit cost)

Purpose:
- Measure both credit deterioration and risk absorption capacity.

---

## Capital Adequacy

Key metrics:

- CET1 Ratio
- Capital Adequacy Ratio (CAR)

Purpose:
- Evaluate regulatory capital buffers and stress absorption capacity.

---

## Liquidity

Primary metric:

- Loan-to-Deposit Ratio (LDR)

Interpretation:

Lower LDR indicates stronger funding capacity and greater resilience during liquidity stress.

---

## Interest Rate Risk (IRRBB)

Metric:

- IRRBB sensitivity to interest rate shocks.

Lower values indicate lower exposure to interest rate changes.

---

# Scoring Model

To translate financial metrics into a decision framework, a **multi-factor scoring model** was constructed.

Four composite scores were calculated:

### Profitability Score
Based on:

- ROE
- NIM (lower weight due to reporting differences)

---

### Credit Risk Score

Based on:

- NPL Ratio
- Cost of Risk
- Stage 3 Coverage

---

### Resilience Score

Calculated using:

CET1 − IRRBB

This captures both capital strength and interest rate sensitivity.

---

### Liquidity Score

Derived from:

Inverse LDR scale

Lower LDR corresponds to higher liquidity score.

---

# Additional Supporting Metrics

Two additional indicators were used to support the final interpretation.

### Risk Adjusted Return (RAR)

RAR = ROE / Cost of Risk

This measures profitability relative to credit risk cost.

---

### Capital Efficiency

Capital Efficiency = ROE / CET1

This evaluates how effectively a bank utilizes its capital base.

---

# Scenario-Based Evaluation

Instead of producing a single ranking, the analysis evaluates banks under multiple scenarios.

---

## Base Case Scenario

Assumes a relatively stable economic environment.

Higher weight is assigned to:

- Profitability
- Credit quality
- Capital strength

### Result

Garanti BBVA ranks highest due to strong profitability and relatively low risk metrics.

---

## Funding Stress Scenario

Assumes liquidity pressure in the banking system.

Higher weight is assigned to:

- Liquidity
- Credit risk
- Capital buffers

### Result

Isbank ranks strongest due to its lower LDR and stronger funding flexibility.

---

## Interest Rate Shock Scenario

Focuses on sensitivity to interest rate changes.

Primary metric:

- IRRBB

### Result

Garanti BBVA shows the lowest interest rate sensitivity.

---

# Final Conclusions

The analysis produces scenario-dependent outcomes:

- **Base-case winner:** Garanti BBVA  
- **Funding-stress winner:** Isbank  
- **Rate-shock winner:** Garanti BBVA  

This demonstrates that bank performance depends significantly on the macroeconomic stress scenario.

---

# Analytical Skills Demonstrated

This case study demonstrates:

- Financial statement interpretation
- Banking risk metric analysis
- Data standardization
- Peer benchmarking
- Scenario-based risk thinking
- Structured decision framework design
