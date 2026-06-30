
# Coachmark — Enterprise

**Category:** Actions & Interactions

# USAGE GUIDELINES

- Use coachmarks to introduce first-time features, onboarding steps, or major updates.

- Use sparingly — only when guidance is necessary.

- Must anchor to a specific UI element using a pointer.

- Should capture attention without blocking critical content.

- Always dismissible through a clear button (“Got it”, “Next”) or performing the guided action.

- Use Light or Dark theme based on contrast needs or background complexity.

- Suitable for multi-step flows when onboarding users through several elements.

- Avoid showing multiple coachmarks at once; present them sequentially.
# CONTENT GUIDELINES

- Up to 5 lines (&tilde;200 characters).

- Keep copy friendly, clear, and action-oriented.

- Use verbs (“Tap here to…”, “This button lets you…”).

- Avoid long paragraphs or technical terminology.
# BEHAVIOUR (INTERACTIONS)

  

### Trigger
- Automatically appears when a triggering condition is met (e.g., first-time login, new feature available).
- Can also be manually triggered via “Show tips” or help modes.

### Placement
- Anchored to the relevant UI element.
- Repositions automatically to avoid blocking content.
- Supports all arrow directions (top/bottom/left/right and corner positions) depending on space — treated as behaviour, not variants.

### Dismissal
- User must dismiss through:
- - “Got it”
- - “Next” (multi-step flows)
- - Completing the guided action
- - Optional close (×)
- - May allow tap-away depending on use case.

### Sequence
- Supports multi-step walkthroughs.
- User progresses step-by-step (e.g., Step 1/3).

### Visual Emphasis
- Background may dim using an overlay to draw focus.
- Coachmark card remains the highest emphasis layer.