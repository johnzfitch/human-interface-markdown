---
chunk_index: 1860
ref: "0ba31b15415c"
id: "0ba31b15415cfe28a87a3d9b8d57b93fe567b5c9526e353fc8f6e17069d5b8e7"
slug: "full-document--modelessness"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/full_document.md"
kind: "markdown"
lines: [576, 603]
token_estimate: 758
content_sha256: "5ec16f581c2b9c454a6fc7824a397ae1e3dcd8328e49c249a6fc7f555e96834d"
compacted: false
heading_path: ["Modelessness"]
symbol: null
address: null
asset_path: null
---

# Modelessness

With few exceptions, a given action on the user's part should always have the same result, irrespective of past activities.

Modes are contexts in which a user action is interpreted differently than the same action would be interpreted in another context. In other words, the same action, when completed in two different modes, results in two different reactions. A mode typically restricts the operations that the user can perform while the mode is in effect.

Because people don't usually operate modally in real life, dealing with modes in computer environments gives the impression that computers are unnatural and unfriendly.

A mode is especially confusing when the user enters it unintentionally. When this happens, familiar objects and commands may take on unexpected meanings and the user's habitual actions cause unexpected results.

Most conventional software uses modes heavily. It's tempting to use modes because they sometimes make programming easier. But if you yield to the temptation too frequently, users will consider using your application a chore rather than a satisfying experience.

This is not to say that you should never use modes in applications. Sometimes a mode is the best way out of a particular problem. Most of these acceptable modes fall into one of the following categories:

- Long-term modes, such as doing word processing as opposed to graphics editing. In this sense, each application is a mode.
- D Short-term "spring-loaded" modes, in which the user must constantly do something to maintain the mode. Examples would be holding down the mouse button to scroll text or holding down the Shift key to extend <sup>a</sup> text selection.
- Alert modes, in which the user must rectify an unusual situation before proceeding. Keep these modes to a minimum.

Other modes are acceptable if they do one of the following:

- They emulate a familiar real-life situation that is itself modal. For example, choosing different tools in a graphics application resembles the real-life choice of physical drawing tools. MacPaint and other palette-based applications exemplify this use of modes.
- They change only the attributes of something, but not its behavior. The boldface and underline modes of text entry are examples.
- They block most other normal operations of the system to emphasize the modality, as in error conditions incurable through software (for example, a dialog box that disables all menu items except Close).

If an application uses modes, there must be a clear visual indication of the current mode, and the indicator should be near the object most affected by the mode. A good example is the changing pointer in MacPaint: it looks like a pencil, paintbrush, spray can, or eraser, depending on the function ("mode") the user has chosen. It should also be very easy to get into or out of the mode (such as by clicking on <sup>a</sup> different palette symbol).

No mode should ever prevent <sup>a</sup> user from saving <sup>a</sup> document or quitting the application.