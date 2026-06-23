
# Enterprise

---

# USAGE GUIDELINES

- Use for any input that captures location&hyphen;based information (e.g., Address, Postal Code, City).

- Supports both manual typing and autocomplete suggestions (e.g. dropdown list).

- Support optional use of geolocation API to fetch suggestions.

- Validation may apply to format (e.g. postal code) or selection rules (e.g. valid city name).

- Use ‘**md’** size for mobile view; ‘**lg’ **size for desktop view.

## States

  
**Filled**  
  
  
**Placeholder**  
  
  
**Focused**  
  
  
**Disabled**  
  
  
**Error**  
  
  
**Error (Focused)**  
  


---

# BEHAVIOUR (INTERACTIONS)

  
| Column 1 | Column 2 | Column 3 |  
| --- | --- | --- |  
| Input Handling | Autocomplete (Optional) | Validation & Error Handling |  
| Accepts free&hyphen;text entry or selection from autocomplete.<br>Includes clear (X) button to reset field.<br>Validates on blur, submit, or selection. | Suggests locations dynamically via API.<br>Can be scoped to specific countries, regions, or categories.<br>Selecting a suggestion auto&hyphen;fills the field and closes the list. | Validates based on expected input (e.g. 6&hyphen;digit postal code).<br>Error messages appear inline.<br>Message clears when valid input is provided. |  


# CONTENT GUIDELINES

- Use short, helpful hint text (e.g. “Enter location or postal code”).

- Ensure placeholder text complements but doesn’t duplicate the label.

- Write clear and actionable error messages (e.g. “Please enter a valid location”).