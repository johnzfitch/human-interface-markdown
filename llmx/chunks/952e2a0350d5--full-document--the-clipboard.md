---
chunk_index: 2722
ref: "952e2a0350d5"
id: "952e2a0350d5b0ab947f643c2fdf6b7f672c7a6e3cd4506abe95cbdfcf6b21b6"
slug: "full-document--the-clipboard"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [1994, 2013]
token_estimate: 546
content_sha256: "09c15704618d33f094f029174747a25d38ded6ac3e34774230a291c774257b1c"
compacted: false
heading_path: ["Standard Macintosh Menus","The Edit Menu","The Clipboard"]
symbol: null
address: null
asset_path: null
---

#### The Clipboard

The Clipboard holds whatever data is cut or copied from a document. It stores the contents until the user replaces them with a new cut or copy operation. The user can change documents, applications, or open a utility without losing the Clipboard contents. Because the contents of the Clipboard don't change when the user moves from one application to another, the Clipboard is used to transfer data among compatible applications and desk accessories. If the user moves the Clipboard file from one disk to another, the contents move with it, replacing any existing Clipboard file on the target disk.

Figure 4-76 shows an example of the Clipboard window with some text in it.

**Figure 4-76** The Clipboard

![](images/_page_135_Picture_4.jpeg)

The Clipboard is available to all applications. Your application can show the contents of the Clipboard in a window. The Clipboard window looks and acts like a document window. The contents are visible, but not editable.

Every time the user selects data in the active document and chooses Cut or Copy, store a copy of the selection in the Clipboard, replacing any previous Clipboard contents. Keep the previous contents available in case the user chooses Undo.

Implement the Show Clipboard/Hide Clipboard command in the Edit menu so that the user can display and close the Clipboard window. If the Clipboard is already showing, the user can also use the close box or the Close command to close the window. Show Clipboard and Hide Clipboard are a single toggled item. The Show Clipboard/Hide Clipboard command is described in"Show Clipboard/Hide Clipboard" on page 117.

You should let the user determine when the Clipboard window is open. For example, if the user leaves the window open when quitting your application, the Clipboard should be open when the user restarts it.

In the cooperative, multitasking environment of the current system software, it's important that you hide your application's Clipboard window when your application is not active. In this model, each application has a local Clipboard. Whenever the user switches applications, the contents of the Clipboard are converted to a standard format.