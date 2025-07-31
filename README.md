# dora
calculator of bitcoin premium

START

INPUT: Initial USD Premium (e.g., $10,000)
-> INPUT: Current Bitcoin Price (e.g., $60,000 USD/BTC)

CALCULATE: Initial BTC Purchased

Formula: Initial BTC = Initial USD Premium / Bitcoin Price

Example: $10,000 / $60,000 = 0.1667 BTC
-> DISPLAY: Initial BTC Purchased

CALCULATE: Cash Value (after 10 years)

Assumption: 1% annual growth in BTC terms.

Formula: Cash Value BTC = Initial BTC * (1 + 0.01)^10

Example: 0.1667 BTC * (1.01)^10 = ~0.1834 BTC
-> CALCULATE: Cash Value (USD Equivalent)

Formula: Cash Value USD = Cash Value BTC * Current Bitcoin Price

Example: 0.1834 BTC * $60,000 = ~$11,004 USD
-> DISPLAY: Cash Value (BTC & USD)

CALCULATE: Death Benefit

Assumption: Fixed Death Benefit of 2.0 BTC.

Formula: Death Benefit USD = Fixed Death Benefit BTC * Current Bitcoin Price

Example: 2.0 BTC * $60,000 = $120,000 USD
-> DISPLAY: Death Benefit (BTC & USD)

END