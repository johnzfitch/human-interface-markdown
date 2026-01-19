---
chunk_index: 2630
ref: "ced272141dd7"
id: "ced272141dd762c429c4b64af0b835950cabc815f8f5912d60e53c9e63f2e619"
slug: "full-document--modelessness"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [736, 754]
token_estimate: 616
content_sha256: "eb08869fbb143d1316032388a53538063a6aef11e0fd0ea850ef1346614b13aa"
compacted: false
heading_path: ["The Human Interface Design Principles","Modelessness"]
symbol: null
address: null
asset_path: null
---

## Modelessness

For the most part, try to create modeless features that allow people to do whatever they want when they want to in your application. Avoid using modes in your application because a mode typically restricts the operations that the user can perform while it is in effect. It locks the user into one operation and doesn't allow the user to work on anything else until that operation is completed. In contrast, modelessness allows the user to perform more than one operation at a time and thus gives the user more control over what he or she can do on the computer and in an application. As much as possible, you want to preserve the user's ability to be in control of the task and the order of operations.

This is not to say that you should never use modes in applications. Sometimes using a mode is the best way out of a particular problem. Most acceptable modes fall into one of the following categories:

Long-term modes, such as doing word processing as opposed to graphics editing. In this sense, each application is a mode.

- Short-term "spring-loaded" modes, in which the user must constantly do something to maintain the mode. Examples are holding down the mouse button to scroll text or holding down the Shift key to extend a text selection.
- Alert modes, in which the user must rectify an unusual situation before proceeding. Keep these modes to a minimum.

Other modes are acceptable if they do one of the following:

- They emulate a familiar real-life situation that is itself modal. For example, choosing different tools in a graphics application resembles the real-life choice of physical drawing tools.
- They change only the attributes of something, not its behavior. The boldface and underline modes of text entry are examples.
- They block most other normal operation of the system to emphasize the modality, as in error conditions incurable through the software (for example, a dialog box that disables all menu items except Close).

If an application uses modes, there must be a clear visual indicator of the current mode, and the indicator should be near the object most affected by the mode. A good example is the changing pointer in many Macintosh graphics applications; depending on the function ("mode") the user has selected, the pointer looks like a pencil, a paintbrush, a spray can, or an eraser. It should also be very easy for users to get into or out of the mode (such as by clicking a different palette symbol).