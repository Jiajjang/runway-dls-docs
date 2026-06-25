
# Enterprise

# USAGE GUIDELINES

- Use when visual date selection improves accuracy or speed over manual entry.

- Triggered by interaction with a [Date Input](#) or suffix icon.

- Keep date format consistent across all products and regions.

- Disable unavailable or past dates where relevant.

- Support both single-date and date-range selection as required.

- Provide inline validation for incomplete or invalid selections.

- Include contextual hints such as “Select departure date.”
# CONTENT GUIDELINES

- Labels should describe the date’s purpose clearly, such as “Departure Date,” “Date of Birth,” or “Booking Period.”  Keep the label short and consistent across similar forms.

- Error messages should clearly state what went wrong, such as “Please select a valid date” or “End date cannot be before start date.”

- Maintain a consistent date format throughout a user journey to reduce confusion, and avoid using multiple styles (e.g., mixing numeric and text-based month formats).
# BEHAVIOUR (INTERACTIONS)

  

### Opening & Closing
- Opens when the Date Input Field or calendar icon is clicked or tapped.
- Closes automatically after selection (single date) or on “Apply” for date ranges.
- “Cancel” or tapping outside closes without saving changes.

### Navigation
- Navigate between months using chevrons or arrows.
- Month and year accessible through dropdowns or tap on header.
- Scrollable variant allows continuous vertical browsing across months.

### Selection
- Clicking a day selects that date (single mode) or start/end (range mode).
- Selected dates are visually highlighted.
- Displays full date or range in linked input field automatically.

### Validation & Error Handling
- Restricts selection outside of defined minimum/maximum date range.
- Displays inline feedback for invalid entries
- - “Please select a valid date.”
- - “End date cannot be before start date.”
- Clears error automatically upon valid correction.

