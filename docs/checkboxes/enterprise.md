
# Enterprise

---

# USAGE GUIDELINES

- Use when multiple options can be selected independently.

- Always include a clear, visible label — avoid relying on placeholder or icon&hyphen;only context.

- Use ‘**lg’** size when accompanied text is in font size 16px; ‘**md’ **size when accompanied text is in font size 14px.

- Use the **Indeterminate** state only for parent&hyphen;level selections (e.g., “Select All”).

- Disable when the option is unavailable or should remain fixed.

## Variants

  
**With Label**  
  
- Default form for most UI.  
- Label is clickable and toggles the checkbox.  
- Use when the option needs explanation, clarity, or accessibility.  
  
**Without Label**  
  
- Use only when the meaning is self&hyphen;evident (e.g., row selection in tables where column header already explains “Select”).  
- Must have an accessible name (e.g., “Select row: Flight TR189”).  


## States

  
**Default**  
  
  
**Hover**  
  
  
**Focused**  
  
  
**Disabled**  
  
  
**Error**  
  
  
**Error (Focused)**  
  


---

# BEHAVIOUR (INTERACTIONS)

  
| Column 1 | Column 2 | Column 3 | Column 4 |  
| --- | --- | --- | --- |  
| Selection | Keyboard | Indeterminate | Validation & Error Handling |  
| Clicking the checkbox or associated label toggles checked/unchecked.<br>Checkbox supports multi&hyphen;select within a group. | **Tab**: Moves focus.<br>**Space**: Toggles selection.<br>Focus ring remains visible for keyboard navigation. | Indeterminate is a computed visual state for parent checkboxes:<br>&hyphen; All children selected → Checked<br>&hyphen; None selected → Unchecked<br>&hyphen; Some selected → Indeterminate<br>Clicking an indeterminate parent typically results in:<br>&hyphen; Checked (select all), or Unchecked (clear all) depending on product logic (pick one behaviour and keep consistent). | Error appears when a required checkbox (or group) is not selected.<br>Show inline error message below the checkbox or group.<br>Error clears once a valid selection is made. |  
