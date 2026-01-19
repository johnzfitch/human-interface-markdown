---
chunk_index: 4144
ref: "18bcd1891b9a"
id: "18bcd1891b9a0374dec5a1e3ad20e1939415dd40c2ac0f01f6ea2de2da875e09"
slug: "full-document--programming-note-the-windows-menu"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [2524, 2531]
token_estimate: 206
content_sha256: "51393ab95d20fb869f45160ff05b6baf46dac3ac26eb44c4b0b04d47ecb2c32f"
compacted: false
heading_path: ["5 *Panels*","**The Windows Menu**","**Programming Note: The Windows Menu**"]
symbol: null
address: null
asset_path: null
---

#### **Programming Note: The Windows Menu**

This menu and all of its functionality are provided for you. All you have to do is drag the Windows command into your main menu from the Palettes window of Interface Builder.

The commands inserted below Arrange in Front list document windows. Each command brings one window to the front and, if possible, makes it the key window. The Application Kit creates this list and dynamically adds a command for each document window when it's opened. An example of these dynamically created commands is below. Because the Application Kit creates the command names from the title bar of each window, improperly titled windows can lead to the Windows menu becoming confusing or too wide. Window titles are discussed in "Choosing a Title" in Chapter 4.

![](images/_page_142_Picture_1.jpeg)