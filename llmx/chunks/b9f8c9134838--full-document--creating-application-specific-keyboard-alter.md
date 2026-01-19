---
chunk_index: 3998
ref: "b9f8c9134838"
id: "b9f8c91348383d1286db64674add26ca5e38ea109a95ca53c5f921e941124752"
slug: "full-document--creating-application-specific-keyboard-alter"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [893, 908]
token_estimate: 603
content_sha256: "6ee3e097567745b954f36eaa17422dfa5fbbe56d0270daeb08273ece464f145d"
compacted: false
heading_path: ["*Introduction*","**Creating Application-Specific Keyboard Alternatives**"]
symbol: null
address: null
asset_path: null
---

## **Creating Application-Specific Keyboard Alternatives**

The NeXTSTEP user interface is visual, so all operations-all menu commands and scrolling operations, for example-have a graphical representation on-screen and can be performed using the mouse. Keyboard alternatives are just that: alternatives. They should never be used for operations that can't be performed using the mouse.

The main consideration in deciding which operations should have keyboard alternatives is frequency of use. It's better to assign a keyboard alternative to a frequently used command than to one that's used less often. Infrequently used commands-such as the Info Panel command-should never be assigned keyboard alternatives.

Keyboard alternatives are allowed only for the commands in a menu, the buttons in a panel, or the items in a pull-down list. The characters used as keyboard alternatives must be displayed to the user in the menu, panel, or list. Menus put them on the commands themselves, and pull-down lists follow this example. A panel can present the keyboard alternatives for its buttons in any way that's appropriate to the design of the panel.

It's usually a good idea to assign keyboard alternatives to command~ that are needed while working on the keyboard (for example, the commands in the Find menu). The keyboard alternative frees users from having to switch their attention from the keyboard to the mouse and back again.

You can also use keyboard alternatives to enable proficient users to work with one hand on the keyboard and the other on the mouse. For example, Command-x, Command-c, and Command-v allow users to select with the mouse while carrying out cut, copy, and paste operations from the keyboard. These keyboard alternatives free users from having to move the cursor out of the region where they're working just to click a command.

If keyboard alternatives are assigned to any in a set of parallel commands for formatting or viewing data (for example, commands that sort a list of items in various ways), the command that restores the default should also be assigned a keyboard alternative. The keyboard can then take the user to an alternative format and back to the default, rather than just half way.

**Note:** You don't need to assign a keyboard alternative to every command. Remember that users can create their own global keyboard alternatives by using the Preferences application.