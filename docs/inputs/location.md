
# Location — Enterprise

**Category:** Inputs

# USAGE GUIDELINES

- Use for any input that captures location-based information (e.g., Address, Postal Code, City).

- Supports both manual typing and autocomplete suggestions (e.g. dropdown list).

- Support optional use of geolocation API to fetch suggestions.

- Validation may apply to format (e.g. postal code) or selection rules (e.g. valid city name).

- Use ‘**md’** size for mobile view; ‘**lg’ **size for desktop view.
# CONTENT GUIDELINES

- Use short, helpful hint text (e.g. “Enter location or postal code”).

- Ensure placeholder text complements but doesn’t duplicate the label.

- Write clear and actionable error messages (e.g. “Please enter a valid location”).
# BEHAVIOUR (INTERACTIONS)

  

### Input Handling
- Accepts free-text entry or selection from autocomplete.
- Includes clear (X) button to reset field.
- Validates on blur, submit, or selection.

### Autocomplete (Optional)
- Suggests locations dynamically via API.
- Can be scoped to specific countries, regions, or categories.
- Selecting a suggestion auto-fills the field and closes the list.

### Validation & Error Handling
- Validates based on expected input (e.g. 6-digit postal code).
- Error messages appear inline.
- Message clears when valid input is provided.