---
chunk_index: 135
ref: "81040fac138d"
id: "81040fac138dfb878514533b5c6a62546848d0c575a49fa2351fa673aee28bef"
slug: "chunk-030--confirmation"
path: "marker/1982 Apple IIe Design Guidelines/chunks/chunk_030.md"
kind: "markdown"
lines: [3, 6]
token_estimate: 155
content_sha256: "e167cb02571578e89068551cbfc54fee33aa98a7d2286dd43bd20fe0d94dbcdd"
compacted: false
heading_path: ["**Confirmation**"]
symbol: null
address: null
asset_path: null
---

#### **Confirmation**  
The program tries to prevent catastrophic errors. If the user commands that a 100K text file be deleted, the program should require cognizant confirmation:  
Are you sure you want to destroy 5 days' work? Type DESTROY 5 DAYS' WORK to confirm.  
If the user commands that a new file be saved under a name already being used for a 100K text file, the program will announce that saving the file under this name will result in the destruction of the original file, and then present a confirmation question similar to the one above if the user says to save the file under the duplicate name anyway.