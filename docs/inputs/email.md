
# Email — Enterprise

**Category:** Inputs

# USAGE GUIDELINES

- Use when collecting a user’s email for login, contact, verification, or notifications.

- Always display a clear label (“Email” or “Email Address”).

- Include a hint or helper text only when necessary (e.g., format guidance).

- Use an appropriate input type (email) to trigger the correct mobile keyboard.

- Avoid using a placeholder as the only indicator of purpose — labels must remain visible.

- Validate format automatically as the user types or on blur.

- Disable the field when email input is not allowed or pre-filled and non-editable.

- Use ‘**md’** size for mobile view; ‘**lg’ **size for desktop view.

# BEHAVIOUR (INTERACTIONS)

  

### Input Handling
- Auto-inserts space every 4 digit
- Restricts non-numeric characters
- Shows visual confirmation (logo) when card type is recognized (e.g., starts with 5 → Mastercard)

### Validation & Error Handling
- Validates using standard email patterns (e.g., must include “@” and domain).
- Shows inline message for invalid entries (“Please enter a valid email address”).
- Error clears automatically when the value becomes valid.
- Supports domain-level validation when necessary (optional custom rules).