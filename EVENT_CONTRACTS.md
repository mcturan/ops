# EVENT CONTRACTS

STRUCTURE:
id, type, userId, sourceApp, targetApps, payload, clientTime, serverTime, processedBy

## transfer_created
caseId, amount, currency, mode, companyFee, agentFee, receiverAmount

## transaction_created
transactionId, caseId, type, amount, currency

## ledger_created
transactionId, entries[]

## document_uploaded
caseId, documentId
