# Data Quality Report

## Dataset

- Raw rows:
- Raw columns:
- Cleaned rows:
- Target: is_canceled

## Missing Values

- children:
- country:
- agent:
- company:

## Duplicate-looking rows

- Count:
- Decision: retained because there is no booking ID and identical rows may represent separate bookings.

## Invalid values

- Zero-guest rows removed:
- Negative ADR rows:
- Decision: negative ADR replaced with missing value and adr_was_negative flag created.

## Next Step

Leakage prevention and booking-time feature engineering.