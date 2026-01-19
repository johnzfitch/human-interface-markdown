---
chunk_index: 3727
ref: "880fcbdd4d00"
id: "880fcbdd4d00d0ce0c4f8699addc2cf9fc5d34d4bff78fe4e2e48b1c8285ca4a"
slug: "chunk-117--programming-note-implementing-on-line-help"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_117.md"
kind: "markdown"
lines: [4, 11]
token_estimate: 433
content_sha256: "3f13eaa13413786e817e170bbffca6a33ce68eed7079cd2eb389055cec32639a"
compacted: false
heading_path: ["**Programming Note: Implementing On-Line Help**"]
symbol: null
address: null
asset_path: null
---

#### **Programming Note: Implementing On-Line Help**  
The Help panel is one part of NeXTSTEP support for on-line help. Other support includes:  
- A question mark cursor that appears when the user presses the Help key (or on keyboards without a Help key, when both the Alternate and Control keys are pressed)
- An easy way to connect interface objects with help text, so that when the user Help-clicks an object, information about the object automatically appears in the Help panel
- Built-in help for basic tasks (such as using menus and operating scrollers)  
To add help to an application, you first add a help folder using Project Builder. This help folder includes template files for the Help panel's index and table of contents. You can create and modify these and other help files, along with the help links in them, with developer-mode Edit. Both Interface Builder and the Application Kit have support for associating help with the user interface objects in your application.  
For more information on implementing on-line help, see the NXHelpPanel discussion in the NeXTSTEP General Reference.  
If your application uses the Help panel, it should also support Help-clicking of its objects. (Otherwise, when the user Help-clicks an object, the Help panel will come up but will likely show inappropriate help.) Help-clicking an object results in the panel automatically displaying the most specific help available. For example, when the user Help-clicks a button, the help system first looks to see whether the button has help associated with it; if so, the Help panel displays it. If not, the help system looks for more general help, such as that associated with the window or even the application that the button is in.