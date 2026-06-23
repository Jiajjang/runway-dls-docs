
# Enterprise

---

# USAGE GUIDELINES

- Display card brand logo (e.g., Mastercard, Visa) based on user input or pre&hyphen;selection

- Space the number for better legibility: xxxx xxxx xxxx xxxx

- Accept numeric input only (16–19 digits depending on card type)

- Mask or partially obfuscate on blur (if security requires)

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

  
| Column 1 | Column 2 | Column 3 |  
| --- | --- | --- |  
| Formatting | Validation | Credit Card Brand |  
| Auto&hyphen;inserts space every 4 digit<br>Restricts non&hyphen;numeric characters<br>Shows visual confirmation (logo) when card type is recognized (e.g., starts with 5 → Mastercard) | Accepts 16&hyphen;digit card number (or valid range per card type)<br>Optional: Luhn check for client&hyphen;side validation<br>Error shown if incomplete or invalid pattern entered | The credit card logo is automatically detected based on the card number prefix, while a default credit card icon is shown as the placeholder. |  


# CONTENT GUIDELINES

- Label clearly states purpose (e.g., “Price”, “Total Fee”).

- Helper text can reinforce correct input: "Enter amount in SGD" or "Values will auto&hyphen;format to two decimals".