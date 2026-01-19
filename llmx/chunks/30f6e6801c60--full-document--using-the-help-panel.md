---
chunk_index: 4093
ref: "30f6e6801c60"
id: "30f6e6801c6042c82cf2b0e26c27eae83d5a568f1522ae341616fad977de9dd0"
slug: "full-document--using-the-help-panel"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1843, 1848]
token_estimate: 260
content_sha256: "1634d5a440f3f8464ca9593a06285df7ab587f0208ccbe68a5ec431c34d0d9b9"
compacted: false
heading_path: ["5 *Panels*","**Using the Help Panel**"]
symbol: null
address: null
asset_path: null
---

## **Using the Help Panel**

The Application Kit Help panel is part of the NeXTSTEP help system. Some of the information displayed by this panel is already provided by the help system. For example, every application has available to it ready-made help on using the NeXTSTEP user interface. Besides help on basic tasks, such as using menus and scrollers, the help system has skeletal help that's automatically displayed when the user Help-clicks in menus and panels that are implemented by the Application Kit. For example, when the user Help-clicks in the Print panel, some basic information on using the panel appears in the Help panel.

To use the Help panel, you need to add information about the objects in your application and the tasks associated with them. You should also override the standard help for Application Kit panels and commands with new files containing links to more task-oriented help. Once you've added the information, you should modify the provided index and table of contents so that they refer to the information.