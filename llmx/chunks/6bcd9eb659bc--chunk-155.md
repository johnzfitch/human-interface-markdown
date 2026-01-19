---
chunk_index: 3781
ref: "6bcd9eb659bc"
id: "6bcd9eb659bcd359c3d2acfc0a33fc1c42d9d3b77283d2d8267c47d12a011472"
slug: "chunk-155"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_155.md"
kind: "markdown"
lines: [1, 5]
token_estimate: 311
content_sha256: "2b6c5f85157f334dc3ecc7c4bc0cd06d9cfbb1fa88833413aa00180027aabb77"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 155 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 284 -->
Since it's easiest for users to find a command if it's arranged in a submenu with other functionally related commands, commands that bring up panels and special, nondocument windows should be located throughout the menu hierarchy as appropriate. For example, the Font Panel command is in the Font menu, the Open command is in the Document menu, and Page Layout is in the Format menu.  
However, if a window or panel is an independent tool that encapsulates a functional domain all its own, it may be difficult to group it with other commands. Examples are the palettes in a graphics program, the Inspector in Interface Builder, and the Console in the Workspace Manager. If your application has two or more such commands, you should consider collecting them together in a Tools menu. An example from the Workspace Manager is illustrated below.  
![](images/_page_144_Picture_3.jpeg)  
However, the Tools menu should not be considered a default location for commands that bring up windows or panels. If a window or panel isn't perceived to be a tool, its command should go elsewhere. If a command can be functionally grouped, it should be.