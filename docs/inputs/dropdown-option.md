
# Enterprise

# USAGE GUIDELINES

- Triggers when the user clicks on the [Dropdown Input ](../dropdown-input/enterprise.md)field.

- Use when users must choose from a predefined set of options.

- Keep option text short, clear, and consistent with user-facing terminology.

- Show a maximum of 8 visible options before a scrollbar appears. Enable vertical scrolling when there are more than 8 options to prevent excessive height.

- Group related options logically to improve scan and selection.

- Maintain consistent spacing, font size, and selection indicators across variants.

- Avoid using more than one visual cue type (dot, icon, avatar) within the same list.

- When lists exceed 20 options, enable in-menu search or filtering.

# BEHAVIOUR (INTERACTIONS)

  

### Opening & Selection
- Click, tap, or press Enter to select an option.
- Single-select lists close immediately after selection.
- Multi-select lists remain open until user manually closes or confirms.
- Selected options update the linked Dropdown Input Field.

### Scrolling & Overflow
- Dropdown displays up to 8 visible items before scroll is enabled.
- Scrollbar appears automatically when more than 8 options exist.
- Scrollbar height scales dynamically based on container height.
- When over 20 options, in-list search or filtering should be implemented.
- Keyboard scroll (Arrow Up/Down) navigates seamlessly between visible and hidden options.

### Grouping
- Headers visually distinct with bold or smaller caps style.
- Group headers remain visible when scrolling.
- Groups are non-selectable and act as visual dividers only.

### Validation & Error Handling
- Disabled options are skipped during keyboard navigation.
- Parent Dropdown Input Field displays error if required selection is missing (“Please select an option”).
- Errors clear automatically upon valid selection.

