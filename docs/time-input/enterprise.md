
# Enterprise

---

# USAGE GUIDELINES

- Use when time must be selected via a Time Picker, not entered manually.

- Field is display&hyphen;only — users cannot type directly.

- Interaction should always open the Time Picker overlay.

- Use a clear, consistent placeholder such as "HH : MM".

- Include a leading time icon to reinforce purpose.

- Disable the field when time selection is unavailable.

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

  
| Column 1 | Column 2 | Column 3 | Column 4 |  
| --- | --- | --- | --- |  
| Input Handling | Picker Activation | Selection & Display | Validation & Error Handling |  
| Field is non&hyphen;editable.<br>No typing, cursor, or keyboard input.<br>Selected or placeholder value remains centered and visually consistent. | Clicking or tapping anywhere on the field opens the Time Picker.<br>Leading time icon also triggers the picker.<br>Selected time populates the field immediately.<br>Picker closes after selection or cancellation. | Time displays in **HH:MM** format.<br>If cancelled, previous valid value remains.<br>If no selection was made, placeholder persists. | Field enters Error state when:<br>&hyphen; Invalid time is returned.<br>&hyphen; Selected time violates business rules (e.g., blocked slot, restricted hours).<br>Error clears automatically once a valid time is selected. |  


# CONTENT GUIDELINES

- Placeholder must match display format (e.g., **“HH:MM”**).

- Error messages should be clear and factual (e.g.,*“Please select a valid time.”*).