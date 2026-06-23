
# Enterprise

---

# USAGE GUIDELINES

- Triggers when the user clicks on the [Dropdown Input ](../dropdown-input/enterprise.md)field.

- Use when users must choose from a predefined set of options.

- Keep option text short, clear, and consistent with user&hyphen;facing terminology.

- Show a maximum of 8 visible options before a scrollbar appears. Enable vertical scrolling when there are more than 8 options to prevent excessive height.

- Group related options logically to improve scan and selection.

- Maintain consistent spacing, font size, and selection indicators across variants.

- Avoid using more than one visual cue type (dot, icon, avatar) within the same list.

- When lists exceed 20 options, enable in&hyphen;menu search or filtering.

## Variants

### Basic Dropdown (Default)

  
**Description**  
- Single&hyphen;select list for simple options.   
- Expands on click or tap.   
- Collapses automatically when selection is made.  
  
**Image**  
  


### Multi&hyphen;Select Dropdown

  
**Description**  
• Allows multiple selections with checkboxes.   
• Displays selected items as tags or count summary.   
• Includes “Select All” and “Clear All” interactions if needed.  
  
**Image**  
  


### Dot Leading Dropdown

  
**Description**  
-  Each option shows a colored dot on the left.  
- Indicates categories or statuses visually.  
- Ideal for labeled statuses (e.g., Available, In Progress).  
  
**Image**  
  


### Icon Leading Dropdown

  
**Description**  
- Each option includes an icon before text.   
- Aids quick recognition and improves scannability.   
- Icons maintain consistent sizing and alignment.  
  
**Image**  
  


### Avatar Leading Dropdown

  
**Description**  
• Displays avatars or profile images beside labels.   
• Suitable for selecting users or accounts.   
• Supports secondary text (e.g., role or username).  
  
**Image**  
  


### Dropdown with Subtext

  
**Description**  
•Shows primary label with smaller subtext below.   
• Useful for secondary details like descriptions, metadata or shortcut keys.  
  
**Image**  
  


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
| Opening & Selection | Scrolling & Overflow | Grouping | Validation & Error Handling |  
| Click, tap, or press Enter to select an option.<br>Single&hyphen;select lists close immediately after selection.<br>Multi&hyphen;select lists remain open until user manually closes or confirms.<br>Selected options update the linked Dropdown Input Field. | Dropdown displays up to 8 visible items before scroll is enabled.<br>Scrollbar appears automatically when more than 8 options exist.<br>Scrollbar height scales dynamically based on container height.<br>When over 20 options, in&hyphen;list search or filtering should be implemented.<br>Keyboard scroll (Arrow Up/Down) navigates seamlessly between visible and hidden options. | Headers visually distinct with bold or smaller caps style.<br>Group headers remain visible when scrolling.<br>Groups are non&hyphen;selectable and act as visual dividers only. | Disabled options are skipped during keyboard navigation.<br>Parent Dropdown Input Field displays error if required selection is missing (“Please select an option”).<br>Errors clear automatically upon valid selection. |  
