---
chunk_index: 2284
ref: "48497f8cdbfa"
id: "48497f8cdbfa7aed086a96c2cf6d34fd3214d077f3aa7455ea70b6ea5d3f9603"
slug: "chunk-104--close"
path: "marker/1992 Macintosh Human Interface Guidelines/chunks/chunk_104.md"
kind: "markdown"
lines: [27, 38]
token_estimate: 814
content_sha256: "4cc471189aba81715cbf2bb000de3f8e787ec85673a20c3090bb2b933a1e3506"
compacted: false
heading_path: ["New","Open","Close"]
symbol: null
address: null
asset_path: null
---

#### Close  
The Close command closes the active window, which may be a document window, a modeless dialog box, a folder, or any other type of window. Clicking in a window's close box provides a mouse-based method of closing windows. The user can also press Command-W to close windows.  
When the user chooses the Close command, and the active document has been changed since the last save, display the standard save changes alert box. This alert box is designed to prevent users from accidentally losing data. The standard appearance and layout of the alert box help users quickly identify a potentially dangerous situation. For information about the layout of items in alert boxes, see "Basic Dialog Box Layout," which begins on page 196 in Chapter 6, "Dialog Boxes."  
Use the caution alert box, which includes the caution icon in the upper-left corner. This icon indicates to users that they need to carefully consider the alert box message before clicking the default button or pressing the Return key. The caution icon should always be in the same, predictable location so that users easily recognize it as a warning and understand its meaning.  
The button names in the save changes alert box correlate to the action users perform by pressing the button. The buttons read Save, Don't Save, and Cancel. Using these verbs reinforces the identity of each possible action to the user. In other words, Don't Save provides much more context for the user than No does.  
In order to prevent accidental clicks of the wrong button, you should always keep safe buttons apart from buttons that could cause data loss. Standardizing the location of buttons in a safe configuration provides an additional safeguard for the user. Place the Save button in the lower-right corner with the Cancel button to its left. Place the Don't Save button left-aligned with the message text. Make the Save button the one that is linked to the Return or Enter key. This way, the user is less likely to accidentally click the Don't Save button and cause irretrievable loss of data. Figure 4-64 shows an example of a standard save changes alert box.  
**Figure 4-64** The save changes alert box  
![](images/_page_126_Picture_4.jpeg)  
Include the name of your application and the name of the document in the alert box message, as shown in Figure 4-64. When a user chooses the Close command, the message should read, "Save changes to the . . . document . . . before closing?" This wording should change to "Save changes to the . . . document . . . before quitting?" if the alert box appears as a result of the Shut Down command or the Quit command. When a user shuts down the computer, several save changes alert boxes may appear if there are several open, unsaved documents on the desktop. The addition of contextual information to the message helps the user by identifying to which application and document the message refers.  
When you display the save changes alert box, center it horizontally either on the screen or over the active window if the window is on a large screen. Figure 4-65 shows the correct placement of the alert box on three common sizes of screens.  
**Figure 4-65** The correct location of the save changes alert box  
![](images/_page_127_Picture_3.jpeg)