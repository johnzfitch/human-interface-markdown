---
chunk_index: 2802
ref: "05c26d4fc857"
id: "05c26d4fc857080e8612e06776d0401d870c4291ed110454c3d1ba16964f7231"
slug: "full-document--text-entry-fields"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [3387, 3403]
token_estimate: 532
content_sha256: "df59cc6fb01b4613bc10267ca4f2af84ade7ea11cfa6430076b85b667765d343"
compacted: false
heading_path: ["Other Elements for User Interaction","Text Entry Fields"]
symbol: null
address: null
asset_path: null
---

## Text Entry Fields

The **text entry field** is typically a rectangular box in a dialog box where the user enters some text to identify something. It is also called an *editable text field*. For example, in the Save As dialog box, the user types in the name of a document. Figure 7-19 shows an example of a text entry field.

**Figure 7-19** A text entry field

![](images/_page_242_Picture_5.jpeg)

If an application isn't primarily a text application, but does use text in fields, you may not need to provide the full text-editing capabilities. In Macintosh applications, the simplest way to implement text editing is to use TextEdit, or to use the Dialog Manager, which in turn uses TextEdit. You need to make sure that whatever level of text-editing capabilities you implement for text entry fields is upward compatible with the full text-editing capabilities. You should implement these editing capabilities:

- The user can select the whole field and type in a new value, delete text, select a substring of the field and replace it, and select a word by double-clicking.
- The user can choose Undo, Cut, Copy, Paste, and Clear, as described in the section "The Edit Menu" on page 109 in Chapter 4, "Menus."

In addition, you can also implement intelligent cut and paste. (TextEdit does not provide this.) This capability is described in the section "Intelligent Cut and Paste," which begins on page 301 in Chapter 10, "Behaviors."

Even applications with only minimal text editing should perform appropriate edit checks. For example, if the only legitimate value for a field is a string of digits, the application should issue an alert message if the user types any nondigits. For example, the alert message might interrupt the user to remind him or her that the letters *l* and *o* can't be used in place of the numerals *1* and *0*. Alternatively, the application could wait until the user is through typing before checking the validity of a field's contents. In this case, the appropriate time to check the field is when the user clicks anywhere other than within the field or presses the Return, Enter, or Tab key.