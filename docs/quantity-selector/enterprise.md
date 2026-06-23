
# Enterprise

---

# **USAGE GUIDELINES**

- Step controls for quick adjustments, allowing users to increment or decrement values without typing

- Allow manual input when precision or larger jumps are needed, enabling users to enter a value directly.

- Define a clear step value appropriate to the use case (e.g., +1 for items, +10 or +100 for bulk quantities).

- Start with a valid default, usually the minimum allowed quantity.

- Label and hint text are optional. Place the selector close to the object it controls to maintain clear context (e.g., next to the item name or price).

- Use ‘**md’** size for mobile view; ‘**lg’ **size for desktop view.

## **States**

  
**Placeholder**  
  
  
**Focused**  
  
  
**Filled**  
  
  
  
**Error**  
  
  
**Error Focused**  
  
  
**Disabled**  
  


---

# **BEHAVIOUR (INTERACTIONS)**

  
| Column 1 | Column 2 | Column 3 | Column 4 | Column 5 |  
| --- | --- | --- | --- | --- |  
| Increment | Decrement | Manual Entry | Range Constraints | Validation & Feedback |  
| Clicking the + button increases the quantity by the defined step (e.g., +1, +10, or +100).<br>If the updated value reaches the maximum limit, the + button becomes disabled. | Clicking the − button decreases the quantity by the defined step (e.g., −1, −10, or −100).<br>If the updated value reaches the minimum limit, the − button becomes disabled. | Users can type a value directly into the input field.<br>The entered value must: 
&hyphen; Be a valid numeric format.
&hyphen; Fall within the defined range. | Minimum quantity: 1

Maximum quantity: 9999 | If a manually entered value exceeds the limits, the component should correct it to the nearest valid value or display validation feedback. |  
