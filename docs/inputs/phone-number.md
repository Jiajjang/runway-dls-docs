
# Phone Number — Enterprise

**Category:** Inputs

# USAGE GUIDELINES

- Use this for any input that requires a mobile or landline number.

- Always pair with a clear label and optional hint text showing expected format.

- Support for international users requires a country selector.

- Automatically format and validate phone number based on the selected country.

- Use ‘**md’** size for mobile view; ‘**lg’ **size for desktop view.
# CONTENT GUIDELINES

- Placeholder text should display a real-world example number for context (e.g., “+65 9123 4567”).

- Error messages should state the problem clearly and be action-oriented (e.g., “Please enter a valid number”, “Include country code if international.”).
# BEHAVIOUR (INTERACTIONS)

  

### Selector Interaction
- Clicking the dropdown opens a searchable list of countries with flag and dial code.
- Selected country updates the prefix (e.g. `+65`) and internal validation format.
- Dropdown closes on selection or when clicking outside.

### Input Handling
- Accepts only numeric characters and spaces.
- Automatically formats based on selected country (e.g. `9123 4567` for SG).
- Supports keyboard entry, copy-paste, and retains formatting.

### Validation & Error Handling
- Real-time or on-blur validation (configurable).
- Fails validation if:
- - Input is too short/long for selected country format.
- - Country code is missing (for international users).
- Error messages appear below field.
- Example messages:
- - “Please enter a valid mobile number.”
- - “Include country code if international.”