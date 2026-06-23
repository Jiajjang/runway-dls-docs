
# Enterprise

---

# USAGE GUIDELINES

- Use when users need to enter short text that fits a single line.

- Always include a visible label — do not rely solely on placeholder text.

- Add helper text when additional context is helpful.

- Keep the input width aligned to surrounding form elements.

- Avoid multiline content — use [Text Area](../text-area/enterprise.md) instead.

- Use as the base for other variants (Email, Search, Password, etc.).

- Disable when input should not be editable.

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

  
| Column 1 | Column 2 | Column 3 |  
| --- | --- | --- |  
| Input Handling | Keyboard Interaction | Validation & Error Handling |  
| Accepts alphanumeric characters, punctuation, and common symbols.<br>Supports copy, paste, cursor movement, and editing.<br>Placeholder disappears on input and returns when cleared. | **Tab**: Moves to the next input or focusable element.<br>**Enter**: May trigger form submission (depending on context).<br>**Arrow keys**: Navigate left/right within the input. | Inline error appears below the field on blur or submit.<br>Examples:<br>*&hyphen; “This field is required.”*<br>*&hyphen; “Please enter a valid value.”*<br>Error clears automatically once input becomes valid. |  


# CONTENT GUIDELINES

- Use concise and clear label text.

- Add hint text only when necessary to explain expected input.

- Keep inline error messages specific and instructional.