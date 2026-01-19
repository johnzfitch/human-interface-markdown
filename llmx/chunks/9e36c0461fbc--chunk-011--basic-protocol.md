---
chunk_index: 111
ref: "9e36c0461fbc"
id: "9e36c0461fbc918e6ea34fa5ba86b85122833c727f1765bd44e723c6a9a5d122"
slug: "chunk-011--basic-protocol"
path: "marker/1982 Apple IIe Design Guidelines/chunks/chunk_011.md"
kind: "markdown"
lines: [4, 11]
token_estimate: 110
content_sha256: "af4e2cc92161c90e48a10782f5e14c4f89bab2a0ff16978263aa3927ca0f6b20"
compacted: false
heading_path: ["BASIC Protocol"]
symbol: null
address: null
asset_path: null
---

#### BASIC Protocol  
The BASIC protocol is very simple; it requires that three entry points be found at fixed locations for a card in slot s:  
| Address | Contains                           |
|---------|------------------------------------|
| \$Cs00  | initialization routine entry point |
| \$Cs05  | input routine entry point          |
| \$Cs07  | output routine entry point         |
|         |                                    |