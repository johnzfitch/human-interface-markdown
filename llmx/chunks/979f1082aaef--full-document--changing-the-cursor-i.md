---
chunk_index: 4015
ref: "979f1082aaef"
id: "979f1082aaef9b008be2d8730dba29d17d29a75d1a91e136ed77a761bf1593fb"
slug: "full-document--changing-the-cursor-i"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1072, 1081]
token_estimate: 325
content_sha256: "bd71b8fb8efe63ce7d15ff64fdc4da41ff54709d00ad9db12ee37617794ebb12"
compacted: false
heading_path: ["*Introduction*","**Changing the Cursor** ~ I"]
symbol: null
address: null
asset_path: null
---

## **Changing the Cursor** ~ I

An application can change the cursor from the standard arrow (shown above) to a'ny other image of an equal size (16 pixels by 16 pixels). When doing so, it must specify what point in the cursor acts like the tip of the arrow. That point, the cursor's *hot spot,* should be apparent to the user from the shape of the image. For example, if the cursor is an X, the hot spot would be where the two lines cross.

For some types of applications, a shape other than an arrow might be more convenient. For example, an I-beam cursor (shown above) is handier for positioning between characters. Its hot spot is in the center of the beam.

It's often a good idea to change the shape of the cursor to indicate that the user has entered a mode. In applications that use the modal-tool paradigm, the cursor should change to indicate which tool has been selected. For example, the cursor might look like a pencil while thin lines are being drawn in a graphics application, or like a wide brush when painting in broad strokes.

If mouse actions are valid only in a certain area, the cursor should revert to its normal shape when it leaves the area. It's best not to change the cursor too often, however. To avoid confusing the user, stick with the standard arrow wherever reasonable.