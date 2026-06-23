
# Enterprise

---

# USAGE GUIDELINES

- Use this for any input that requires a mobile or landline number.

- Always pair with a clear label and optional hint text showing expected format.

- Support for international users requires a country selector.

- Automatically format and validate phone number based on the selected country.

- Use ‘**md’** size for mobile view; ‘**lg’ **size for desktop view.

## Variants

  
**Flag Selector Phone Input**  
  
- Displays country flag, country code, and phone number field.  
- Dropdown opens searchable country list with flags and codes.   
- Selected country determines input validation rules.  
  
**Code Selector Phone Input**  
  
• Shows country code (+XX) only, without flag icon.   
• Dropdown allows changing country or region.   
• Simpler visual style for forms with limited space.  


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
| Selector Interaction | Input Handling | Validation & Error Handling |  
| Clicking the dropdown opens a searchable list of countries with flag and dial code.<br>Selected country updates the prefix (e.g. `+65`) and internal validation format.<br>Dropdown closes on selection or when clicking outside. | Accepts only numeric characters and spaces.<br>Automatically formats based on selected country (e.g. `9123 4567` for SG).<br>Supports keyboard entry, copy&hyphen;paste, and retains formatting. | Real&hyphen;time or on&hyphen;blur validation (configurable).<br>Fails validation if:<br>&hyphen; Input is too short/long for selected country format.<br>&hyphen; Country code is missing (for international users).<br>Error messages appear below field.<br>Example messages:<br>&hyphen; “Please enter a valid mobile number.”<br>&hyphen; “Include country code if international.” |  


# CONTENT GUIDELINES

- Placeholder text should display a real&hyphen;world example number for context (e.g., “+65 9123 4567”).

- Error messages should state the problem clearly and be action&hyphen;oriented (e.g., “Please enter a valid number”, “Include country code if international.”).