---
chunk_index: 4040
ref: "143905ee9e58"
id: "143905ee9e5821a981a53557e5159da607dd480a569d8451645cd04724605b73"
slug: "full-document--application-deactivation"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1315, 1329]
token_estimate: 302
content_sha256: "612f5a24bc991bd898d9571e3d9e8e354a6ef7055e0acdee2ecc81e36f078755"
compacted: false
heading_path: ["The Window Interface to Applications","**The Active Application**","**Application Activation**","**Application Deactivation**"]
symbol: null
address: null
asset_path: null
---

#### **Application Deactivation**

There can be only one active application per workspace (that is, one per Window Server) at a time. Whenever the user chooses a new active application, the previous one is automatically deactivated. The Application Kit and Workspace Manager take care of this task.

The active application is also deactivated when:

- The user hides its windows (by using the Hide command).
- The user terminates it (by choosing the Quit command).

In either case, if another application has panels or standard windows on-screen, then the Workspace Manager activates the application with the frontmost panel or window. If no other applications have panels or standard windows on-screen, then no application becomes active.

In addition, an application should deactivate itself just before sending a message to another application, if the intent of the message is to have the other application become active. (See "Activating an Application" later in this chapter for details.)

**Note:** A deactivated but running application can still do work. It's "deactivated" only in the sense that it no longer is the active application, so the user can't interact with it without activating it again.