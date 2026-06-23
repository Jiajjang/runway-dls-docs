
# Enterprise

---

# USAGE GUIDELINES

- Use when multiple lines of text input are expected (e.g. comments, notes).

- Always include a clear, visible label above the field.

- Add hint text to guide input expectations.

- Avoid for short inputs — use Text Field instead.

- Support character counters when applicable (optional).

- Counter is usually aligned bottom&hyphen;right.

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
| Focus & Input | Character Counter | Validation & Error Handling | Mobile Behaviour |  
| Field receives visual focus when active.<br>Cursor appears at correct insertion point.<br>Supports multi&hyphen;line entry with line breaks. | Shows remaining or used characters.<br>Updates dynamically as user types.<br>Can be:<br>&hyphen; Soft Limit: Allows input beyond max with a warning.<br>&hyphen; Hard Limit: Prevents typing once limit is reached. | Validates on blur or submit (especially if character limit applies).<br>Shows inline messages (e.g. “Please limit input to 150 characters.”).<br>Clears error once valid input is entered. | Opens multi&hyphen;line keyboard on tap.<br>Expands field height dynamically.<br>Ensures tap targets are sufficiently large. |  


# CONTENT GUIDELINES

- Labels should reflect purpose (e.g. “Comments”, “Feedback”).

- Hint text should explain expected content (e.g. “Tell us more about your experience.”)

- Character counter text should be short and consistent (e.g. “140/150 characters left”).