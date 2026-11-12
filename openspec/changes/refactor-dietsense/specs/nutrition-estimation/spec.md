## ADDED Requirements

### Requirement: Deterministic estimates
The system SHALL calculate kcal from edible grams and kcal per 100 grams and label assumption-based bounds as estimated ranges, not statistical confidence intervals.

#### Scenario: Known quantities
- **WHEN** edible mass is 150 g and density is 200 kcal per 100 g
- **THEN** the result is 300 kcal with the referenced source
