---
chunk_index: 4039
ref: "7a8664d83dd3"
id: "7a8664d83dd34a5f8a2b4b6951ff66421e00eeeae8d2d0b2c2a14a2c554c09c2"
slug: "full-document--application-activation"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1300, 1314]
token_estimate: 420
content_sha256: "769fe6f5e9e2a663bd1c6707ef0f16614810edb7a46586841769701597ad3560"
compacted: false
heading_path: ["The Window Interface to Applications","**The Active Application**","**Application Activation**"]
symbol: null
address: null
asset_path: null
---

#### **Application Activation**

In general, the task of selecting the active application is left to the user. With one exception, an application never becomes active unless the user does something to activate it. The user's action can be direct, such as starting up the application or clicking in one of its windows, or indirect, such as having one application send a message to another application.

The exception is that when the user hides or terminates an application, the system guesses which application should be activated next (based on which applications have on-screen windows, as described below). This method saves the user from always having to click to choose the new active application.

An application is activated when:

• The user starts it up, unless the user activates another application while the first one is starting up.

- The user double-clicks a miniwindow belonging to the application, or double-clicks the application's freestanding or docked icon. Double-clicking a docked icon starts up the application if it's not already running.
- The user clicks within one of the windows belonging to the application, provided the window isn't a miniwindow or application icon.
- It receives a message from another application, if the message asks it to do something that may require interaction with the user. A message from the Workspace Manager asking the receiver to open a file is one such message. A message sent to Digital Webster asking it to define a word is another. (See "Activating an Application" later in this chapter for details.)
- It has the frontmost panel or standard window on-screen after the current application is hidden or terminated.