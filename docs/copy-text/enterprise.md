
# Enterprise

---

# USAGE GUIDELINES

- Use when users need to copy static, non&hyphen;editable text (e.g., referral code, URL, tracking number).

- Keep field content short and readable; truncate long text if necessary.

- Provide visual feedback when the text is successfully copied.

- Do not allow direct editing or selection of field content.

- Use ‘**md’** size for mobile view; ‘**lg’ **size for desktop view.

## States

  
**Filled**  
  
  
**Focused**  
  
  
**Disabled**  
  
  
**Error**  
  
  
**Error (Focused)**  
  


---

# BEHAVIOUR (INTERACTIONS)

  
| Column 1 | Column 2 |  
| --- | --- |  
| Copy Action | Validation & Error Handling |  
| Clicking the copy icon copies the entire value to the clipboard.<br>Displays a temporary confirmation toast (“Copied!”).<br>Confirmation disappears automatically after a short duration. | If copy action fails (e.g., browser restriction or clipboard error), show inline feedback such as “Copy failed. Try again.”<br>Do not modify or remove text after failure.<br>Ensure retry behaviour remains accessible and non&hyphen;blocking. |  


# CONTENT GUIDELINES

- Labels should describe the content type clearly (e.g., “Referral Code,” “Link,” “Tracking ID”).  Keep labels concise and consistent with page context.

- Text within the field should be static and visible, truncated with ellipsis if necessary.  Feedback messages should be brief and positive (e.g., “Copied!”, “Try again”).  

- No placeholder text, as the field always displays content by default.