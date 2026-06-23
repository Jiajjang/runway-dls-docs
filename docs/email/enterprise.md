
# Enterprise

---

# USAGE GUIDELINES

- Use when collecting a user’s email for login, contact, verification, or notifications.

- Always display a clear label (“Email” or “Email Address”).

- Include a hint or helper text only when necessary (e.g., format guidance).

- Use an appropriate input type (email) to trigger the correct mobile keyboard.

- Avoid using a placeholder as the only indicator of purpose — labels must remain visible.

- Validate format automatically as the user types or on blur.

- Disable the field when email input is not allowed or pre&hyphen;filled and non&hyphen;editable.

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

  
| Column 1 | Column 2 |  
| --- | --- |  
| Input Handling | Validation & Error Handling |  
| Auto&hyphen;inserts space every 4 digit<br>Restricts non&hyphen;numeric characters<br>Shows visual confirmation (logo) when card type is recognized (e.g., starts with 5 → Mastercard) | Validates using standard email patterns (e.g., must include “@” and domain).<br>Shows inline message for invalid entries (“Please enter a valid email address”).<br>Error clears automatically when the value becomes valid.<br>Supports domain&hyphen;level validation when necessary (optional custom rules). |  
