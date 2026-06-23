
# Enterprise

---

# USAGE GUIDELINES

- Triggered only through the [Time Input](#) field.

- Displays hour and minute columns with snapping intervals.

- Support configurable minute intervals (e.g., 1, 15, 30, or 60 minutes).

- Disable unavailable or out&hyphen;of&hyphen;range time slots.

- May auto&hyphen;confirm on selection or require explicit confirmation (e.g., “Done”).

- Always return time in a consistent format (e.g., **HH : MM**).

## Variants

  
**1 Min**  
  
- 1&hyphen;minute increments.  
- Used for highly time&hyphen;sensitive scenarios.  
  
**5 Min**  
  
- Standard interval for general scheduling.  
- Recommended default for most use cases.  
  
**10 Min**  
  
- Faster selection with fewer options.  
- Suitable for simplified workflows.  
  
**15 Min**  
  
- Balanced option for appointments and bookings.  
- Four selectable options per hour.  
  
**30 Min**  
  
- Two options per hour.  
- Ideal for block&hyphen;based scheduling.  
  
**60 Min**  
  
- One option per hour.  
- Suitable for hourly estimations or coarse selection.  


---

# BEHAVIOUR (INTERACTIONS)

  
| Column 1 | Column 2 | Column 3 | Column 4 |  
| --- | --- | --- | --- |  
| Opening & Closing | Scrolling & Snapping | Selection | Validation & Error Handling |  
| Opens when Time Input is clicked or tapped.<br>Closes when:<br>&hyphen; User selects a time (auto&hyphen;confirm mode),<br>&hyphen; User taps outside,<br>&hyphen; User taps “Done” or “Close” (if applicable). | Hours and minutes scroll independently.<br>Options snap into a centered selection slot.<br>Active selection is visually highlighted. | Final value = selected hour + selected minute.<br>Selected time is returned to the Time Input immediately.<br>If user cancels, previously selected value remains unchanged. | Disabled or restricted time slots cannot be selected.<br>If business logic invalidates a time (e.g., blocked window),Time Input shows error state (e.g., *“This timing is invalid.”*).<br>Errors are cleared automatically after choosing a valid time. |  
