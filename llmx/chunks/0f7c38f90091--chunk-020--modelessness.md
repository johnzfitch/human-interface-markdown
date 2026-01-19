---
chunk_index: 1052
ref: "0f7c38f90091"
id: "0f7c38f90091046a728ec16be2bde9189864c9c10f8ca19a343ea6a4dc8920f7"
slug: "chunk-020--modelessness"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/chunks/chunk_020.md"
kind: "markdown"
lines: [6, 21]
token_estimate: 748
content_sha256: "86f577e1b8876374c079152245d6eb4aa03b6c736afa79d207bffe710c20a021"
compacted: false
heading_path: ["Modelessness"]
symbol: null
address: null
asset_path: null
---

#### Modelessness  
With few exceptions, a given action on the user's part should always have the same result, irrespective of past activities.  
Modes are contexts in which a user action is interpreted differently than the same action would be interpreted in another context. In other words, the same action, when completed in two different modes, results in two different reactions. A mode typically restricts the operations that the user can perform while the mode is in effect.  
Because people don't usually operate modally in real life, dealing with modes in computer environments gives the impression that computers are unnatural and unfriendly.  
A mode is especially confusing when the user enters it unintentionally. When this happens, familiar objects and commands may take on unexpected meanings and the user's habitual actions cause unexpected results.  
Most conventional software uses modes heavily. It's tempting to use modes because they sometimes make programming easier. But if you yield to the temptation too frequently, users will consider using your application a chore rather than a satisfying experience.  
This is not to say that you should never use modes in applications. Sometimes a mode is the best way out of a particular problem. Most of these acceptable modes fall into one of the following categories:  
- Long-term modes, such as doing word processing as opposed to graphics editing. In this sense, each application is a mode.
- Short-term "spring-loaded" modes, in which the user must constantly do something in order to maintain the mode, for example, holding down the mouse button to scroll text or holding down the Shift key to extend a text selection.
- Alert modes, where the user must rectify an unusual situation before proceeding. Keep these modes to a minimum.  
Other modes are acceptable if they do one of the following:  
- They emulate a familiar real-life situation that is itself modal. For example, choosing different tools in a graphics editor resembles the real-life choice of physical drawing tools. MacPaint and other palette-based applications exemplify this use of modes.
- They change only the attributes of something, but not its behavior. The boldface and underline modes of text entry are examples.  
They block most other normal operations of the system to emphasize the modality, as in error conditions incurable through software (for example, a dialog box that disables all menu items except Close).  
If an application uses modes, there must be a clear visual indication of the current mode, and the indicator should be near the object most affected by the mode. A good example is MacPaint's changing pointer, which looks like a pencil, paintbrush, spray can, or eraser, depending on the function ("mode") the user has chosen. It should also be very easy to get into or out of the mode (such as by clicking on a different palette symbol).  
No mode should ever prevent a user from saving a document or quitting the application.