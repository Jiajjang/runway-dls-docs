
# Enterprise

---

# USAGE GUIDELINES

- Use when users need to input multiple discrete values (e.g., categories, skills, keywords).

- Support both free text inputs and suggestions from a dropdown list.

- Each input is a removable tag within the field.

- Prevent duplicate tags entries.

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

  
| Column 1 | Column 2 | Column 3 | Column 4 |  
| --- | --- | --- | --- |  
| Tag Addition | Tag Removal | Input Handling | Validation & Errors |  
| Users can type and press Enter or Comma to add tags. <br>Dropdown suggestions can be selected using arrow keys or mouse (if available).<br>Prevent duplicate tag creation.<br> | Tags can be removed via (×) icon or Backspace to delete the last tag sequentially.<br>“Clear all” action removes all tags at once (if implemented). | Field grows horizontally and wraps tags to next line when full.<br>Cursor stays after the last tag for continuous input.<br>Respects maximum input width and truncates overflow gracefully. | Supports field&hyphen;level and tag&hyphen;level validation.<br>Invalid tags show individually with error styling. <br>Inline message appears for generic field errors (e.g., “Some tags are not allowed”).<br>Errors disappear after correction. |  


# CONTENT GUIDELINES

- Use simple, recognisable labels for tags (e.g. "Design", "Analytics", "Security").

- Keep placeholder text instructional but short (e.g. "Add a category").

- Prevent empty or invalid tags where applicable.

- Use sentence case for consistency.