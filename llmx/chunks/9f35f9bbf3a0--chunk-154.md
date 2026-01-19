---
chunk_index: 3779
ref: "9f35f9bbf3a0"
id: "9f35f9bbf3a06ee1693cc0a2e0e59c989cea7b6c5f9c9a6a2af938376374a24a"
slug: "chunk-154"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_154.md"
kind: "markdown"
lines: [1, 7]
token_estimate: 385
content_sha256: "4cf1cce0cfac90eb8352872df8381d9609d9255a2d11c843e66e5393e38119e3"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 154 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 533 -->
Applications can specify how commands that request their services should be worded. The following guidelines apply:  
- Each command should begin with a verb and should name the application that will respond to the request. If the name of the application can be interpreted as a verb, it can be the first word of a command phrase (for example, Chart Selection for an application named Chart). Otherwise, the verb that begins the command should be followed by a preposition and the name of the responding application (Open from Workspace, Define in Webster).
- If an application responds to more than one service request, it can arrange the commands in a submenu under the application's name. Commands in the submenu don't have to name the application, but should, like all other commands, begin with a verb.  
However, if the application name is commonly interpreted as a verb, the submenu commands can consist of words that would meaningfully follow the application name in a phrase, much as the commands in the Paste As menu. For example:  
![](images/_page_143_Picture_5.jpeg)  
Service requests conditionally activate the other application, but only if user input might be required. For example, Digital Webster is likely to require the user to scroll the display, but the Workspace Manager doesn't need the user's help to get a file opened. The application that opens the file will become active, but the Workspace Manager won't.