
# Enterprise

---

# USAGE GUIDELINES

- Use for any input that involves search, filter, or lookup actions.

- Always include a visible label unless used in tight spaces (e.g. isolated search bars).

- Leading search icon reinforces intent; trailing clear (×) icon appears after text entry.

- Input should remain single&hyphen;line, fast, and responsive.

- Avoid multiline content or long responses.

- Disable when search is unavailable or not applicable.

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
| Input Handling | Search Trigger | Validation & Error Handling | Clear Action |  
| Accepts free&hyphen;form single&hyphen;line input.<br>Search icon is always visible on the left.<br>Clear icon (×) appears when input is detected.<br>Pressing the clear icon resets the field instantly. | Triggered via:<br>&hyphen; Hitting Enter<br>&hyphen; Stopping typing (debounce)<br>&hyphen; Tapping a Search buttor<br>&hyphen; or live search based on user input (if supported by product context) | Typically rare; shown as inline message only when needed (e.g. “No special characters allowed”).<br>Errors clear automatically upon valid input. | Tapping the clear icon removes all text.<br>Field remains focused for immediate retry (recommended). |  


# CONTENT GUIDELINES

- Placeholder text should clearly hint at purpose (e.g. “Search item or keyword”).

- Error messages should be brief and action&hyphen;oriented (e.g. “Please enter a valid query”).