## ADDED Requirements

### Requirement: Contextual safety
The system SHALL distinguish incomplete daily records from complete days and SHALL withhold personalized energy comparison when required profile fields are absent.

#### Scenario: Incomplete day
- **WHEN** only breakfast has been logged and the day is not marked complete
- **THEN** the output indicates an incomplete record and does not infer dangerous restriction from the daily total alone
