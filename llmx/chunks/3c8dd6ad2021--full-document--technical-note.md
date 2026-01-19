---
chunk_index: 1505
ref: "3c8dd6ad2021"
id: "3c8dd6ad20211d005b0502e725eea8b8b8fb3f12b67d9582caafac92a2c6c51a"
slug: "full-document--technical-note"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/full_document.md"
kind: "markdown"
lines: [2635, 2658]
token_estimate: 598
content_sha256: "c315e77e878a6b6d81e3784d0e0f3ba12b07f96bcc2fa5a054096327cc002cce"
compacted: false
heading_path: ["Technical Note"]
symbol: null
address: null
asset_path: null
---

# Technical Note

#8. Stationery

By: Katie Withey Date: 31 March 87

This information will be in the final version of Human Interface Guidelines: the Apple Desktop Interface (to be published by Addison Wesley)

Many users find that they create, for example, a "Letterhead" document in their word processor and an "Overhead template" document in their graphics package, which they duplicate in the Finder (or open and then immediately Save As something else) every time they use. This is an inefficient way for users to create "stationery", and we've standardized on a way for applications to implement this feature, so users don't have to. Stationery is a different type of file, which can contain anything that a regular document contains (even simply page setup or layout information). It's sort of a cross between an application and a document: when stationery is opened, all the information in the original is shown (like opening a document), but the user must name it as if it were a new document (like opening the application icon). What actually happens is a copy of the file is opened instead of the original. Stationery is created using the Save As dialog. The user first sets up a document that contains everything that's wanted in the stationery, such as a standard memo template. The user then chooses Save As, and the dialog provides an option to save as Stationery, similar to the common options to save as TEXT or PICT (see Figure 1).

![](images/_page_173_Picture_0.jpeg)

Figure 1. Save As dialog box with Stationery option

The user names the stationery, clicks the radio button labeled Stationery, and then clicks Save.

In the Finder, the stationery appears as an icon that looks like a stack of document icons (with the bottom corner turned up instead of the top corner, as shown in Figure 2).

![](images/_page_173_Picture_4.jpeg)

Figure 2. Sample Document and Stationery icons

To use the stationery, the user double-clicks on the stationery icon (or, from within the application, the user chooses Open from the File menu, selects the stationery name, and clicks Open). The document that appears has the name of the stationery, with a number appended (for example, "Memo #1"). It contains whatever was saved in the stationery. When the user chooses Save, the Save As dialog appears, so the new document can be either saved with the default numbered name or renamed.