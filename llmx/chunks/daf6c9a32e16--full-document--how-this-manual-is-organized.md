---
chunk_index: 3937
ref: "daf6c9a32e16"
id: "daf6c9a32e16a8443b549b099e98c2de1dd331277ebe70da0eed0e741abf4a1b"
slug: "full-document--how-this-manual-is-organized"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [290, 308]
token_estimate: 586
content_sha256: "2fe738bb0c03e951b6b6bb990d4c0ec87dde682a41e211e7aea9695c027014f9"
compacted: false
heading_path: ["*Introduction*","**How This Manual is Organized**"]
symbol: null
address: null
asset_path: null
---

## **How This Manual is Organized**

Much of the functionality and appearance of the NeXTSTEP user interface is built into the Window Server and Application Kif .... You won't need to program the complete interface for your application; windows, buttons, scrollers, and other graphic objects are provided for you. For this reason, discussions with detailed guidelines are divided into two major parts:

- The first part discusses the functionality that's built in.
- The second part describes what you have to do.

Some chapters also have a third part that lists standard objects (which you might or might not have to implement) that you can use in your application. For example, Chapter 5, "Panels," lists all the standard panels, such as the Info panel, Print panel, and Quit panel.

When thinking about putting a panel in your application, you should make sure to use a standard panel if it's appropriate.

The first two chapters of this book offer an overview of the NeXTSTEP user interface. Chapter 1, "A Visual Guide to the User Interface," shows what the standard objects in the user interface look like. Chapter 2, "Design Philosophy," discusses the guiding principles behind the user interface. You need a good understanding of these principles to be able to develop NeXTSTEP applications that have a great user interface.

The next two chapters give guidelines for the most basic aspects of communicating with the user. Chapter 3, "User Actions: The Keyboard and Mouse," discusses how to interpret mouse and keyboard actions. Chapter 4, "The Window Interface to Applications," discusses how windows (which contain the bulk of the information you present to the user) should work.

The next three chapters give detailed guidelines for implementing standard NeXTSTEP objects: panels, menus, and controls. Chapter 5, "Panels," gives guidelines about implementing panels, in general, and then goes into detail about what you have to do to implement standard panels. Chapter 6, "Menus," does the same for menus. Chapter 7, "Controls," discusses each control in tum, describing how it works and what you must do to implement it. It then summarizes what controls you should use under which circumstances.

Finally, the last chapter, "The Interface to the File System," gives details about how your application should treat files and folders.