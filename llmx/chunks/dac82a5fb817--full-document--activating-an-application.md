---
chunk_index: 4059
ref: "dac82a5fb817"
id: "dac82a5fb8170b1a2d58054e01b5f4bb9adfc88abf76fd91916d2e216939b863"
slug: "full-document--activating-an-application"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1496, 1503]
token_estimate: 424
content_sha256: "3587fb47cac82b521de5fded105c5b40e31bae03a7f3b4efc92865c0d92f8ec5"
compacted: false
heading_path: ["The Window Interface to Applications","**Activating an Application**"]
symbol: null
address: null
asset_path: null
---

## **Activating an Application**

Usually, an application doesn't have to explicitly activate or deactivate itself. When your application exchanges messages with the Workspace Manager, uses services, or provides services, application activation and deactivation are handled by the system. For example, when the user chooses the Mail Selection service from Edit's Services menu, the Edit application is deactivated. Mail is then activated on condition that no other application is currently active. Since the Edit has been deactivated, this condition will be met, unless the user has activated another application in the meantime. All this happens automatically.

The only time an application should need to explicitly activate or deactivate itself is when it communicates with another application without using the services system or the Workspace Manager. This might happen when two applications work together closely by sending messages directly to each other. If the intent of a message is to activate the receiving application, then the sender of the message should deactivate itself just before sending the message, and the receiver should conditionally activate itself when it receives the message. If the intent of a message is not to activate the other application, then neither application should activate or deactivate itself. In general, a message should conditionally activate the receiving application if the user might need to work in it-even if only to operate a scroller.

**Important:** Applications should avoid activating themselves unconditionally. Unconditional activation violates the principle of user control, since it ignores the user's desire to turn to something else.