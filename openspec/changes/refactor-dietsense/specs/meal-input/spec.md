## ADDED Requirements

### Requirement: Bounded clarification
The system SHALL extract food, portion and meal date, ask at most two clarification rounds, and retain unresolved entries as pending.

#### Scenario: Missing portion
- **WHEN** the user provides a food without a portion
- **THEN** the system asks for the portion and does not commit an invented estimate
