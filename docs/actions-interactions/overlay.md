
# Overlay

A background overlay dims underlying content 
to focus attention on an active foreground component 
and prevent interaction with the background.

---

# USAGE GUIDELINES

- Use overlays when displaying **modal or blocking UI layers** that require user focus.

- Overlays should **prevent interaction with background content** while active.

- Ensure the foreground component remains clearly visible and visually dominant.

- Use consistent overlay opacity levels across the product to maintain predictable UI behavior.

- Avoid overly dark overlays that obscure all background context unless required for critical interactions.

## Variants

  
**Black Opacity**  
  
- The most common overlay style.  
- Applies a semi&hyphen;transparent black layer to dim background content.  
- Recommended for modals, dialogs, and blocking interactions.  
  
**Gradient Opacity**  
  
- Uses a gradient fade to partially dim the background.  
- Useful when maintaining some visual context of underlying content is desirable.  
  
**White Opacity**  
  
- Applies a light overlay over the interface.  
- Often used in light&hyphen;themed environments or subtle focus states.  


## States 

  
**Blurred**  
  
- Applies a background blur effect beneath the overlay.  
- Creates stronger visual separation between foreground and background.  
- Best used in high&hyphen;emphasis UI layers such as full modals.  
  
**Not Blurred**  
  
- Applies a background blur effect beneath the overlay.  
- Creates stronger visual separation between foreground and background.  
- Best used in high&hyphen;emphasis UI layers such as full modals.  


---

# BEHAVIOUR (INTERACTIONS)

  
| Column 1 | Column 2 | Column 3 | Column 4 |  
| --- | --- | --- | --- |  
| Activation | Interaction Blocking | Dismissal | Layering |  
| Overlay appears when a foreground component (e.g., modal or drawer) is triggered.<br>It covers the entire viewport behind the active component. | Prevents interaction with underlying UI elements.<br>User focus should remain within the active foreground component. | Depending on product context, interacting with the overlay may:<br>&hyphen; Close the foreground component, or<br>&hyphen; Do nothing if the interaction must be explicitly confirmed. | Overlay sits above the base interface but below the active foreground component.<br>Ensure proper layering order so the overlay does not block the foreground element. |  
