---
chunk_index: 181
ref: "50af764e1b30"
id: "50af764e1b30bd20a4a4d97f84e18e475d4147402e836f5509ba1b8f4a2f9d03"
slug: "full-document--basic-protocol"
path: "marker/1982 Apple IIe Design Guidelines/full_document.md"
kind: "markdown"
lines: [171, 181]
token_estimate: 109
content_sha256: "4d0251e12570be85e9b1665562178fdadb437cd8a9e0cc4769d3cd621eb4f9e0"
compacted: false
heading_path: ["Peripheral Card Firmware","BASIC Protocol"]
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