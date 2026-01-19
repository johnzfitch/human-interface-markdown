---
chunk_index: 3958
ref: "100f964bdf35"
id: "100f964bdf353d78e89709746243e7e0da18343f3e122a00bc096e560bfa14ef"
slug: "full-document--acting-for-the-user"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [508, 515]
token_estimate: 263
content_sha256: "11176675d5c1168bc7cc8848d1a899ada2678e88f97410904819f2c92618571f"
compacted: false
heading_path: ["*Introduction*","**Modes**","**Acting for the User**"]
symbol: null
address: null
asset_path: null
---

#### **Acting for the User**

Even though the user is in control, sometimes it's appropriate for an application to act on the user's behalf without waiting for the user's instructions. For example, if a user will always select an item after bringing up a panel, perhaps the panel should already have an item that's selected.

The purpose of acting on behalf of the user is to simplify the task at hand-to make a user action possibly unnecessary. Therefore, the end result of the application's action must be the same as if the user had performed the action. For example, if the panel's display changes whenever the user selects an item, then the display must also change when the application selects an item. Actions made on the user's behalf should be simple and convenient. Otherwise, they can be annoying or confusing, weakening the user's sense of control over the system.

If there's any doubt as to whether an application should act on the user's behalf, then it probably shouldn't. It's better for the application to do too little than too much.