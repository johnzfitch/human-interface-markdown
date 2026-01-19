---
chunk_index: 4148
ref: "f2fd42c762cc"
id: "f2fd42c762cc6a41455c83db9a8ccfb29d07d37e9e967a198a5a1c2c63532445"
slug: "full-document--adding-a-tools-menu"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [2557, 2566]
token_estimate: 291
content_sha256: "64650f8b1f0e53c4c150ef5aeabe5990a671488403e82418eb87ffa535127db8"
compacted: false
heading_path: ["5 *Panels*","**Adding a Tools Menu**"]
symbol: null
address: null
asset_path: null
---

## **Adding a Tools Menu**

Since it's easiest for users to find a command if it's arranged in a submenu with other functionally related commands, commands that bring up panels and special, nondocument windows should be located throughout the menu hierarchy as appropriate. For example, the Font Panel command is in the Font menu, the Open command is in the Document menu, and Page Layout is in the Format menu.

However, if a window or panel is an independent tool that encapsulates a functional domain all its own, it may be difficult to group it with other commands. Examples are the palettes in a graphics program, the Inspector in Interface Builder, and the Console in the Workspace Manager. If your application has two or more such commands, you should consider collecting them together in a Tools menu. An example from the Workspace Manager is illustrated below.

![](images/_page_144_Picture_3.jpeg)

However, the Tools menu should not be considered a default location for commands that bring up windows or panels. If a window or panel isn't perceived to be a tool, its command should go elsewhere. If a command can be functionally grouped, it should be.