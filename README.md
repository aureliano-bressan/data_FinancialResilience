# Financial Inclusion & Money Management Dataset

This dataset (`final_model_20_items.csv`) contains anonymized survey responses collected to study financial inclusion, money management, and social support indicators across different demographic groups.

## Dataset Description

Each row represents a unique participant, with columns capturing demographic information, financial inclusion (FI), money management (MM), and social support (SS) factors, as well as responses to related survey items.

### Column Definitions

- **age**: Age group of the respondent (numeric code)
- **gender**: Gender (numeric code)
- **region**: Geographic region (numeric code)
- **education_level**: Highest education achieved (numeric code)
- **income**: Income bracket (numeric code)
- **employment_status**: Employment status (numeric code)
- **race**: Racial/ethnic group (numeric code)
- **marital_status**: Marital status (numeric code)
- **housing_arrangement**: Type of housing/living arrangement (numeric code)
- **children**: Number of children (numeric code)
- **FI_BankAcc**: Has a bank account (Likert/ordinal scale)
- **FI_DebitCard**: Has a debit card (Likert/ordinal scale)
- **FI_Insurance**: Has insurance products (Likert/ordinal scale)
- **FI_DebitPurch**: Makes purchases using debit (Likert/ordinal scale)
- **FI_MobPay**: Uses mobile payments (Likert/ordinal scale)
- **MM_SaveBank**: Saves money in a bank (Likert/ordinal scale)
- **MM_Mgmt**: Actively manages finances (Likert/ordinal scale)
- **MM_Improve**: Seeks to improve money management (Likert/ordinal scale)
- **MM_PayExp**: Pays expenses on time (Likert/ordinal scale)
- **MM_SaveIncome**: Saves a portion of income (Likert/ordinal scale)
- **MM_StmtCtrl**: Reviews and controls bank statements (Likert/ordinal scale)
- **MM_PlanExp**: Plans expenses (Likert/ordinal scale)
- **MM_SaveNeed**: Saves for future needs (Likert/ordinal scale)
- **SS_Housing**: Has social support for housing (Likert/ordinal scale)
- **SS_HelpProb**: Receives help in problem situations (Likert/ordinal scale)
- **SS_Loan**: Can borrow from social network (Likert/ordinal scale)
- **SS_Salary**: Receives salary support (Likert/ordinal scale)
- **emergency_funds_salary**: Access to emergency funds equal to one salary (Likert/ordinal/code)
- **SS_2400**: Social support for R$2,400 (Likert/ordinal scale)
- **emergency_funds_2400**: Access to R$2,400 in emergency funds (Likert/ordinal/code)
- **MM_DailyFinance**: Manages daily finances (Likert/ordinal scale)
- **MM_OverKnow**: Overconfidence in financial knowledge (Likert/ordinal scale)

**Note:** All categorical variables are coded numerically. Please refer to the survey documentation for codebook details.

## How to Use

1. **Load the dataset** using your preferred tool (e.g., pandas in Python, R).
2. **Decode categorical variables** using the codebook (not included here).
3. **Analyze patterns** in financial inclusion, money management, and social support across demographics.

Example (Python, pandas):
```python
import pandas as pd
df = pd.read_csv("final_model_20_items.csv", sep=";")
print(df.head())
```

## Citation

If you use this dataset, please cite the original study or dataset source (add citation here).

## License

OpenSource. 

## Contact

For questions or access to the full codebook, contact the dataset author or research team.
