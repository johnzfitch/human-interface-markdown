---
chunk_index: 4184
ref: "5578c5e448a6"
id: "5578c5e448a6ea783709f6c6ab73a744e68de8431185f84d7fe1e65164f4872e"
slug: "full-document--the-i-nterface-to-the-file-system"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [3016, 3023]
token_estimate: 272
content_sha256: "0032f2e293426fb2d84aaa57935e40c9561490e270bde583ebdb4cf6f88be409"
compacted: false
heading_path: ["*The I nterface to the File System*"]
symbol: null
address: null
asset_path: null
---

# *The I nterface to the File System*

One of the goals of the NeXTSTEP user interface is to provide a simple, graphical interface to the UNIX operating system. This is largely the responsibility of the Workspace Manager, the application that's brought to the screen after the user logs in. More specifically, the Workspace Manager provides a graphical interface to the file system. It's a substitute for a UNIX command interpreter (or shell) that locates files, displays folder contents, associates files with applications and icons, starts up applications, and keeps track of the user's home folder and working environment. It lets users manage files by manipulating their iconic representations.

For command-line interaction with the operating system, users can put up a window that emulates a VT-I 00 terminal and runs a standard shell. This window is provided by the Terminal application, which can be started up from the Workspace Manager.

Terminal is documented in the *NeXTSTEP Development Tools and Techniques* manual. The Workspace Manager is documented in the *User's Guide.*