---
chunk_index: 301
ref: "ca771785f242"
id: "ca771785f2420ab2922267321d19e51ac0bfcfd72b3a65472046bf1a1cab53a1"
slug: "full-document--details"
path: "marker/1983 Lisa UI Guidelines/full_document.md"
kind: "markdown"
lines: [270, 273]
token_estimate: 75
content_sha256: "48e79ea96ad7a93ae83f3953fff0adad268eeb6a18920e0dcf4f4577d0fcbbeb"
compacted: false
heading_path: ["Chapter 5 Desktop Manager","5.2.3 Set Aside","5.2.4 Save & Continue","Details:"]
symbol: null
address: null
asset_path: null
---

#### Details:

Implementation: By default, an active document has two files associated with it: The Save file, written to only when the document is saved, and the Suspend file, which contains the document heap and which is swapped out from time to time. Saving the document deletes the Suspend file.