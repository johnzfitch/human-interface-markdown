---
chunk_index: 4146
ref: "4b14258990ac"
id: "4b14258990ac47f91b507e1502379bb1e81fc2c4dadab1af63cb58937a25dfa1"
slug: "full-document--providing-services"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [2538, 2550]
token_estimate: 365
content_sha256: "13c4d2a2346f68bd58a6fe1ccb7f4f701b82b18dba28726474559dc35219eaeb"
compacted: false
heading_path: ["5 *Panels*","**Providing Services**"]
symbol: null
address: null
asset_path: null
---

## **Providing Services**

Applications can specify how commands that request their services should be worded. The following guidelines apply:

- Each command should begin with a verb and should name the application that will respond to the request. If the name of the application can be interpreted as a verb, it can be the first word of a command phrase (for example, Chart Selection for an application named Chart). Otherwise, the verb that begins the command should be followed by a preposition and the name of the responding application (Open from Workspace, Define in Webster).
- If an application responds to more than one service request, it can arrange the commands in a submenu under the application's name. Commands in the submenu don't have to name the application, but should, like all other commands, begin with a verb.

However, if the application name is commonly interpreted as a verb, the submenu commands can consist of words that would meaningfully follow the application name in a phrase, much as the commands in the Paste As menu. For example:

![](images/_page_143_Picture_5.jpeg)

Service requests conditionally activate the other application, but only if user input might be required. For example, Digital Webster is likely to require the user to scroll the display, but the Workspace Manager doesn't need the user's help to get a file opened. The application that opens the file will become active, but the Workspace Manager won't.