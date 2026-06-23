
# Enterprise

---

# USAGE GUIDELINES

- Use for any form input requiring currency entry

- Keep the currency code visible at all times (e.g., SGD)

- Prefix the input with a currency symbol (e.g., $) for clarity

- Ensure numeric&hyphen;only input and format with thousands separators

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
| Formatting | Validation | Input Restrictions | Accessibility |  
| Inserts thousands separators automatically (e.g., 1000 → 1,000.00)<br>Only allows numeric input and one decimal point<br>Defaults to 2 decimal places | Triggers error state if left empty when require<br>*Optional: *Enforce minimum or maximum allowed value | Prevents letters or symbols except for period (.)<br>Mobile should invoke a numeric keypad | Currency code should be keyboard accessible if interactive<br>Field should support aria&hyphen;label and be screen reader friendly |  


# CONTENT GUIDELINES

- Label clearly states purpose (e.g., “Price”, “Total Fee”).

- Helper text can reinforce correct input: "Enter amount in SGD" or "Values will auto&hyphen;format to two decimals".

---