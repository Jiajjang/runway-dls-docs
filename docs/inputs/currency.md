
# Currency — Enterprise

**Category:** Inputs

# USAGE GUIDELINES

- Use for any form input requiring currency entry

- Keep the currency code visible at all times (e.g., SGD)

- Prefix the input with a currency symbol (e.g., $) for clarity

- Ensure numeric-only input and format with thousands separators

- Use ‘**md’** size for mobile view; ‘**lg’ **size for desktop view.
# CONTENT GUIDELINES

- Label clearly states purpose (e.g., “Price”, “Total Fee”).

- Helper text can reinforce correct input: "Enter amount in SGD" or "Values will auto-format to two decimals".

---
# BEHAVIOUR (INTERACTIONS)

  

### Formatting
- Inserts thousands separators automatically (e.g., 1000 → 1,000.00)
- Only allows numeric input and one decimal point
- Defaults to 2 decimal places

### Validation
- Triggers error state if left empty when require
- *Optional: *Enforce minimum or maximum allowed value

### Input Restrictions
- Prevents letters or symbols except for period (.)
- Mobile should invoke a numeric keypad

### Accessibility
- Currency code should be keyboard accessible if interactive
- Field should support aria-label and be screen reader friendly