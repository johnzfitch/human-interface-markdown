---
chunk_index: 3768
ref: "57a23cc5dca3"
id: "57a23cc5dca32bf84f9a08203b4789bc6bf868afcaf74e6c8b9f6b8402f11a1d"
slug: "chunk-147"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_147.md"
kind: "markdown"
lines: [1, 4]
token_estimate: 355
content_sha256: "4b5eacf49da770b5dc49a209664ea7957c0787c216c66c3e32c4fef9989235ed"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 147 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 328 -->
The Spelling and Check Spelling commands in the Edit menu are intended to provide a uniform interface for checking spelling that in many ways parallels the interface for Find. (Find is discussed under "The Find Menu," below.) These commands for checking spelling are supported by the Application Kit's Text object; custom objects will need custom code for checking spelling.  
The Spelling command brings up the Spelling panel, which is described in Chapter 5. The Check Spelling command is equivalent to the button on the panel that searches for and selects the next misspelled word in the main window. It permits the user to find the next misspelled word without bringing up the panel. If the application can't find the next misspelled word until the user takes some action within the Spelling panel (for example, loads a dictionary), Check Spelling brings up the panel. (This is parallel behavior to Save bringing up a panel when the user must first supply a file name, or Find Next bringing up the Find panel if the user needs to enter a text string to search for.)  
If an application has spelling options that can't be accommodated in a panel, Spelling and Check Spelling should be replaced by a Spelling command that brings up a submenu. That menu might then have Spelling Panel and Check Spelling commands.