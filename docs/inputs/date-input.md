
# Date Input — Enterprise

**Category:** Inputs

# USAGE GUIDELINES

- Use when users can either type a date or open a Date Picker for selection.

- Display clear format guidance (e.g., DD/MM/YYYY).

- Tapping or clicking the field opens the Date Picker overlay.

- Validate input automatically when typed or after selection.

- Use ‘**md’** size for mobile view; ‘**lg’ **size for desktop view.

- For date selection, see [Date Picker](#).
# CONTENT GUIDELINES

- Include contextual hints such as “Select departure date.”
# BEHAVIOUR (INTERACTIONS)

  

### Input Handling
- Accepts manual date entry in DD/MM/YYYY format.
- Restricts non-numeric characters except “/”.
- Formats input as users type.

### Picker Activation
- Opens[ Date Picker](#) overlay on click, tap, or icon press.
- Selected date populates the input field automatically.
- Overlay closes after selection or focus loss.

### Validation & Error Handling
- Validates typed or selected dates for correct format and range.
- Displays inline error when invalid (e.g., “Enter a valid date”).
- Clears error automatically once a valid date is entered or selected.

### Mobile Behaviour
- Opens native Date Picker where supported.
- Uses numeric or date-optimized keyboard for manual entry.