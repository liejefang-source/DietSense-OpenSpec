## ADDED Requirements

### Requirement: Traceable retrieval
The system SHALL preserve source identifier, version, units and cooking state for each matched food. Missing matches SHALL remain unresolved.

#### Scenario: No compatible match
- **WHEN** all retrieved candidates have incompatible cooking states
- **THEN** the system requests clarification or returns insufficient evidence
