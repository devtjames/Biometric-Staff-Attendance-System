# Technical Decisions

## Fingerprint Biometrics

Fingerprint authentication was selected to:

- Prevent staff impersonation
- Remove reliance on cards or passwords
- Ensure attendance reflects physical presence
- Improve accuracy of attendance records

---

## Centralized Database

A centralized database was used to:

- Maintain a single source of truth
- Enable reliable reporting
- Preserve historical attendance data
- Simplify auditing and administration

---

## Desktop-Based Deployment

A desktop-based approach was chosen because:

- Fingerprint scanners integrate directly with desktop systems
- Hardware behavior is more predictable
- Network dependency is reduced

---

## Data Integrity Approach

The system enforces correctness by:

- Recording exact timestamps for each event
- Preventing duplicate attendance entries
- Separating clock-in and clock-out actions
- Preserving historical logs without overwriting records

---

## Accepted Constraints

- Dependence on biometric hardware
- Initial fingerprint enrollment required
- Physical access to the system needed

These constraints were accepted based on the operating environment and project scope.
