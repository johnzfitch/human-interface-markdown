---
chunk_index: 2289
ref: "2eef35d65a63"
id: "2eef35d65a6307b02bb8cbb5ce41a4a977cbc05cd416b1cb66bc2d68d183cf8b"
slug: "chunk-104--print"
path: "marker/1992 Macintosh Human Interface Guidelines/chunks/chunk_104.md"
kind: "markdown"
lines: [66, 72]
token_estimate: 316
content_sha256: "73976c49d47bf1ecef21505dda4cdebd80b46368e853831e5b453c26ff7fec67"
compacted: false
heading_path: ["New","Open","Close","Print…"]
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