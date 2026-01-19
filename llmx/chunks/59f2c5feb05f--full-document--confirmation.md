---
chunk_index: 208
ref: "59f2c5feb05f"
id: "59f2c5feb05fe85189fcb01e2fbbefcaad3c1e9b157dd71af63af6f78e6a8315"
slug: "full-document--confirmation"
path: "marker/1982 Apple IIe Design Guidelines/full_document.md"
kind: "markdown"
lines: [607, 614]
token_estimate: 154
content_sha256: "45b7ba268c7ae30a26e5d8bf6a3addf2343098340e1c434dd76658c82fb47b96"
compacted: false
heading_path: ["Keep It Simple","Intelligence","**Confirmation**"]
symbol: null
address: null
asset_path: null
---

#### **Confirmation**

The program tries to prevent catastrophic errors. If the user commands that a 100K text file be deleted, the program should require cognizant confirmation:

Are you sure you want to destroy 5 days' work? Type DESTROY 5 DAYS' WORK to confirm.

If the user commands that a new file be saved under a name already being used for a 100K text file, the program will announce that saving the file under this name will result in the destruction of the original file, and then present a confirmation question similar to the one above if the user says to save the file under the duplicate name anyway.