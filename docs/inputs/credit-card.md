
# Enterprise

# USAGE GUIDELINES

- Display card brand logo (e.g., Mastercard, Visa) based on user input or pre-selection

- Space the number for better legibility: xxxx xxxx xxxx xxxx

- Accept numeric input only (16–19 digits depending on card type)

- Mask or partially obfuscate on blur (if security requires)

- Use ‘**md’** size for mobile view; ‘**lg’ **size for desktop view.
# CONTENT GUIDELINES

- Label clearly states purpose (e.g., “Price”, “Total Fee”).

- Helper text can reinforce correct input: "Enter amount in SGD" or "Values will auto-format to two decimals".
# BEHAVIOUR (INTERACTIONS)

  

### Formatting
- Auto-inserts space every 4 digit
- Restricts non-numeric characters
- Shows visual confirmation (logo) when card type is recognized (e.g., starts with 5 → Mastercard)

### Validation
- Accepts 16-digit card number (or valid range per card type)
- Optional: Luhn check for client-side validation
- Error shown if incomplete or invalid pattern entered

### Credit Card Brand
- The credit card logo is automatically detected based on the card number prefix, while a default credit card icon is shown as the placeholder.

