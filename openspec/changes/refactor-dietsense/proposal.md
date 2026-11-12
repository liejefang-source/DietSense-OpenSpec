# Refactor DietSense

## Why
Convert the narrative proposal into testable behavior and explicit engineering decisions.

## What Changes
Define five capabilities, bounded clarification, source provenance, idempotent logging and contextual safety.

## Capabilities
### New Capabilities
- meal-input: structured input and clarification
- food-retrieval: compatible evidence retrieval
- nutrition-estimation: deterministic interval calculation
- daily-journal: date-aware idempotent records
- safe-response: contextual output and safety

### Modified Capabilities
None; this is the first formal specification baseline.

## Impact
Future implementation includes input adapters, retrieval, calculation, storage and response components. See REPORT.md for evaluation.
