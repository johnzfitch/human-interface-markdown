---
chunk_index: 297
ref: "d10e6acf4168"
id: "d10e6acf4168b8d9a6ca247f874d0343b02e4e4db9b5c40d4de69414ae93d511"
slug: "full-document--5-2-2-deactivate"
path: "marker/1983 Lisa UI Guidelines/full_document.md"
kind: "markdown"
lines: [226, 248]
token_estimate: 277
content_sha256: "2a6267d06184987f07fe72006308600bdb0edfa33366266af9886e4299ffaebd"
compacted: false
heading_path: ["Chapter 5 Desktop Manager","5.2.2 Deactivate"]
symbol: null
address: null
asset_path: null
---

## 5.2.2 Deactivate

The user deactivates a window by clicking outside of it. When she does this, the document stays just as it is; the application does not ask her to finish doing anything. When the user reactivates the window, the application picks up where it left off.

A descrivated <del>Lisawriter</del> document is shown in Figure 9.

5-2

Source: David T Craig

![](images/_page_12_Figure_1.jpeg)

Floure 9. Deactivated LisaCalc Document

Details: When the user deactivates a window, the display changes in the following ways:

- 1) The scroll ber portion of the window is shown in white.
- 2) The title bar is no longer highlighted.
- If a selection is visible in the window, it is highlighted with a gray pattern rather then in inverse video.
- 4) The menus for the application disappear from the menu bar.

Implementation: Automatic in the Toolkit. The Toolkit provides a gray pattern for dinhighlingting, but the application can use its own pattern if it wents. Alternatively, it can nake the dinhighlighting look like a regular selection or like a deselection if necessary for sesthetic reasons.