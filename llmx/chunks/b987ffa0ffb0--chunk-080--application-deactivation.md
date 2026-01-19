---
chunk_index: 3673
ref: "b987ffa0ffb0"
id: "b987ffa0ffb080d7afbd6d95ad7d8c4c7630b8d50ef785fada51b6878ce023eb"
slug: "chunk-080--application-deactivation"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_080.md"
kind: "markdown"
lines: [17, 24]
token_estimate: 304
content_sha256: "f8ac53abf279fe7b57d205d263ca4fc19eb116077524bd0a57d8e584ac791cd1"
compacted: false
heading_path: ["**Application Activation**","**Application Deactivation**"]
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