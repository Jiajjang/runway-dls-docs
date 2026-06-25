
# Enterprise

# USAGE GUIDELINES

- Use when users need to attach or submit one or more files.

- Always include helper text specifying allowed file types and size limits.

- Clearly distinguish upload states (uploading, success, cancelled, error).

- Provide clear recovery CTA to aid users (e.g., Retry, Remove).

- For drag-and-drop mode, show a 1px brand border (&num;7A35B0) on hover to indicate an active drop zone.

# BEHAVIOUR (INTERACTIONS)

  

### Core Interactions
- Click: Opens native file picker.
- Drag & Drop (Desktop): Activates drop zone on hover.
- Cancel: Stops upload in progress.
- Retry: Re-initiates upload (unlimited attempts unless restricted by product).

### Validation Logic
- File type and size restrictions are product-defined.
- Invalid files are rejected before upload begins (if validated client-side).
- Duplicate filenames may be allowed unless otherwise specified.

### Validation & Error Handling
- Progress reflects actual upload status (not simulated).
- Error messages may be returned by backend.
- No preview or download support after upload (if not implemented in product).

