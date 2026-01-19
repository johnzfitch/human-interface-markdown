---
chunk_index: 2719
ref: "fe92a7261b6e"
id: "fe92a7261b6ead8bb9d4f7bb3e56b7494546efabd6c8db06cd5688250c170c33"
slug: "full-document--print"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [1948, 1961]
token_estimate: 315
content_sha256: "ac13ca606944167b91e9dec992b658d834f02a19715167b3ddc7438edc4a2687"
compacted: false
heading_path: ["Standard Macintosh Menus","File Menu","New","Print…"]
symbol: null
address: null
asset_path: null
---

#### Print…

The Print command lets the user specify various parameters, such as print quality and number of copies, and then prints the document. The parameters apply to only the current printing operation and are not saved with the document. Figure 4-71 shows a typical Print dialog box.

If the user has not selected a printer in the Chooser, display a dialog box when the user chooses the Print command. This dialog box should alert the user of the situation and direct the user to the Chooser to select a printer.

If a document is printed from the Finder, the document is opened and the Print dialog box is displayed. If the application is launched for the purpose of printing the document, the application quits after the printing is complete or canceled. If the application is already running, the application remains active after the printing is complete. This behavior occurs so that the application remains in the same state after printing a document as before the printing was initiated.

**Figure 4-71** A Print dialog box

![](images/_page_132_Picture_3.jpeg)

If you find it necessary to add items to the Print dialog box, do so at the bottom of the dialog box. For more information on printing, see the appropriate book in *Inside Macintosh*.