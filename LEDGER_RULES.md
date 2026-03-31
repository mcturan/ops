# LEDGER RULES (ABSOLUTE)

## CORE PRINCIPLE
Every financial transaction MUST produce a balanced set of ledger entries.

## RULE 1 — DOUBLE ENTRY (MANDATORY)
SUM(amounts) == 0

## RULE 2 — NO SINGLE ENTRY
Single-sided entries are strictly forbidden.

## RULE 3 — SIGN CONVENTION
Positive = increase, Negative = decrease

## RULE 4 — BALANCE IS DERIVED
Balance = SUM(ledger)

## RULE 5 — IMMUTABILITY
No edits, only reversing entries

## RULE 6 — REQUIRED FIELDS
id, caseId, transactionId, accountId, partyId, amount, currency, createdAt

## RULE 7 — CURRENCY CONSISTENCY
All entries same currency

## RULE 8 — VALIDATION
If any rule fails → reject transaction
