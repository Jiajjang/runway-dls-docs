
# Enterprise

---

# USAGE GUIDELINES

- Use when users need to attach or submit one or more files.

- Always include helper text specifying allowed file types and size limits.

- Clearly distinguish upload states (uploading, success, cancelled, error).

- Provide clear recovery CTA to aid users (e.g., Retry, Remove).

- For drag&hyphen;and&hyphen;drop mode, show a 1px brand border (&num;7A35B0) on hover to indicate an active drop zone.

## Variants

  
**Desktop**  
  
- Optimised for wider screens with horizontal layout.  
- Supports drag&hyphen;and&hyphen;drop interaction.  
- Suitable for document&hyphen;heavy workflows.  
  
**Mobile**  
  
- Optimised for smaller viewports with stacked layout.  
- Drag&hyphen;and&hyphen;drop may not be supported depending on platform.  
- Uses tap&hyphen;to&hyphen;upload as primary interaction.  


## States &hyphen; File Upload Base

  
**Default**  
![Img](https://studio-assets.supernova.io/design-systems/570165/56290d35-b794-4184-be83-fccd1275dce2.png)  
- Initial state when no files are uploaded.  
- Field is active and displays upload instructions.  
- Users can click to upload or drag files into the drop zone.  
  
**Hover**  
![Img](https://studio-assets.supernova.io/design-systems/570165/f6d2f420-ab9b-4d45-8c74-d67e235361cf.png)  
- Indicates drop zone is active.  
- Shows brand border (&num;7A35B0).  
- Optional visual cue when file is dragged over drop zone.  
  
**Disabled**  
![Img](https://studio-assets.supernova.io/design-systems/570165/6748c1eb-71fe-4441-88b6-d5d8901a787a.png)  
- Entire field appears inactive.  
- Prevents clicking or dragging files.  
- Used when upload is unavailable (e.g., read&hyphen;only mode, locked step).  


## States &hyphen; File Upload Items

  
**Uploading**  
![Img](https://studio-assets.supernova.io/design-systems/570165/a49619ab-bcd3-4670-bb8b-6ba967f6d521.png)  
- Shows real&hyphen;time progress (spinner + percentage).  
- Cancel action available while uploading (if supported).  
  
**Success**  
![Img](https://studio-assets.supernova.io/design-systems/570165/68506ea1-12a7-495b-9b88-aa847fe52b40.png)  
- Displays success icon and confirmation message.  
- User may remove the file if needed.  
  
**Cancelled**  
![Img](https://studio-assets.supernova.io/design-systems/570165/257bb588-2b3f-4f6f-8b9a-fc069b813c13.png)  
- Displays cancelled status.  
- User may retry upload or remove the file.  
  
**Error**  
![Img](https://studio-assets.supernova.io/design-systems/570165/b3f6e2e6-f5fc-4dfe-9f34-c9a1c9a9113a.png)  
- Displays error icon and message.  
- Backend&hyphen;provided error reason shown when available.  
- User may retry or remove the file.  


---

# BEHAVIOUR (INTERACTIONS)

  
| Column 1 | Column 2 | Column 3 |  
| --- | --- | --- |  
| Core Interactions | Validation Logic | Validation & Error Handling |  
| Click: Opens native file picker.<br>Drag & Drop (Desktop): Activates drop zone on hover.<br>Cancel: Stops upload in progress.<br>Retry: Re&hyphen;initiates upload (unlimited attempts unless restricted by product). | File type and size restrictions are product&hyphen;defined.<br>Invalid files are rejected before upload begins (if validated client&hyphen;side).<br>Duplicate filenames may be allowed unless otherwise specified. | Progress reflects actual upload status (not simulated).<br>Error messages may be returned by backend.<br>No preview or download support after upload (if not implemented in product). |  


# CONTENT GUIDELINE

- Instruction text should be concise (e.g., “Click to upload or drag and drop”).

- File constraints should be clearly formatted (e.g., “Max 25MB · SVG, PNG, JPG”).

- Error messages should be clear and actionable (e.g., “File exceeds 25MB limit”).

- Avoid technical wording in user&hyphen;facing messages.