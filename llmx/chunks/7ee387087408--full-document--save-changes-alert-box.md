---
chunk_index: 2790
ref: "7ee387087408"
id: "7ee387087408dd68594ed1e6fbc339063456d695017382f72e04e4353ecb8046"
slug: "full-document--save-changes-alert-box"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [3173, 3200]
token_estimate: 1044
content_sha256: "d04587305dcf97c4de1f4a0d91a92263e2f9919368d3df9cbf2715f574c391e5"
compacted: false
heading_path: ["Save Changes Alert Box"]
symbol: null
address: null
asset_path: null
---

# Save Changes Alert Box

![](images/_page_224_Picture_3.jpeg)

This section describes the standard alert box for saving all changes to a document before a user closes a document with unsaved changes without saving those changes or quits an application when there's an open document with unsaved changes. The design of the save changes alert box standardizes the appearance of the alert box and placement of its buttons so that users can quickly identify a potentially dangerous situation. Follow the guidelines in this section to create your save changes alert box.

Use the caution alert box, which includes the caution icon in the upper-left corner. This icon indicates to users that they need to carefully consider the alert box message before clicking the default button or pressing the Return key. The caution icon should always be in the same, predictable location so that users easily recognize it as a warning and understand its meaning.

The button names in the save changes alert box correlate to the action users perform by pressing the button. The buttons read Save, Don't Save, and Cancel. Using these verbs reinforces the identity of each possible action to the user. In other words, the Don't Save label provides much more context for the user than the word No does.

In order to prevent accidental clicks of the wrong button, you should always keep safe buttons apart from buttons that could cause data loss. Standardizing the location of buttons in a safe configuration provides an additional safeguard for the user. Place the Save button in the lower-right corner with the Cancel button to its left. Place the Don't Save button left-aligned with the message text. Make the Save button the default button, which means that it should be linked to the Return or Enter key. This way, the user is less likely to accidentally click the Don't Save button or activate it with a keystroke and cause irretrievable loss of data. Figure 6-25 shows an example of a standard save changes alert box.

**Figure 6-25** The save changes alert box

![](images/_page_224_Figure_9.jpeg)

Include the name of your application and the name of the document in the alert box message, as shown in Figure 6-25. When a user shuts down the computer, several save changes alert boxes may appear if there are several open documents on the desktop. This addition of contextual information to the standard message helps the user by identifying to which application and document the message refers.

![](images/_page_226_Picture_2.jpeg)

This chapter describes the controls that users manipulate in windows, dialog boxes, and alert boxes. These controls are described in terms of their appearance and behavior, which are standardized. This chapter describes controls provided by the Macintosh Toolbox. This group includes buttons, radio buttons, checkboxes, and pop-up menus. (Pop-up menus are described in Chapter 4, "Menus," which begins on page 49.) This chapter also describes controls that are not supported by the Macintosh Toolbox, including sliders, little arrows, and the outline triangle. In addition, this chapter describes text entry fields and scrolling lists. If you need to, you can design your own controls, following the guidelines in this chapter.

![](images/_page_227_Picture_3.jpeg)

**Controls** are graphic objects that cause instant actions or audible results when the user manipulates them with the mouse. Users set controls that change settings to modify future actions. Controls also allow users to make choices or assign parameters in a range. Controls display existing choices so that they are visible to users. Because of their appearance and behavior, controls enhance the user's sense of direct manipulation.

When an operation requires more than one object or when it needs additional information before it executes, the Macintosh interface uses dialog boxes or alert boxes to convey and gather information. These dialog boxes and alert boxes use controls that users manipulate to provide the additional input. Controls are also found in windows. Controls provide users with familiar tools and formats for responding to the computer's need for information.