---
chunk_index: 182
ref: "99957de57c92"
id: "99957de57c92c27d194601db8361a9c7bbf5888505807beb982eba7e3d401d59"
slug: "full-document--pascal-1-0-protocol"
path: "marker/1982 Apple IIe Design Guidelines/full_document.md"
kind: "markdown"
lines: [182, 194]
token_estimate: 157
content_sha256: "0d61606f12b298fba906bb49e76cd0ceb6b32023d51ee7028c25f3194bd3cf4b"
compacted: false
heading_path: ["Peripheral Card Firmware","BASIC Protocol","Pascal 1.0 Protocol"]
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