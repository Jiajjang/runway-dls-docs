
# Enterprise

---

# USAGE GUIDELINES

- Use when visual date selection improves accuracy or speed over manual entry.

- Triggered by interaction with a [Date Input](#) or suffix icon.

- Keep date format consistent across all products and regions.

- Disable unavailable or past dates where relevant.

- Support both single&hyphen;date and date&hyphen;range selection as required.

- Provide inline validation for incomplete or invalid selections.

- Include contextual hints such as “Select departure date.”

## Variants

### Day Picker

  
**Description**  
- Allows selection of one specific date.  
- Day Picker is best used for selection of date within a month  
  
**Image**  
  


### Scrollable Date Picker

  
**Description**  
- Allows vertical scrolling across months  
- Choose to show Month/Year or Date/Month/Year  
- Scrollable Date is used for selection of dates within a year  
  
**Image**  
  


### Month & Year Picker (Single)

  
**Description**  
- Allows vertical scrolling across multiple months and specific years.  
- Displays months and years together for selection.  
- Used when users need to pick a specific month or year only.  
  
**Image**  
  


### Month & Year Picker (Double)

  
**Description**  
- Allows vertical scrolling across multiple months.   
- Shows two adjacent months and years simultaneously.   
- Ideal for date range selections spanning multiple months.  
  
**Image**  
  


### Date Range Picker

  
**Description**  
- Date Range is used for an even wider range selection  
  
**Image**  
  


---

# BEHAVIOUR (INTERACTIONS)

  
| Column 1 | Column 2 | Column 3 | Column 4 |  
| --- | --- | --- | --- |  
| Opening & Closing | Navigation | Selection | Validation & Error Handling |  
| Opens when the Date Input Field or calendar icon is clicked or tapped.<br>Closes automatically after selection (single date) or on “Apply” for date ranges.<br>“Cancel” or tapping outside closes without saving changes. | Navigate between months using chevrons or arrows.<br>Month and year accessible through dropdowns or tap on header.<br>Scrollable variant allows continuous vertical browsing across months. | Clicking a day selects that date (single mode) or start/end (range mode).<br>Selected dates are visually highlighted.<br>Displays full date or range in linked input field automatically. | Restricts selection outside of defined minimum/maximum date range.<br>Displays inline feedback for invalid entries<br>&hyphen; “Please select a valid date.”<br>&hyphen; “End date cannot be before start date.”<br>Clears error automatically upon valid correction. |  


# CONTENT GUIDELINES

- Labels should describe the date’s purpose clearly, such as “Departure Date,” “Date of Birth,” or “Booking Period.”  Keep the label short and consistent across similar forms.

- Error messages should clearly state what went wrong, such as “Please select a valid date” or “End date cannot be before start date.”

- Maintain a consistent date format throughout a user journey to reduce confusion, and avoid using multiple styles (e.g., mixing numeric and text&hyphen;based month formats).