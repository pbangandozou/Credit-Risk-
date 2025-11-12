# Credit-Risk-
Credit Risk Data Generator (Synthetic → Styled Excel)

A fast, CLI-driven Python tool that creates synthetic consumer credit data, computes key risk metrics (DTI, utilization, default probability, credit score, risk grade), and exports a professionally formatted Excel workbook ready for analysis or demo use.

What It Does

Generate realistic sample borrower data (age, income, credit lines, delinquencies, balances, limits, loans, payments).

Compute derived fields: monthly debt payments, total debt, DTI ratio, credit utilization.

Estimate default probability with a logistic function over a composite risk score.

Assign an interpretable credit score (300–850) and map to a risk grade (Very Poor → Excellent).

Write to Excel and apply professional formatting (headers, borders, alignment).

Apply number formats: % for ratios/probabilities, $ for money fields.

Color-code Risk_Grade cells (green → red) for instant scanability.

Auto-size columns with sensible max widths for readability.

Print a concise CLI summary with count and default rate.

Key Features Feature Benefit
Synthetic data Realistic distributions & caps Useful for demos, prototypes, and teaching
Derived metrics DTI, utilization, total debt Immediate risk insights without extra prep
PD estimation Logistic over composite risk Probabilistic view of default risk
Scoring & grading 300–850 score + 5-bucket grade Intuitive interpretation for stakeholders
Excel styling Headers, borders, alignment, widths Clean, shareable workbook out of the box
Number formats %, $ where appropriate Reduces errors and speeds up analysis
Risk heat colors Grade-based cell fills Quick visual triage of borrower risk
CLI summary Count, defaults, default rate Sanity check right in the terminal

Outputs

Excel: credit_risk_data.xlsx (sheet: “Credit Risk Data”)
