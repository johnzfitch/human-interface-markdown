---
chunk_index: 184
ref: "81297d6d8394"
id: "81297d6d8394ce020c100844aa614dc62f40245642ae4177e73eac72ea484847"
slug: "full-document--hardware"
path: "marker/1982 Apple IIe Design Guidelines/full_document.md"
kind: "markdown"
lines: [256, 267]
token_estimate: 333
content_sha256: "869cf62655b63c66191579819b6a66addddd53247f1a26f2ce2513d4e08189c4"
compacted: false
heading_path: ["Peripheral Card Firmware","Hardware"]
symbol: null
address: null
asset_path: null
---

## Hardware

The Apple IIe Reference Manual specifies the overall physical and electrical characteristics of peripheral cards disigned for use with the Apple IIe computer. In addition to these requirements, some detailed guidelines apply:

- To maintain a consistent installation procedure as well as avoid interference with adjacent cards, always design cards so their component sides face away from the power supply case.
- Avoid designs that require connection to chip sockets on the main circuit board, as future revisions to the board may make such cards obsolete.
- Do not require that a card be installed in slot 3 if its intended application can involve a text or video card in the AUX CONNECTOR slot.
- 4. Cards should not dissipate more than the amount of power specified in Chapter 7 of the Apple IIe Reference Manual.
- 5. Cables should use 9-pin or 25-pin "DB" style connectors. The four 19-pin openings (1 through 4) on the back panel are reserved for use with disk drives.
- 6. Internal cables should preferably connect to the keyboard end of the card. This gives the user more freedom in selecting a slot to install the card. It also alleviates strain and bending on the cable.
- 7. Cards that have firmware on them should be identifiable according to the protocols outlined in the Firmware section preceding this.