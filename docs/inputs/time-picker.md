
# Time Picker — Enterprise

**Category:** Inputs

# USAGE GUIDELINES

- Triggered only through the [Time Input](#) field.

- Displays hour and minute columns with snapping intervals.

- Support configurable minute intervals (e.g., 1, 15, 30, or 60 minutes).

- Disable unavailable or out-of-range time slots.

- May auto-confirm on selection or require explicit confirmation (e.g., “Done”).

- Always return time in a consistent format (e.g., **HH : MM**).

# BEHAVIOUR (INTERACTIONS)

  

### Opening & Closing
- Opens when Time Input is clicked or tapped.
- Closes when:
- - User selects a time (auto-confirm mode),
- - User taps outside,
- - User taps “Done” or “Close” (if applicable).

### Scrolling & Snapping
- Hours and minutes scroll independently.
- Options snap into a centered selection slot.
- Active selection is visually highlighted.

### Selection
- Final value = selected hour + selected minute.
- Selected time is returned to the Time Input immediately.
- If user cancels, previously selected value remains unchanged.

### Validation & Error Handling
- Disabled or restricted time slots cannot be selected.
- If business logic invalidates a time (e.g., blocked window),Time Input shows error state (e.g., *“This timing is invalid.”*).
- Errors are cleared automatically after choosing a valid time.