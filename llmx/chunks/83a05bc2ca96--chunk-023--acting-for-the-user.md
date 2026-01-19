---
chunk_index: 3591
ref: "83a05bc2ca96"
id: "83a05bc2ca96ebd21dc2ba31db589392b4b39a99a1f8d46bebb047ac3628d453"
slug: "chunk-023--acting-for-the-user"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_023.md"
kind: "markdown"
lines: [7, 10]
token_estimate: 264
content_sha256: "41a1a2de9a76422e55c648f9edc2aec34015b4b450c8993c1e99c801fece9df7"
compacted: false
heading_path: ["**Acting for the User**"]
symbol: null
address: null
asset_path: null
---

#### **Acting for the User**  
Even though the user is in control, sometimes it's appropriate for an application to act on the user's behalf without waiting for the user's instructions. For example, if a user will always select an item after bringing up a panel, perhaps the panel should already have an item that's selected.  
The purpose of acting on behalf of the user is to simplify the task at hand-to make a user action possibly unnecessary. Therefore, the end result of the application's action must be the same as if the user had performed the action. For example, if the panel's display changes whenever the user selects an item, then the display must also change when the application selects an item. Actions made on the user's behalf should be simple and convenient. Otherwise, they can be annoying or confusing, weakening the user's sense of control over the system.  
If there's any doubt as to whether an application should act on the user's behalf, then it probably shouldn't. It's better for the application to do too little than too much.