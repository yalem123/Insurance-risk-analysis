Task 1: Exploratory Data Analysis & Initial Statistics
Objective:
The aim of Task 1 was to perform initial data cleaning, parsing, and exploratory analysis to understand the structure and relationships within the financial insurance dataset.

Key Activities:

Parsed and converted date fields such as VehicleIntroDate and handled missing or malformed entries using errors='coerce'.

Cleaned key numeric variables, particularly TotalPremium, TotalClaims, and SumInsured, ensuring consistent data types.

Conducted descriptive statistics and distributional analysis, identifying outliers and skewed distributions (especially for TotalPremium).

Created a histogram to visualize the distribution of TotalPremium, revealing a right-skewed pattern with a concentration of values below 2000.

Built a correlation heatmap to explore relationships between:

TotalPremium

TotalClaims

SumInsured

CalculatedPremiumPerTerm

Key Findings:

Moderate positive correlation between TotalPremium and CalculatedPremiumPerTerm (r = 0.64)

Weak correlation between TotalPremium and TotalClaims (r = 0.12)

No significant correlation between SumInsured and other variables.

Strong data imbalance in TotalPremium distribution — this may require log transformation or outlier treatment in future modeling steps.
