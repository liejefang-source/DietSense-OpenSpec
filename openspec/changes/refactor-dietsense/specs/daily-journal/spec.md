## ADDED Requirements

### Requirement: Idempotent date-aware logging
The system SHALL preserve the confirmed meal date and use request identifiers to prevent duplicate entries. Queries SHALL be read-only.

#### Scenario: Duplicate submission
- **WHEN** the same request identifier is submitted twice
- **THEN** only one meal entry is stored
