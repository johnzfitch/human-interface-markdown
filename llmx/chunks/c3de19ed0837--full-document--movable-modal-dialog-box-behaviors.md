---
chunk_index: 2774
ref: "c3de19ed0837"
id: "c3de19ed08374cf7e776894ad3ba0d047a38a9fb3ec99fe67a099d7c3372e536"
slug: "full-document--movable-modal-dialog-box-behaviors"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [2975, 2984]
token_estimate: 238
content_sha256: "8d13b558e6559688b4f7cc68d2072dd5c93e3c82283b0fdd823709c69a27d077"
compacted: false
heading_path: ["Movable Modal Dialog Boxes","Movable Modal Dialog Box Behaviors"]
symbol: null
address: null
asset_path: null
---

## Movable Modal Dialog Box Behaviors

Movable modal dialog boxes should respond like modal dialog boxes in most ways. (See the section "Modal Dialog Boxes" on page 188 for a discussion of modal dialog boxes.) You must make certain that the dialog box is modal within your application. That is, the user should not be able to switch to another of your application's windows while the dialog box is active.

For movable modal dialog boxes, there are certain behaviors you need to support. Allow your application to run in the background when you display a movable modal dialog box. For example, System 7 uses movable modal dialog boxes to show that an application is busy with a time-consuming operation, yet a user can still switch the application to the background. Figure 6-10 shows a movable modal dialog box displayed by the Finder when it is copying files.

**Figure 6-10** A Finder movable modal dialog box

![](images/_page_210_Picture_8.jpeg)