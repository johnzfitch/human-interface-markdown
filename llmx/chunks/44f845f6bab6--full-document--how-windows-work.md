---
chunk_index: 4026
ref: "44f845f6bab6"
id: "44f845f6bab689a6a63e36f3e2ae7fe3d3e97137f9b7e9393d9c4dc02b4b44e3"
slug: "full-document--how-windows-work"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1152, 1163]
token_estimate: 240
content_sha256: "1679dc50ebb5df258a202484db7d47a175f882a24b5841daf44f94d3ba85b5dc"
compacted: false
heading_path: ["The Window Interface to Applications","**How Windows Work**"]
symbol: null
address: null
asset_path: null
---

## **How Windows Work**

Every window has a content area, where the application is free to draw (although the Application Kit draws default miniwindows and application icons for you). Standard windows, panels, and menus also have a title bar above the content area, and a border surrounding both the content area and title bar.

The title bar is the center of control for the window. It holds the window's title, if it has one, and may contain buttons that can be used to dismiss it from the screen. If a window has a title bar, users move the window by dragging it by its title bar.

Panels and standard windows can also have a resize bar at the bottom, below the content area but within the border. By dragging any of the regions of the resize bar, the user can alter the size and shape of the window. The resize bar is the only window control located outside the title bar.

The parts of a window are illustrated below.

![](images/_page_64_Picture_6.jpeg)