---
chunk_index: 4135
ref: "3484d6b5d285"
id: "3484d6b5d28584ebaa2136a71d9b0152756a12b818bd6843a03c018db581920f"
slug: "full-document--checking-spelling"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [2346, 2353]
token_estimate: 335
content_sha256: "7ba6374fe70a95a5c5d0c83e9dc7376fd92473d08f6b59dfdd279980e431fa54"
compacted: false
heading_path: ["5 *Panels*","**Checking Spelling**"]
symbol: null
address: null
asset_path: null
---

## **Checking Spelling**

The Spelling and Check Spelling commands in the Edit menu are intended to provide a uniform interface for checking spelling that in many ways parallels the interface for Find. (Find is discussed under "The Find Menu," below.) These commands for checking spelling are supported by the Application Kit's Text object; custom objects will need custom code for checking spelling.

The Spelling command brings up the Spelling panel, which is described in Chapter 5. The Check Spelling command is equivalent to the button on the panel that searches for and selects the next misspelled word in the main window. It permits the user to find the next misspelled word without bringing up the panel. If the application can't find the next misspelled word until the user takes some action within the Spelling panel (for example, loads a dictionary), Check Spelling brings up the panel. (This is parallel behavior to Save bringing up a panel when the user must first supply a file name, or Find Next bringing up the Find panel if the user needs to enter a text string to search for.)

If an application has spelling options that can't be accommodated in a panel, Spelling and Check Spelling should be replaced by a Spelling command that brings up a submenu. That menu might then have Spelling Panel and Check Spelling commands.