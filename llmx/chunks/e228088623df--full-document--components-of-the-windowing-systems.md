---
chunk_index: 522
ref: "e228088623df"
id: "e228088623df3e1984de611d67fd0336b3344b7629ee08c893a9dd35b1b058b5"
slug: "full-document--components-of-the-windowing-systems"
path: "marker/1985 Apple II Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [1112, 1129]
token_estimate: 565
content_sha256: "503080215552db5603891af28cb708e157d228770d89b4a085c2f9e237aa0f13"
compacted: false
heading_path: ["COMPONENTS OF THE WINDOWING SYSTEMS"]
symbol: null
address: null
asset_path: null
---

# COMPONENTS OF THE WINDOWING SYSTEMS

This section explains the relationship among the principal large-scale components of the windowing systems (from an external point of view).

The main vehicle for the interaction of the user and the system is the application. Only one application is active at a time. When an application is active, it's in control of all communications between the user and the system. The application's menus are in the menu bar, and the application is in charge of all windows as well as the desktop.

1/15/85 Tognazzini

/INTF/STRUC

To the user, the main unit of information is the document. Each document is a unified collection of information—a single business letter or spreadsheet or chart. A complex application, such as a data base, might require several related documents. Some documents can be processed by more than one application, but each document has a principal application, which is usually the one that created it. The other applications that process the document are called secondary applications.

The only way the user can actually see the document (except by printing it) is through a window. The application puts one or more windows on the screen; each window shows a view of a document or of auxiliary information used in processing the document. The part of the screen underlying all the windows is called the desktop.

At the time of this writing, we have not created tools for making a Macintosh-like Finder to change applications. With such a Finder active, if the user double-clicks on either the application's icon or the icon of a document belonging to that application (or opens the document or application by choosing Open from the File menu), the application becomes active and displays the document window. If you are using the MouseGraphics environment for a integrated software package, you still might want to emulate the Macintosh Finder. If you are writing a text-based integrated application or hard-disk filing system, please contact Apple II technical support to find out what kind of metaphor we are using/recommending.

Internally, applications and documents are both kept in files. However, the user never sees files as such, so they don't really enter into the windowing user interface.