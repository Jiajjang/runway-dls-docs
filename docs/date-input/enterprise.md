
# Enterprise

---

# USAGE GUIDELINES

- Use when users can either type a date or open a Date Picker for selection.

- Display clear format guidance (e.g., DD/MM/YYYY).

- Tapping or clicking the field opens the Date Picker overlay.

- Validate input automatically when typed or after selection.

- Use ‘**md’** size for mobile view; ‘**lg’ **size for desktop view.

- For date selection, see [Date Picker](#).

## States

  
**Filled**  
  
  
  
**Placeholder**  
  
  
  
**Focused**  
  
  
**Disabled**  
  
  
**Error**  
  
  
**Error (Focused)**  
  


---

# BEHAVIOUR (INTERACTIONS)

  
| Column 1 | Column 2 | Column 3 | Column 4 |  
| --- | --- | --- | --- |  
| Input Handling | Picker Activation | Validation & Error Handling | Mobile Behaviour |  
| Accepts manual date entry in DD/MM/YYYY format.<br>Restricts non&hyphen;numeric characters except “/”.<br>Formats input as users type. | Opens[ Date Picker](#) overlay on click, tap, or icon press.<br>Selected date populates the input field automatically.<br>Overlay closes after selection or focus loss. | Validates typed or selected dates for correct format and range.<br>Displays inline error when invalid (e.g., “Enter a valid date”).<br>Clears error automatically once a valid date is entered or selected. | Opens native Date Picker where supported.<br>Uses numeric or date&hyphen;optimized keyboard for manual entry. |  


# CONTENT GUIDELINES

- Include contextual hints such as “Select departure date.”