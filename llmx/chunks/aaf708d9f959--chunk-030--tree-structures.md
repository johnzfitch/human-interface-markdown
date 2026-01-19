---
chunk_index: 136
ref: "aaf708d9f959"
id: "aaf708d9f95989c92d1c04f51d1ed83579eab0a74cb025c61c2b2f0fe7dd1b63"
slug: "chunk-030--tree-structures"
path: "marker/1982 Apple IIe Design Guidelines/chunks/chunk_030.md"
kind: "markdown"
lines: [7, 8]
token_estimate: 156
content_sha256: "c5db32f92c72f056e45cc6e33446c0971ed2f637a9aab54986cd185ed429e0b9"
compacted: false
heading_path: ["**Confirmation**","**Tree Structures**"]
symbol: null
address: null
asset_path: null
---

#### **Tree Structures**  
The tree structure of a program is designed to feel natural to a user, not the programmer. For example, one could design a program which will both create and play music. Saving created music and loading that music for later playing are highly similar programming tasks and can quite possibly be done using the same basic subroutines. But while it is structurally logical to share code between them, it is intuitively wrong to dump the two options adjacent to each other on a menu. Saving should be grouped with other music-creation options; loading with both creation (for editing), and playing.