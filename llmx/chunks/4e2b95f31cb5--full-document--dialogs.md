---
chunk_index: 1332
ref: "4e2b95f31cb5"
id: "4e2b95f31cb5a65b7eae26ef04fb7f0ba85455d4a65d6074f9be8af2d8e3088e"
slug: "full-document--dialogs"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/full_document.md"
kind: "markdown"
lines: [881, 923]
token_estimate: 1061
content_sha256: "ca4a1f96b350c851302c7e2df80719efc8ff2f853fd1e249f601230f22be2af6"
compacted: false
heading_path: ["Controls, dialogs, and alerts","Dialogs"]
symbol: null
address: null
asset_path: null
---

## Dialogs

Commands in menus normally act on only one object. If a command needs more information before it can be performed, it presents a **dialog box** to gather the additional information from the user. The user can tell which commands will use a dialog box to get more information because these commands are followed by an ellipsis (...) in the menu.

A dialog box is a rectangle that may contain text, controls, and icons. There should be some text in the box that indicates which command caused the dialog box to appear and what the function of the box is.

The user sets controls and text fields in the dialog box to provide the needed information. When the application puts up the dialog box, it should set the controls to some default setting and fill in the text fields with default values, if possible. One of the text fields (the "first" field) should be highlighted, so that the user can change its value just by typing in the new value. If all the text fields are blank, there should be an insertion point in the first field.

Editing text fields in a dialog box should conform to the guidelines detailed under "Editing Text."

When the user is through editing an item,

- Pressing the Tab key accepts the changes made to the item and selects the next field in sequence.
- Clicking in another item accepts the changes made to the previous item and selects the newly clicked item.

Dialog boxes can be either modal or modeless.

A modal dialog box is one that the user must explicitly dismiss before doing anything else, such as making a selection outside the dialog box or choosing a command. Figure 20 shows an example of a modal dialog box.

![](images/_page_62_Picture_7.jpeg)

Figure 20 A modal dialog box

Because it restricts the user's freedom of action, you should use this type of dialog box only sparingly. In particular, the user can't choose a menu item while a modal dialog box is up and therefore can do only the simplest kinds of text editing. For these reasons, the main use of a modal dialog box is when it's important for the user to complete an operation before doing anything else.

A modal dialog box usually has at least two buttons: OK and Cancel. OK dismisses the dialog box and performs the original command according to the information provided; it can be given a more descriptive name than OK: "Start printing," for example. Cancel dismisses the dialog box and cancels the original command. It should always be called Cancel.

A dialog box can have other kinds of buttons as well. These may or may not dismiss the dialog box. The **default button** (the most likely choice in the current situation) is doubly outlined to call attention to it. In Figure 20, OK is the default button. The user can activate the default button simply by pressing Return or Enter on the keyboard. If there's no default button, Return and Enter have no effect and the user must click in one of the screen buttons.

A special type of modal dialog box is one with no buttons. This type of box just informs the user of a situation without eliciting any response. It usually describe the progress of an ongoing operation, then disappears. Because it has no buttons, the user has no way to control or dismiss it. It must remain on the screen long enough for the user to read it.

A modeless dialog box allows the user to perform other operations without dismissing the dialog box. Figure 21 shows an example of a modeless dialog box.

![](images/_page_63_Picture_3.jpeg)

Figure 21 A modeless dialog box

A modeless dialog box is dismissed by clicking in the close box or by choosing Close. The dialog box is also dismissed implicitly when the user chooses Quit. The application should remember the contents of the dialog box after it's dismissed, so that when it's opened again, it can be restored exactly as it was.

Controls work the same way in modeless dialog boxes as in modal dialog boxes, except that buttons never dismiss the dialog box. In this context, the OK button means "go ahead and perform the operation, but leave the dialog box up," whereas the Cancel button usually terminates an ongoing operation.

A modeless dialog box can also have text fields, which the user can edit with the commands in the Edit menu.