
# Enterprise

---

# USAGE GUIDELINES

- Use for sensitive fields requiring secure inputs.

- Display password rules below the input when applicable for transparency. These rules should be visible in all states except disabled.

- Use the visibility toggle to help avoid typographical errors.

- Use helper text only for contextual instructions, not rules.

- Validate inputs either:

- Disable field only when password entry is not applicable.

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
| Input Handling | Visibility Toggle | Password Rules (if used) | Validation & Error Handling |  
| Default masking (•••••••) for all entries.<br>Accepts alphanumeric, symbols, and special characters.<br>No auto&hyphen;capitalization or autocorrect on mobile.<br>Standard cursor movement/editing expected. | Tapping the eye icon toggles between masked and visible states.<br>Label (“Show/Hide Password” and icon (eye close/open) update dynamically when toggled.<br>Visible state resets when user leaves field (if enforced by security policy). | Rules are always visible below the field**,** except in disabled state.<br>Rules appear in 3 states:<br>&hyphen; Grey (●) → unmet rule<br>&hyphen; Green (✔) → rule met<br>&hyphen; Red (❗) → failed rule<br>Rules update dynamically as the user types. | Input shows error state when:<br>&hyphen; Field left empty when required<br>&hyphen; 1 or more rules are not met<br>Error clears once all rules passes. |  


# CONTENT GUIDELINES

- **Labels**: Use "Password" or context&hyphen;appropriate labels (e.g. "Create Password").

- **Helper Text**: Keep short and relevant; do not restate rules.

- **Error Text**: Specific and actionable, e.g. “Password must be at least 8 characters.”

- On blur

- In real&hyphen;time as user types

- On submit, depending on flow requirements.