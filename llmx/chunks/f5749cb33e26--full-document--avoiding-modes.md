---
chunk_index: 515
ref: "f5749cb33e26"
id: "f5749cb33e26804b65b19d5af3765889501d0000ac81b4786982aa05aa8fe74e"
slug: "full-document--avoiding-modes"
path: "marker/1985 Apple II Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [998, 1035]
token_estimate: 750
content_sha256: "e7a1c02b3d3360ec6aa738d71e31894d28b15180dad075a012f5aa6b19243d67"
compacted: false
heading_path: ["Avoiding Modes"]
symbol: null
address: null
asset_path: null
---

# Avoiding Modes

"But, gentlemen, you overdo the mode."

-- John Dryden, <u>The</u>
<u>Assignation</u>, <u>or Love in a</u>
<u>Nunnery</u>, 1672

A mode is a part of an application that the user has to formally enter and leave, and that restricts the operations that can be performed while it's in effect. Since people don't usually operate modally in real life, having to deal with modes in computer software reinforces the idea that computers are unnatural and unfriendly.

Modes are most confusing when you're in the wrong one. Unfortunately, this is the most common case. Being in a mode is confusing because it makes future actions contingent upon past ones; it changes the behavior of familiar objects and commands; and it makes habitual actions cause unexpected results.

It's tempting to use modes in a windowing application, since most existing software leans on them heavily. If you yield to the temptation too frequently, however, users will consider spending time with your application a chore rather than a satisfying experience.

This is not to say that modes are never used in windowing applications. Sometimes a mode is the best way out of a particular problem. Most of these modes fall into one of the following categories:

- Long-term modes with a procedural basis, such as doing word processing as opposed to graphics editing. Each application program is a mode in this sense.
- Short-term "spring-loaded" modes, in which the user is constantly doing something to perpetuate the mode. Holding down the mouse button or a key is the most common example of this kind of mode.
- Alert modes, where the user must rectify an unusual situation before proceeding. These modes should be kept to a minimum.

Other modes are acceptable if they meet one of the following requirements:

1/15/85 Tognazzini

/INTF/INTRO

INTRODUCTION 61

- They emulate a familiar real-life model that is itself modal, like picking up different-sized paintbrushes in a graphics editor.

  MousePaint and other palette-based applications are examples of this use of modes.
- They change only the attributes of something, and not its behavior, like the boldface and underline modes of text entry.
- They block most other normal operations of the system to emphasize the modality, as in error conditions incurable through software ("There's no disk in the disk drive", for example).

If an application uses modes, there must be a clear visual indication of the current mode, and the indication should be near the object being most affected by the mode. It should also be very easy to get into or out of the mode (such as by clicking on a palette symbol).

Several features of the keyboard (mouseless) interface are modal. For example, the cursor keys are usually redefined, along with Escape and Return being used as mode-terminators. However, every effort has been made to limit both the extent of this modality to only these keys, and to be consistent in the kind of behavior changes that the user can expect.