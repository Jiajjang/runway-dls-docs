
# Search — Enterprise

**Category:** Inputs

# USAGE GUIDELINES

- Use for any input that involves search, filter, or lookup actions.

- Always include a visible label unless used in tight spaces (e.g. isolated search bars).

- Leading search icon reinforces intent; trailing clear (×) icon appears after text entry.

- Input should remain single-line, fast, and responsive.

- Avoid multiline content or long responses.

- Disable when search is unavailable or not applicable.

- Use ‘**md’** size for mobile view; ‘**lg’ **size for desktop view.
# CONTENT GUIDELINES

- Placeholder text should clearly hint at purpose (e.g. “Search item or keyword”).

- Error messages should be brief and action-oriented (e.g. “Please enter a valid query”).
# BEHAVIOUR (INTERACTIONS)

  

### Input Handling
- Accepts free-form single-line input.
- Search icon is always visible on the left.
- Clear icon (×) appears when input is detected.
- Pressing the clear icon resets the field instantly.

### Search Trigger
- Triggered via:
- - Hitting Enter
- - Stopping typing (debounce)
- - Tapping a Search buttor
- - or live search based on user input (if supported by product context)

### Validation & Error Handling
- Typically rare; shown as inline message only when needed (e.g. “No special characters allowed”).
- Errors clear automatically upon valid input.

### Clear Action
- Tapping the clear icon removes all text.
- Field remains focused for immediate retry (recommended).