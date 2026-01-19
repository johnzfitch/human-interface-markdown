---
chunk_index: 959
ref: "71388aecf3f1"
id: "71388aecf3f11de7bb158570636940ff14ccb28d497a8ec744f991d224dcb8c7"
slug: "full-document--dialogs"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/full_document.md"
kind: "markdown"
lines: [1951, 1995]
token_estimate: 1051
content_sha256: "17e1e497e39501affb1a1b4f55a034b196f28a40d93736b510c1df991a380f75"
compacted: false
heading_path: ["Controls, Dialogs, and Alerts","Controls","Buttons","Dialogs"]
symbol: null
address: null
asset_path: null
---

#### Dialogs

Commands in menus normally act on only one object. If a command needs more information before it can be performed, it presents a dialog box to gather the additional

information from the user. The user can tell which commands bring up dialog boxes because they're followed by an ellipsis (...) in the menu.

A dialog box is a rectangle that may contain text, controls, and icons. There should be some text in the box that indicates which command caused the dialog box to appear and what the function of the box is.

The user sets controls and text fields in the dialog box to provide the needed information. When the application puts up the dialog box, it should set the controls to some default setting and fill in the text fields with default values, if possible. One of the text fields (the "first" field) should be highlighted, so that the user can change its value just by typing in the new value. If all the text fields are blank, there should be an insertion point in the first field.

Editing text fields in a dialog box should conform to the guidelines detailed under "Text Editing."

When the user is through editing an item,

- Pressing the Tab key accepts the changes made to the item and selects the next item in sequence.
- Clicking in another item accepts the changes made to the previous item and selects the newly clicked item.

Dialog boxes are either modal or modeless.

A modal dialog box is one that the user must explicitly dismiss before doing anything else, such as making a selection outside the dialog box or choosing a command.

![](images/_page_90_Figure_10.jpeg)

Figure 46. A Modal Dialog Box

Because it restricts the user's freedom of action, this type of dialog box should be used only sparingly. In particular, the user can't choose a menu item while a modal dialog box is up and therefore can do only the simplest kinds of text editing. For these reasons, the main use of a modal dialog box is when it's important for the user to complete an operation before doing anything else.

A modal dialog box usually has at least two buttons: OK and Cancel. OK dismisses the dialog box and performs the original command according to the information provided; it can be given a more descriptive name than "OK." Cancel dismisses the dialog box and cancels the original command. It should always be called "Cancel."

A dialog box can have other kinds of buttons as well. These may or may not dismiss the dialog box. The **default button** (the safest or most likely choice in the current situation) is boldly outlined to call attention to it. The default button is the one that takes effect if the user presses Return or Enter on the keyboard instead of one of the screen buttons. Pressing the Return or Enter key has the same effect as clicking the default button. If there's no default button, Return and Enter have no effect.

A special type of modal dialog box is one with no buttons. This type of box just informs the user of a situation without eliciting any response. It usually describe the progress of an ongoing operation. Because it has no buttons, the user has no way to dismiss it. Therefore, the application must display it long enough for the user to read it before taking it down.

A modeless dialog box allows the user to perform other operations without dismissing the dialog box.

![](images/_page_91_Picture_4.jpeg)

Figure 47. A Modeless Dialog Box

A modeless dialog box is dismissed by clicking in the close box or by choosing Close. The dialog box is also dismissed implicitly when the user chooses Quit. It's usually a good idea for the application to remember the contents of the dialog box after it's dismissed, so that, when it's opened again, it can be restored exactly as it was.

Controls work the same way in modeless dialog boxes as in modal dialog boxes, except that buttons never dismiss the dialog box. In this context, the OK button means "go ahead and perform the operation, but leave the dialog box up," whereas the Cancel button usually terminates an ongoing operation.

A modeless dialog box can also have text fields. Because the user can choose menu commands, the full range of editing capabilities can be made available.