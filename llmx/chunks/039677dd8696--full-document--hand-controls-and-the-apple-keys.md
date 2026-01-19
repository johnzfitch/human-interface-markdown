---
chunk_index: 178
ref: "039677dd8696"
id: "039677dd86963587360a2b91d22d99fa56bf9a1c1cd68066a1044aa23f2a70ef"
slug: "full-document--hand-controls-and-the-apple-keys"
path: "marker/1982 Apple IIe Design Guidelines/full_document.md"
kind: "markdown"
lines: [143, 146]
token_estimate: 121
content_sha256: "c9504ee560070c6da06612f844749e250d4422f38b3272fef9ec5053f2e59bf5"
compacted: false
heading_path: ["New Apple 80-Column Text Cards","Hand Controls and the APPLE Keys"]
symbol: null
address: null
asset_path: null
---

## Hand Controls and the APPLE Keys

The new OPEN-APPLE key is connected to the pushbutton of hand control #0, and the new SOLID-APPLE key is connected to the pushbutton of hand control #1. Therefore, do not have a program check for the absence of hand controls by checking whether both pushbuttons have been pressed. Instead, have the program wait for a count of 512 (twice the normal count) and see if the hand control timer has timed out. If not, no hand controls are connected.