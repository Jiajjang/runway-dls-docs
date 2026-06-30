
# Text Area — Enterprise

**Category:** Inputs

# USAGE GUIDELINES

- Use when multiple lines of text input are expected (e.g. comments, notes).

- Always include a clear, visible label above the field.

- Add hint text to guide input expectations.

- Avoid for short inputs — use Text Field instead.

- Support character counters when applicable (optional).

- Counter is usually aligned bottom-right.

- Use ‘**md’** size for mobile view; ‘**lg’ **size for desktop view.
# CONTENT GUIDELINES

- Labels should reflect purpose (e.g. “Comments”, “Feedback”).

- Hint text should explain expected content (e.g. “Tell us more about your experience.”)

- Character counter text should be short and consistent (e.g. “140/150 characters left”).
# BEHAVIOUR (INTERACTIONS)

  

### Focus & Input
- Field receives visual focus when active.
- Cursor appears at correct insertion point.
- Supports multi-line entry with line breaks.

### Character Counter
- Shows remaining or used characters.
- Updates dynamically as user types.
- Can be:
- - Soft Limit: Allows input beyond max with a warning.
- - Hard Limit: Prevents typing once limit is reached.

### Validation & Error Handling
- Validates on blur or submit (especially if character limit applies).
- Shows inline messages (e.g. “Please limit input to 150 characters.”).
- Clears error once valid input is entered.

### Mobile Behaviour
- Opens multi-line keyboard on tap.
- Expands field height dynamically.
- Ensures tap targets are sufficiently large.