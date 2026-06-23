
# Enterprise

---

# USAGE GUIDELINES

- Use Filter Chips to allow users to quickly refine lists, search results, or displayed content

- Multiple filter chips may be selected simultaneously unless defined otherwise by product logic.

- Use the Applied state to clearly indicate when a filter is active.

- Include the “×” icon in the Applied state to allow users to remove the filter quickly.

- Place filter chips above or near the content they affect.

- Use Disabled state when a filter option is temporarily unavailable.

- Avoid mixing Pill and Rectangular styles within the same interface experience.

## Variants

**Filter** Chip: Used to toggle filters that narrow down displayed results.

**Category** Chip: Used to represent or select a content category or grouping.

  
**Outline Pill**  
  
- Outlined rounded chip used commonly in **consumer&hyphen;facing (B2C) interfaces**.  
- Provides a lightweight and friendly appearance.  
  
**Solid Pill**  
  
- Filled rounded chip used for **stronger emphasis in B2C interfaces**.  
- Useful when filters need higher visual prominence.  
  
**Outline Rect**  
  
- Outlined rectangular chip typically used in **B2B tools, dashboards, and operational interfaces**.  
- Provides a structured and utilitarian appearance.  
  
**Solid Rect**  
  
- Filled rectangular chip used when **higher visibility is required in B2B environments**, such as dashboards or dense admin interfaces.  


## States

  
**Default**  
  
- The chip is available but **no filter is applied**.  
- Use when the filter option is available for selection.  
  
**Default (Hover)**  
  
- The chip surface highlights to indicate it is **interactive**.  
- Use when the cursor hovers over a selectable chip.  
  
**Applied**  
  
- The filter is **currently active** and affecting the content.  
- **Characteristics: **Chip styling changes to indicate selection. Includes a **“×” icon** allowing the user to remove the filter  
- Use when a filter has been applied.  
  
**Applied (Hover)**  
  
- Indicates the chip is **interactive while active**.  
- Use when the cursor hovers over an applied chip, and helps signal the filter can be removed.  
  
**Disabled**  
  
- The chip is visible but **cannot be interacted with**.  
- Use when the filter option is unavailable due to system conditions, and is not applicable to the current dataset.  


---

# BEHAVIOUR (INTERACTIONS)

  
| Column 1 | Column 2 | Column 3 | Column 4 |  
| --- | --- | --- | --- |  
| Selection | Removal | Multiple Selection | Grouping |  
| Clicking a **Default chip** switches it to **Applied state**, activating the filter.<br>Clicking an **Applied chip** toggles it back to **Default**, removing the filter. | When in **Applied state**, a **“×” icon** appears allowing users to remove the filter directly.<br>Clicking the **“×” icon** removes the filter immediately. | Multiple filter chips may be applied simultaneously unless restricted by the product’s filtering logic. | Filter chips are typically displayed in **horizontal groups or rows above content lists or search results**. |  


---

# CONTENT GUIDELINES

- Labels should be **short and descriptive** (e.g., “Terminal 2”, “Dining”, “Promotions”).

- Use **sentence case** for chip labels

- Avoid long text that causes chips to wrap excessively.

- Maintain **consistent naming within the same filter group**.