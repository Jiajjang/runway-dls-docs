
# Text Input Field — Enterprise

**Category:** Inputs

# USAGE GUIDELINES

- Use when users need to enter short text that fits a single line.

- Always include a visible label — do not rely solely on placeholder text.

- Add helper text when additional context is helpful.

- Keep the input width aligned to surrounding form elements.

- Avoid multiline content — use [Text Area](../text-area/enterprise.md) instead.

- Use as the base for other variants (Email, Search, Password, etc.).

- Disable when input should not be editable.

- Use ‘**md’** size for mobile view; ‘**lg’ **size for desktop view.
# CONTENT GUIDELINES

- Use concise and clear label text.

- Add hint text only when necessary to explain expected input.

- Keep inline error messages specific and instructional.
# BEHAVIOUR (INTERACTIONS)

  

### Input Handling
- Accepts alphanumeric characters, punctuation, and common symbols.
- Supports copy, paste, cursor movement, and editing.
- Placeholder disappears on input and returns when cleared.

### Keyboard Interaction
- **Tab**: Moves to the next input or focusable element.
- **Enter**: May trigger form submission (depending on context).
- **Arrow keys**: Navigate left/right within the input.

### Validation & Error Handling
- Inline error appears below the field on blur or submit.
- Examples:
- *- “This field is required.”*
- *- “Please enter a valid value.”*
- Error clears automatically once input becomes valid.