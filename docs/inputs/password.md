
# Enterprise

# USAGE GUIDELINES

- Use for sensitive fields requiring secure inputs.

- Display password rules below the input when applicable for transparency. These rules should be visible in all states except disabled.

- Use the visibility toggle to help avoid typographical errors.

- Use helper text only for contextual instructions, not rules.

- Validate inputs either:

- Disable field only when password entry is not applicable.

- Use ‘**md’** size for mobile view; ‘**lg’ **size for desktop view.
# CONTENT GUIDELINES

- **Labels**: Use "Password" or context-appropriate labels (e.g. "Create Password").

- **Helper Text**: Keep short and relevant; do not restate rules.

- **Error Text**: Specific and actionable, e.g. “Password must be at least 8 characters.”

- On blur

- In real-time as user types

- On submit, depending on flow requirements.
# BEHAVIOUR (INTERACTIONS)

  

### Input Handling
- Default masking (•••••••) for all entries.
- Accepts alphanumeric, symbols, and special characters.
- No auto-capitalization or autocorrect on mobile.
- Standard cursor movement/editing expected.

### Visibility Toggle
- Tapping the eye icon toggles between masked and visible states.
- Label (“Show/Hide Password” and icon (eye close/open) update dynamically when toggled.
- Visible state resets when user leaves field (if enforced by security policy).

### Password Rules (if used)
- Rules are always visible below the field**,** except in disabled state.
- Rules appear in 3 states:
- - Grey (●) → unmet rule
- - Green (✔) → rule met
- - Red (❗) → failed rule
- Rules update dynamically as the user types.

### Validation & Error Handling
- Input shows error state when:
- - Field left empty when required
- - 1 or more rules are not met
- Error clears once all rules passes.

