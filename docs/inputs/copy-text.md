
# Enterprise

# USAGE GUIDELINES

- Use when users need to copy static, non-editable text (e.g., referral code, URL, tracking number).

- Keep field content short and readable; truncate long text if necessary.

- Provide visual feedback when the text is successfully copied.

- Do not allow direct editing or selection of field content.

- Use ‘**md’** size for mobile view; ‘**lg’ **size for desktop view.
# CONTENT GUIDELINES

- Labels should describe the content type clearly (e.g., “Referral Code,” “Link,” “Tracking ID”).  Keep labels concise and consistent with page context.

- Text within the field should be static and visible, truncated with ellipsis if necessary.  Feedback messages should be brief and positive (e.g., “Copied!”, “Try again”).  

- No placeholder text, as the field always displays content by default.
# BEHAVIOUR (INTERACTIONS)

  

### Copy Action
- Clicking the copy icon copies the entire value to the clipboard.
- Displays a temporary confirmation toast (“Copied!”).
- Confirmation disappears automatically after a short duration.

### Validation & Error Handling
- If copy action fails (e.g., browser restriction or clipboard error), show inline feedback such as “Copy failed. Try again.”
- Do not modify or remove text after failure.
- Ensure retry behaviour remains accessible and non-blocking.

