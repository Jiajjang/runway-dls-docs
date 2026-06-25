
# Enterprise

# USAGE GUIDELINES

- Use when time must be selected via a Time Picker, not entered manually.

- Field is display-only — users cannot type directly.

- Interaction should always open the Time Picker overlay.

- Use a clear, consistent placeholder such as "HH : MM".

- Include a leading time icon to reinforce purpose.

- Disable the field when time selection is unavailable.

- Use ‘**md’** size for mobile view; ‘**lg’ **size for desktop view.
# CONTENT GUIDELINES

- Placeholder must match display format (e.g., **“HH:MM”**).

- Error messages should be clear and factual (e.g.,*“Please select a valid time.”*).
# BEHAVIOUR (INTERACTIONS)

### Input Handling
- Field is non-editable.
- No typing, cursor, or keyboard input.
- Selected or placeholder value remains centered and visually consistent.

### Picker Activation
- Clicking or tapping anywhere on the field opens the Time Picker.
- Leading time icon also triggers the picker.
- Selected time populates the field immediately.
- Picker closes after selection or cancellation.

### Selection & Display
- Time displays in **HH:MM** format.
- If cancelled, previous valid value remains.
- If no selection was made, placeholder persists.

### Validation & Error Handling
- Field enters Error state when:
- - Invalid time is returned.
- - Selected time violates business rules (e.g., blocked slot, restricted hours).
- Error clears automatically once a valid time is selected.

