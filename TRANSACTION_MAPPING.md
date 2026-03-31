# TRANSACTION → LEDGER MAPPING

## CAPITAL
DR Cash +amount
CR Equity -amount

## EXPENSE
DR Expense +amount
CR Cash -amount

## INCOME
DR Cash +amount
CR Income -amount

## TRANSFER
DR Target +amount
CR Source -amount

## SETTLEMENT
DR Cash +total
CR Customer -total

DR Receiver +receiverAmount
CR Cash -receiverAmount

DR CompanyRevenue +companyFee
CR Internal -companyFee

DR AgentPayable +agentFee
CR Internal -agentFee

## PURCHASE
DR Expense +amount
CR Supplier -amount

## SALE
DR Customer +amount
CR Revenue -amount

## OFFSET
DR Party +x
CR Party -x
