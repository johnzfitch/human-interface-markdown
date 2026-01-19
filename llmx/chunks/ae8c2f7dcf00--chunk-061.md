---
chunk_index: 3648
ref: "ae8c2f7dcf00"
id: "ae8c2f7dcf00ec2bcf35b0e6e27d6e1a876585cfbad5c48d375f649a85bd0029"
slug: "chunk-061"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_061.md"
kind: "markdown"
lines: [1, 5]
token_estimate: 344
content_sha256: "ae68da0fd2e3f9f6558a16b8382a5b9cbb7a9aa525499e1b8cd0a8da77c8714f"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 61 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 317 -->
An application can change the cursor from the standard arrow (shown above) to a'ny other image of an equal size (16 pixels by 16 pixels). When doing so, it must specify what point in the cursor acts like the tip of the arrow. That point, the cursor's *hot spot,* should be apparent to the user from the shape of the image. For example, if the cursor is an X, the hot spot would be where the two lines cross.  
For some types of applications, a shape other than an arrow might be more convenient. For example, an I-beam cursor (shown above) is handier for positioning between characters. Its hot spot is in the center of the beam.  
It's often a good idea to change the shape of the cursor to indicate that the user has entered a mode. In applications that use the modal-tool paradigm, the cursor should change to indicate which tool has been selected. For example, the cursor might look like a pencil while thin lines are being drawn in a graphics application, or like a wide brush when painting in broad strokes.  
If mouse actions are valid only in a certain area, the cursor should revert to its normal shape when it leaves the area. It's best not to change the cursor too often, however. To avoid confusing the user, stick with the standard arrow wherever reasonable.