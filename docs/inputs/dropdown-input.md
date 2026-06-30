
# Dropdown Input — Enterprise

**Category:** Inputs

# USAGE GUIDELINES

- Use when users must select from a fixed list rather than entering free text.

- When clicked, it opens up a [Dropdown Option](#).

- Keep the field label clear and consistent with surrounding form fields.

- Show placeholder text when no selection has been made.

- Display the selected option(s) clearly within the field.

- Use the chevron icon to indicate open/close state.

- Disable the field when selection is unavailable.

- Use multi-select only when users must choose more than one value.

- Ensure field width accommodates long option labels without clipping.

- Use ‘**md’** size for mobile view; ‘**lg’ **size for desktop view.

# BEHAVIOUR (INTERACTIONS)

  

### Input Handling
- Field is non-editable; typing does not modify the value.
- Placeholder appears until user selects an option.
- Supports single-select or multi-select depending on configuration.

### Opening & Closing
- Dropdown opens when user clicks or taps the field or chevron icon.
- Dropdown closes on:
- - selecting an option (single-select)
- - pressing Esc
- - clicking outside
- - tapping outside on mobile

### Selection & Display
- Selected item replaces placeholder text.
- Multi-select values displayed as:
- - inline tags, or
- - a count summary (“3  selected”), depending on design.
- Selected option remains highlighted in the menu when reopening.
- Text truncates with ellipsis if too long for the field width.

### Validation & Error Handling
- Error state appears when the required selection is missing.
- Field is outlined in red with message such as “Please select an option.
- Error clears automatically upon valid selection.
- Disabled state prevents interaction and hides any error.