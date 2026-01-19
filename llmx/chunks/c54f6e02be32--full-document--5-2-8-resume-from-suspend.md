---
chunk_index: 308
ref: "c54f6e02be32"
id: "c54f6e02be328a45992e2a75a5b54714a2df728eecdc01332e6d26f50ddbd184"
slug: "full-document--5-2-8-resume-from-suspend"
path: "marker/1983 Lisa UI Guidelines/full_document.md"
kind: "markdown"
lines: [311, 320]
token_estimate: 308
content_sha256: "bcb95097752a092993011ea671ebcd0724bb2b90cccefbc5941427af6102877b"
compacted: false
heading_path: ["Chapter 5 Desktop Manager","5.2.8 Resume from suspend"]
symbol: null
address: null
asset_path: null
---

## 5.2.8 Resume from suspend

when the user powers on the Lisa after a suspend, or reinserts the disk whose ejection caused the suspend, the Desktop Manager restores the screen to the way it was when the documents were suspended, except that no information is shown in the windows. Instead, in each window, a message appears telling the user to click in the window if he wants to see the document.

The window that was active when the Lisa was suspended is shown with an active title bar, but its menus are not in the menu bar. It has an active size control, but the rest of its scroll bars are shown in gray with no active elements [this is also a change].

If the user clicks in the scroll bars or title bar of a suspended window, rather than in the window itself, then its document becomes the active document. The user can resize or move it, but its contents are not displayed until the user clicks in the main part of the window. At that time, the document should appear exactly the same way it did when it was suspended.

Details: If, instead of clicking in a suspended document, the user requests that it be put away, the document is put away by the Desktop Hanager, not by the application, and is therefore still suspended.