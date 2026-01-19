---
chunk_index: 209
ref: "5592615f727e"
id: "5592615f727eb6a140fc5489b8014d93001a77ee9420a58ed067c384f45791d3"
slug: "full-document--tree-structures"
path: "marker/1982 Apple IIe Design Guidelines/full_document.md"
kind: "markdown"
lines: [615, 618]
token_estimate: 156
content_sha256: "83d397fe01be5652cb85aae30547d59ae40835e2597f67762b4fc016cafe90df"
compacted: false
heading_path: ["Keep It Simple","Intelligence","**Confirmation**","**Tree Structures**"]
symbol: null
address: null
asset_path: null
---

#### **Tree Structures**

The tree structure of a program is designed to feel natural to a user, not the programmer. For example, one could design a program which will both create and play music. Saving created music and loading that music for later playing are highly similar programming tasks and can quite possibly be done using the same basic subroutines. But while it is structurally logical to share code between them, it is intuitively wrong to dump the two options adjacent to each other on a menu. Saving should be grouped with other music-creation options; loading with both creation (for editing), and playing.