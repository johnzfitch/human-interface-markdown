---
chunk_index: 2048
ref: "6bea99a2ccb8"
id: "6bea99a2ccb89b27e0326660843555794810dce948da35c705882192340709b1"
slug: "full-document--editing-fields"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/full_document.md"
kind: "markdown"
lines: [2645, 2658]
token_estimate: 452
content_sha256: "4d2e1ab3075ed790756da48e676f7d66562774e7d834f8b73987640c7dbf725c"
compacted: false
heading_path: ["Intelligent cut and paste","Editing fields"]
symbol: null
address: null
asset_path: null
---

### Editing fields

If an application isn't primarily a text application, but does use text in fields (such as in <sup>a</sup> dialog box), you may not need to provide the full text-editing capabilities described so far. In Macintosh applications, the simplest way to implement text editing is to use TextEdit in the User Interface Toolbox. It's important, however, that whatever editing capabilities the application provides under these circumstances be upwardcompatible with the full text-editing capabilities. The following list ranks the capabiliues that can be provided, in a continuum from the minimum set to the most sophisticated features:

- n The user can select the whole field and type in <sup>a</sup> new value, use backspace, select <sup>a</sup> substring of the field and replace it, and select a word by double-clicking.
- d The user can choose Undo, Cut, Copy, Paste, and Clear, as described in this chapter under "The Edit Menu."
- Intelligent cut and paste is fully implemented. (TextEdit does not provide this.)

Even applications with only minimal text editing should perform appropriate edit checks. For example, if the only legitimate value for a field is a string of digits, the application should issue an alert message if the user types any nondigits. For example, the alert message might interrupt the erring user to remind him or her that the letters / and O can't be used in place of the numerals <sup>1</sup> and 0. Alternatively, the application could wait until the user is through typing before checking the validity of a field's contents. In this case, the appropriate time to check the field is when the user clicks anywhere other than within the field or presses the Return, Enter, or Tab key.

![](images/_page_135_Picture_0.jpeg)

![](images/_page_136_Picture_0.jpeg)