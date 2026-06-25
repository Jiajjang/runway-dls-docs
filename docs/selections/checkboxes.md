
# Enterprise

# USAGE GUIDELINES

- Use when multiple options can be selected independently.

- Always include a clear, visible label — avoid relying on placeholder or icon-only context.

- Use ‘**lg’** size when accompanied text is in font size 16px; ‘**md’ **size when accompanied text is in font size 14px.

- Use the **Indeterminate** state only for parent-level selections (e.g., “Select All”).

- Disable when the option is unavailable or should remain fixed.

# BEHAVIOUR (INTERACTIONS)

  

### Selection
- Clicking the checkbox or associated label toggles checked/unchecked.
- Checkbox supports multi-select within a group.

### Keyboard
- **Tab**: Moves focus.
- **Space**: Toggles selection.
- Focus ring remains visible for keyboard navigation.

### Indeterminate
- Indeterminate is a computed visual state for parent checkboxes:
- - All children selected → Checked
- - None selected → Unchecked
- - Some selected → Indeterminate
- Clicking an indeterminate parent typically results in:
- - Checked (select all), or Unchecked (clear all) depending on product logic (pick one behaviour and keep consistent).

### Validation & Error Handling
- Error appears when a required checkbox (or group) is not selected.
- Show inline error message below the checkbox or group.
- Error clears once a valid selection is made.

