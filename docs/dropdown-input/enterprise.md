
# Enterprise

---

# USAGE GUIDELINES

- Use when users must select from a fixed list rather than entering free text.

- When clicked, it opens up a [Dropdown Option](#).

- Keep the field label clear and consistent with surrounding form fields.

- Show placeholder text when no selection has been made.

- Display the selected option(s) clearly within the field.

- Use the chevron icon to indicate open/close state.

- Disable the field when selection is unavailable.

- Use multi&hyphen;select only when users must choose more than one value.

- Ensure field width accommodates long option labels without clipping.

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
| Input Handling | Opening & Closing | Selection & Display | Validation & Error Handling |  
| Field is non&hyphen;editable; typing does not modify the value.<br>Placeholder appears until user selects an option.<br>Supports single&hyphen;select or multi&hyphen;select depending on configuration. | Dropdown opens when user clicks or taps the field or chevron icon.<br>Dropdown closes on:<br> &hyphen; selecting an option (single&hyphen;select)<br> &hyphen; pressing Esc<br> &hyphen; clicking outside<br> &hyphen; tapping outside on mobile | Selected item replaces placeholder text.<br>Multi&hyphen;select values displayed as:<br> &hyphen; inline tags, or<br> &hyphen; a count summary (“3  selected”), depending on design.<br>Selected option remains highlighted in the menu when reopening.<br>Text truncates with ellipsis if too long for the field width. | Error state appears when the required selection is missing.<br>Field is outlined in red with message such as “Please select an option.<br>Error clears automatically upon valid selection.<br>Disabled state prevents interaction and hides any error. |  
