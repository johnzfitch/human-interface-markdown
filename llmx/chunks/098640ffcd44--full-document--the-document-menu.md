---
chunk_index: 4129
ref: "098640ffcd44"
id: "098640ffcd446fd377e088c1d39b42ad45d37914cb875139c9c177468a8c8289"
slug: "full-document--the-document-menu"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [2245, 2280]
token_estimate: 1447
content_sha256: "bb0d7f505f7ebfce9a1834e6fdc106e7cb2e1a1f7ddfd263248f71ca9ea4f2a2"
compacted: false
heading_path: ["5 *Panels*","**The Document Menu**"]
symbol: null
address: null
asset_path: null
---

## **The Document Menu**

| Document        |
|-----------------|
| Open o          |
| New n           |
| Save s          |
| Save As S       |
| Save To         |
| Save All        |
| Revert to Saved |
| (add here)      |
| Close           |

This menu contains commands that affect a document as a whole. Commands affecting selected contents of a document are mainly in the Edit menu. Applications that don't open or save documents of some kind and don't have a New command don't have this menu.

The title of this menu (the second command in the main menu) should indicate the kind of thing that the Open command opens and the Save command saves. It might be Document, Project, File, Model (for spreadsheets), Game (for games), or Shell (for a terminal emulator). Never call this menu Window, since a Windows menu is standard in most applications.

| Command | Action                                                                                                                                                                                                                                                                                                                                                                      |
|---------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Open    | Brings up the Open panel so the user can open a file. Opening a file<br>also opens a window (or windows) to display it in.                                                                                                                                                                                                                                                  |
| New     | Opens a new, unnamed file and a window to display it in. This new<br>document should be in the same folder as would be displayed in the<br>Open panel. (See the section "Using the Open Panel" in Chapter 5.)                                                                                                                                                               |
| Save    | Saves any changes in the document displayed in the current main<br>window to a file (writes them to the disk). If the document has never<br>been saved to disk, this command should have the same effect as the<br>Save As command.                                                                                                                                         |
| Save As | Saves the document displayed in the main window, as changed, by<br>writing it to a new file with a name supplied by the user. The<br>document displayed in the main window corresponds to the new file,<br>and the window's title is changed accordingly. This command<br>places a Save panel on-screen that asks the user to type in a file name<br>or cancel the command. |

*(continued)* 

| Command         | Action                                                                                                                                                                                                                                                                                                                                                                   |
|-----------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Save To         | Saves the document displayed in the main window, as changed, by<br>writing it to a new file with a name supplied by the user. In this<br>respect, Save To is identical to the Save As command. However,<br>Save To doesn't replace the window's current file with the new one.<br>You can choose whether to implement Save As or Save To or both in<br>your application. |
| Save All        | Saves every document that's open in the application. This is a<br>shortcut for performing the Save command on every open document.                                                                                                                                                                                                                                       |
| Revert to Saved | Replaces the current version of the document displayed in the main<br>window with the version saved on disk. This undoes any changes<br>made to the document since it was last saved.                                                                                                                                                                                    |
| Close           | Closes the document in the main window, and all the windows used<br>to display that document. In other words, it's completely parallel to<br>the Open command. See "The Windows Menu," later in this chapter,<br>for information on a related command, Close Window.                                                                                                     |

If an application uses more than one window to display a document, it could add a Miniaturize command to miniaturize all the windows associated with the currently selected document (the document of the key window) into a single miniwindow. A standard command already exists (Miniaturize Window in the Windows menu) to miniaturize a single window.