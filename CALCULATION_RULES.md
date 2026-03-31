# CALCULATION RULES

INPUT:
baseAmount, companyRate, agentRate, mode

EXCLUSIVE:
fees = base * rates
customerPays = base + fees
receiver = base

INCLUSIVE:
fees = base * rates
receiver = base - fees
customerPays = base

ROUNDING:
2 decimals, HALF UP

VALIDATION:
no negative values
