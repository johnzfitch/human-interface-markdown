---
chunk_index: 176
ref: "4ab69240d53f"
id: "4ab69240d53f4823feeaa6447cc82961f0989c27416b17682f277d6ff61d0726"
slug: "full-document--new-reset-features"
path: "marker/1982 Apple IIe Design Guidelines/full_document.md"
kind: "markdown"
lines: [119, 125]
token_estimate: 146
content_sha256: "47b6e8cb578add6cc6de1139880761d79371582f3b363f539baf679081c58940"
compacted: false
heading_path: ["Introduction","Software","New RESET Features"]
symbol: null
address: null
asset_path: null
---

### New RESET Features

The Apple IIe has all 64K of its memory in RAM. A reset now affects the contents of what used to be the "language card" area of main memory.

- Do not require the use of the RESET key during program operation unless you are not concerned that the bank-switched RAM (former language card addresses) will be switched out.
- Have BASIC or assembly language programs start up using the OPEN-APPLE CONTROL-RESET sequence rather than PR#s (slot s for the startup disk drive). This recommendation is related to the requirements of the new Apple 80-column text cards.