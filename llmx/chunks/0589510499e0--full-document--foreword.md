---
chunk_index: 817
ref: "0589510499e0"
id: "0589510499e0d1f96bc423ec17f228dbc8106c82d4fc4d578d54c4a882b1c8d9"
slug: "full-document--foreword"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/full_document.md"
kind: "markdown"
lines: [289, 308]
token_estimate: 931
content_sha256: "5f885ae46432599b5a7ca8808f6c9cc22826d50ea7f8c92692fcd9f37c8c8ef1"
compacted: false
heading_path: ["Foreword"]
symbol: null
address: null
asset_path: null
---

# Foreword

This book provides guidelines for creating pleasing, useful, consistent, easy-to-learn software for any computer in the Apple® product line, and provides the rationale behind the Apple desktop interface. Various Apple hardware systems can accommodate this interface in varying degrees. Because of the abundance of tools in its ROM, the Macintosh<sup>TM</sup> system is the one in which this interface is most fully implemented.

There are two major advantages to using ROM-based tools and resources: compatibility and efficiency. The more a program bypasses or replaces these tools or resources, the more likely that sooner or later it will become incompatible with new products or new features. Though you may know a more direct way of getting the information, or a faster way of doing the operation, it's best to use the system-provided features that will ensure hardware independence. You should, for example, access the variable that gives you the current size of the screen rather than hard-coding screen constants into the program. You can also write your program so that it can access, through device drivers, any peripheral device that happens to be installed on the computer being used—even peripherals that aren't yet developed. And don't write new code if you don't have to—find out what wheels have already been invented for your computer, and use them!

A human interface is not merely a visual display—in fact, it is possible to have a human interface with no visual display at all. A human interface is the sum of all communication between the computer system and the user. It is the part of the system that presents information to the user and accepts information from the user. It is the way in which the user accesses the functionality of the computer.

The human interface comprises features that are generally applicable to a variety of applications, but not all of the features are found in every application. In fact, some features are hypothetical because they *anticipate* future needs, and may not be found in any current applications.

You'll get the most from this book if you already have some experience with a desktop—based Finder program and with some application programs that use windows, pull-down menus, and a mouse—preferably one each of a word processor, a spreadsheet or data base, and a graphics application. You should also be familiar with the concepts of pointing, clicking, and dragging with the mouse.

Although you can find examples of most of the features described in this book by looking at existing applications, no one program has fully implemented these guidelines, and perhaps none ever will. Taken together, MacWrite, MacPaint, and MacDraw come close to containing the full set of features as implemented on the Macintosh computer. While there are some very good programs that deviate in some degree from these guidelines, emulate them only with good reason. The interface, and therefore these guidelines, will continue to evolve as Apple, and you, learn more about how people use computers.

You'll find detailed implementation specifications in the technical documentation for the particular Apple computer for which you're developing software. You can also contact Apple Developer Relations about becoming a registered developer.

Remember that there are programming environments (as opposed to application programs) that use human interface techniques that may be inappropriate paradigms for application programs.

The best time to familiarize yourself with the human interface is *before beginning to design* an application. Good application design happens when a software developer has absorbed the spirit as well as the details of the human interface.