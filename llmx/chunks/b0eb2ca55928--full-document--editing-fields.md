---
chunk_index: 2902
ref: "b0eb2ca55928"
id: "b0eb2ca55928fb80864452f70ae68d86b2a292e0100accf81654e25d0f4d7cd1"
slug: "full-document--editing-fields"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [4771, 4789]
token_estimate: 718
content_sha256: "45d24eed62a3ede3e4aa6555742f60ac102c094766d9864959350afdf06fa55a"
compacted: false
heading_path: ["Editing Text","Editing Fields"]
symbol: null
address: null
asset_path: null
---

## Editing Fields

If an application isn't primarily a text application, but does use text in text entry fields (such as in a dialog box), you may not need to provide the full text-editing capabilities described so far. In Macintosh applications, the simplest way to implement text editing is to use TextEdit, or to use the Dialog Manager, which in turn uses TextEdit. It's important, however, that whatever editing capabilities the application provides under these circumstances be upward-compatible with the full text-editing capabilities. The application should support the following editing capabilities:

- The user can select the whole field and type in a new value, delete text, select a substring of the field and replace it, and select a word by double-clicking.
- The user can choose Undo, Cut, Copy, Paste, and Clear, as described in "The Edit Menu" beginning on page 109 in Chapter 4, "Menus."

In addition, you can support intelligent cut and paste. (TextEdit does not provide this.) Even applications with only minimal text editing should perform appropriate edit checks. For example, if the only legitimate value for a field is a string of digits, the application should alert the user if any nondigits are typed. The alert message might remind the user that the letters *l* and *o* can't be used in place of the numerals *1* and *0*. Alternatively, the application could wait until the user is through typing before checking the validity of a field's contents. In this case, the appropriate time to check the field is when the user clicks anywhere other than in the field or presses the Return, Enter, or Tab key.

Editing Text **303**

![](images/_page_328_Picture_2.jpeg)

This chapter describes how you should use language in your product. Although the Macintosh interface uses graphics as the primary means of user-computer interaction, much of the user interface still involves text of some kind—names in buttons, labels for checkboxes and radio buttons, messages in dialog boxes, online help systems, and manuals. Consistency in the use of language helps users easily learn to use the Macintosh.

In certain situations, the computer displays textual messages to describe a particular situation or ask the user for a specific decision. This chapter provides guidance on how to construct these messages in language that users understand. This chapter also contains information on how to write balloon help and how to construct a useful online help system for your application.

This chapter presents guidelines for using language clearly, consistently, and concisely throughout every aspect of your product, ranging from the user interface to paper documentation. Any time words are involved in your product, the design team should include a skilled writer who is responsible for not only the documentation but also the use of language on the screen.