---
chunk_index: 112
ref: "3a77c37927b8"
id: "3a77c37927b8a0305fb50eeeff2f2351a1846567cb930426b0f3a1346020c689"
slug: "chunk-011--pascal-1-0-protocol"
path: "marker/1982 Apple IIe Design Guidelines/chunks/chunk_011.md"
kind: "markdown"
lines: [12, 20]
token_estimate: 158
content_sha256: "7c0ed069869c1c3221d9d5e937ad1b6d79d2e2de7829868553fba819e4c2ae0b"
compacted: false
heading_path: ["BASIC Protocol","Pascal 1.0 Protocol"]
symbol: null
address: null
asset_path: null
---

#### Pascal 1.0 Protocol  
There are also three entry points for firmware cards under the Pascal 1.0 protocol:  
| Address    | Contains                           |
|------------|------------------------------------|
| \$ C 8 O O | initialization routine entry point |
| \$C84D     | read routine entry point           |
| \$ C 9 A A | write routine entry point          |
|            |                                    |  
New peripheral cards can be "accepted" into the Pascal 1.0 system by using these entry points, as well as having the values \$38 at location \$0.505 and \$18 at \$0.507 (see Device ID discussion below).