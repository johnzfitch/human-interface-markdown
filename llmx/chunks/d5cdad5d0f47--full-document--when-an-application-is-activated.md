---
chunk_index: 4045
ref: "d5cdad5d0f47"
id: "d5cdad5d0f47e375a36eac9a530f4e9201bc1e6c22babbfcd5cff3959483a137"
slug: "full-document--when-an-application-is-activated"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1379, 1389]
token_estimate: 353
content_sha256: "d62add1d8ff2e4c452ec8a713341735fef6052eb2f05131a183ecc6d90143877"
compacted: false
heading_path: ["The Window Interface to Applications","**How Windows Become the Key Window and Main Window**","**In the Active Application**","**When an Application Is Activated**"]
symbol: null
address: null
asset_path: null
---

#### **When an Application Is Activated**

When an application is activated, one of its windows is made the key window and one (usually the same one) is made the main window. Again, whenever possible, the user makes the selection:

- If the user activates the application by clicking in a window that accepts keystrokes, it becomes the key window. If the window is a standard window, it's also made the main window.
- If the user activates the application by double-clicking a miniwindow, the window it represents again appears on-screen and becomes the key window and main window.

If an application is activated without the user directly selecting a new key window, the user's previous selections are honored. For example, if the user reactivates an application by double-clicking its icon, the previous key window and main window are restored.

**Note:** When a new application is activated, its key window may be highlighted before the former key window (in the deactivated application) loses its highlighting. This is a consequence of a multitasking environment. Users can begin working in one process (the new active application) before their instructions to another process (the previous active application) have been completed. Although the former key window may retain its highlighting for a short time, it's no longer the key window; all keyboard actions are associated with the new active application.