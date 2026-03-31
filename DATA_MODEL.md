# DATA MODEL

## CASE
id, title, type, status, createdAt

## PARTY
id, name, type, createdAt

## ACCOUNT
id, partyId, type, currency

## TRANSACTION
id, caseId, type, amount, currency, createdAt

## LEDGER_ENTRY
id, transactionId, caseId, accountId, partyId, amount, currency, createdAt

## DOCUMENT
id, caseId, fileUrl, type, hash, createdAt
