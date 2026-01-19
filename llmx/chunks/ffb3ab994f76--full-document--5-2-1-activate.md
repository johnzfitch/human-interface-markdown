---
chunk_index: 296
ref: "ffb3ab994f76"
id: "ffb3ab994f7648f4facee2eb72d2ec8f01cf48fe14aa573502ee030e0bb4b4a0"
slug: "full-document--5-2-1-activate"
path: "marker/1983 Lisa UI Guidelines/full_document.md"
kind: "markdown"
lines: [199, 225]
token_estimate: 265
content_sha256: "5996b27991cbf9fc75408aebd9bf9fe1614e3a7b91adb8ee82ce13869aee3645"
compacted: false
heading_path: ["Chapter 5 Desktop Manager","5.2.1 Activate"]
symbol: null
address: null
asset_path: null
---

## 5.2.1 Activate

The active window is the one the user is currently working on. At most one window on the desktop can be active at a time.

A window becomes active in one of the following ways:

- 1) The user opens the document when it is closed. To open the document, the user either clicks twice on its icon, or chooses Open from the File menu when the icon is selected.
- 2) The user clicks in the document's window when it is deactivated (see section 5.2 for deactivation). The window is exactly the same as it was when the user deactivated it, including the current selection and the position of the document within the window.

An active-Lisawrite document is shown in Figure 8. LisaCalc

5-1

Source: David T Craig Page 0011 of 0024

![](images/_page_11_Figure_1.jpeg)

Figure 8. Active LisaCalc Document

Details: When a window is active, it has the following characteristics:

- 1) Scroll bers are shown in the window.
- 2) The title ber is highlighted.
- 3) The application's nerus are in the neru bar.

Implementation: Automatic in the Toolkit.