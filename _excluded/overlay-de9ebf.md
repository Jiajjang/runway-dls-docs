
# Actions & Interactions — Overlay

**Category:** Components

# USAGE GUIDELINES

- Use overlays when displaying **modal or blocking UI layers** that require user focus.

- Overlays should **prevent interaction with background content** while active.

- Ensure the foreground component remains clearly visible and visually dominant.

- Use consistent overlay opacity levels across the product to maintain predictable UI behavior.

- Avoid overly dark overlays that obscure all background context unless required for critical interactions.

# BEHAVIOUR (INTERACTIONS)

  

### Activation
- Overlay appears when a foreground component (e.g., modal or drawer) is triggered.
- It covers the entire viewport behind the active component.

### Interaction Blocking
- Prevents interaction with underlying UI elements.
- User focus should remain within the active foreground component.

### Dismissal
- Depending on product context, interacting with the overlay may:
- - Close the foreground component, or
- - Do nothing if the interaction must be explicitly confirmed.

### Layering
- Overlay sits above the base interface but below the active foreground component.
- Ensure proper layering order so the overlay does not block the foreground element.