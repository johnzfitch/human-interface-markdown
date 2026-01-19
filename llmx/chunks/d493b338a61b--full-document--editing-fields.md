---
chunk_index: 1434
ref: "d493b338a61b"
id: "d493b338a61b6ee73da4437e9e8f729f15b52d212ed70a847206388d92e54d23"
slug: "full-document--editing-fields"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/full_document.md"
kind: "markdown"
lines: [2084, 2095]
token_estimate: 431
content_sha256: "074c6cd594a1f2e0ef51e24f7d7169bbfdc942ce1272fee4b05196ef7006d79d"
compacted: false
heading_path: ["**Editing fields**"]
symbol: null
address: null
asset_path: null
---

# **Editing fields**

If an application isn't primarily a text application, but does use text in fields (such as in a dialog box), you may not need to provide the full text-editing capabilities described so far. In Macintosh applications, the simplest way to implement text editing is to use TextEdit in the User Interface Toolbox. It's important, however, that whatever editing capabilities the application provides under these circumstances be upward-compatible with the full text-editing capabilities. The following list ranks the capabilities that can be provided, in a continuum from the minimum set to the most sophisticated features:

- The user can select the whole field and type in a new value, use backspace, select a substring of the field and replace it, and select a word by double-clicking.
- The user can choose Undo, Cut, Copy, Paste, and Clear, as described in this chapter under "The Edit Menu."
- Intelligent cut and paste is fully implemented. (TextEdit does not provide this)

Even applications with only minimal text editing should perform appropriate edit checks. For example, if the only legitimate value for a field is a string of digits, the application should issue an alert message if the user types any nondigits. For example, the alert message might interrupt the erring user to remind him or her that the letters l and l can't be used in place of the numerals l and l Alternatively, the application could wait until the user is through typing before checking the validity of a field's contents. In this case, the appropriate time to check the field is when the user clicks anywhere other than within the field or presses the Return, Enter, or Tab key.

![](images/_page_135_Picture_0.jpeg)