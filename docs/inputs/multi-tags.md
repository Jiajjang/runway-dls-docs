
# Multi-tags — Enterprise

**Category:** Inputs

# USAGE GUIDELINES

- Use when users need to input multiple discrete values (e.g., categories, skills, keywords).

- Support both free text inputs and suggestions from a dropdown list.

- Each input is a removable tag within the field.

- Prevent duplicate tags entries.

- Use ‘**md’** size for mobile view; ‘**lg’ **size for desktop view.
# CONTENT GUIDELINES

- Use simple, recognisable labels for tags (e.g. "Design", "Analytics", "Security").

- Keep placeholder text instructional but short (e.g. "Add a category").

- Prevent empty or invalid tags where applicable.

- Use sentence case for consistency.
# BEHAVIOUR (INTERACTIONS)

  

### Tag Addition
- Users can type and press Enter or Comma to add tags.
- Dropdown suggestions can be selected using arrow keys or mouse (if available).
- Prevent duplicate tag creation.

### Tag Removal
- Tags can be removed via (×) icon or Backspace to delete the last tag sequentially.
- “Clear all” action removes all tags at once (if implemented).

### Input Handling
- Field grows horizontally and wraps tags to next line when full.
- Cursor stays after the last tag for continuous input.
- Respects maximum input width and truncates overflow gracefully.

### Validation & Errors
- Supports field-level and tag-level validation.
- Invalid tags show individually with error styling.
- Inline message appears for generic field errors (e.g., “Some tags are not allowed”).
- Errors disappear after correction.