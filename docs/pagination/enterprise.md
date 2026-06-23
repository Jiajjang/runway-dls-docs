
# Enterprise

---

# USAGE GUIDELINES

- Always provide clear navigation controls for multi&hyphen;page data sets.

- Use simplified pagination (e.g., Previous / Next or Page X of Y) when space is limited or when sequential navigation is expected.

- Choose a pagination variant based on whether users need sequential navigation or direct access to specific pages.

**Result Summary:**

- Display “X–Y of Z results” to provide context for the current page.

- The summary may appear above pagination or placed separately if layout requires it.

**Items Per Page:**

- Use the label “Items per page”.

- Typical options: 10, 20, 50, 100.

- The Items per page selector may appear independently from pagination controls when necessary.

**Optional Controls:**

- Include First and Last buttons when datasets contain many pages (e.g., more than 10).

- Disable unavailable controls:

**Page Count Logic:**

- Use “Page X of Y” when:

### Pages

  
**Words**  
Displays the user’s position using “Page X of Y” together with controls.
Includes:  
- Previous / Next controls  
- Page X of Y indicator  
Optional elements:  
- Items per page selector  
- Result summary (e.g., 1–20 of 200)  
- First / Last controls  
Use when users primarily navigate pages sequentially.  
  
**Images**  
  


### Numbering

  
**Words**  
Displays individual page numbers in a single line with controls. Supports ellipsis for large page sets.  
Includes:  
- Previous / Next controls  
- Individual page numbers  
Optional elements:  
- Items per page selector  
- Result summary (e.g., 1–20 of 200)  
- First / Last controls  
Use when users need to jump directly to specific pages, such as in tables or search results.  
  
**Images**  
  


### **Pages Only**

  
**Words**  
Displays only “Page X of Y”.
Does not include:  
- Items per page selector  
- Result summary  
Use for sequential browsing in tight toolbars/headers where direct jumps aren’t needed. Pair with a separate results summary elsewhere if users still need context.  
  
**Images**  
  


### Numbering Only

  
**Words**  
Displays only individual page numbers.
Does not include:  
- Items per page selector  
- Result summary  
Use for sequential browsing in tight toolbars/headers where users must jump to specific pages. Pair with a separate results summary elsewhere if users still need context.  
  
**Images**  
  


### Items Per Page + Total Items Only

  
**Words**  
Allow users to change page size and see totals.  
Displays:  
- Items per page selector  
- Result summary (A–B of Z)  
Does not include navigation controls.
Use when navigation is handled elsewhere (e.g., infinite scrolling or auto&hyphen;loading).  
  
**Images**  
  


### **Previous + Next Buttons Only**

  
**Words**  
Displays only Previous and Next controls.
Use when:  
- Navigation is strictly sequential  
- The number of pages is small  
- Pagination must remain minimal  
  
**Images**  
  


---

# BEHAVIOUR & INTERACTION

  
| Column 1 | Column 2 | Column 3 | Column 4 |  
| --- | --- | --- | --- |  
| Controls | Ellipsis Usage | Mobile Behaviour | Desktop Behaviour |  
| First/Last controls show when total pages > 7<br>Disable Prev/First controls on page 1 and Next/Last controls on the last page. | Use ellipses when the number of pages is too large to display fully.<br>Place ellipses where page ranges are omitted.<br>Avoid placing ellipses directly next to the active page. | Limit the number of visible page numbers to preserve space.<br>Show the first page, last page, and pages near the current page.<br>Use ellipses to represent hidden page ranges. | Display more page numbers when space allows.<br>Use ellipses to collapse long ranges while keeping the first and last pages visible. |  


- Previous and First on the first page

- Next and Last on the last page.

- Screen space is limited, or

- The total number of pages is very large.