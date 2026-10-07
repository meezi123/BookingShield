# Leakage Policy

The model must use only information known at booking creation.

## Known leakage columns

- reservation_status
- reservation_status_date

## Columns to investigate before use

- booking_changes
- days_in_waiting_list
- assigned_room_type

These may be created or changed after the original booking, so they require verification before becoming model inputs.