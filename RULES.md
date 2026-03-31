# RULES

## ABSOLUTE RULES
- No direct API calls between apps
- No shared databases
- Only communication: event system
- Firebase = transport only
- Offline-first mandatory

## LEDGER RULES
- Every transaction creates >=2 entries
- Sum(entries) = 0
- No stored balance

## UI RULES
- User must confirm all actions
- AI never commits automatically
