---
chunk_index: 177
ref: "823a4955b631"
id: "823a4955b631e676842913c454c25cc19542d28dc9255233243d2be827f416bf"
slug: "full-document--new-apple-80-column-text-cards"
path: "marker/1982 Apple IIe Design Guidelines/full_document.md"
kind: "markdown"
lines: [126, 142]
token_estimate: 442
content_sha256: "5514a76ad1485e9413168e872ee4268ec4a5e8610e3712c76967d1b9eb4b4afb"
compacted: false
heading_path: ["New Apple 80-Column Text Cards"]
symbol: null
address: null
asset_path: null
---

# New Apple 80-Column Text Cards

These guidelines apply to BASIC and assembly language programs and their calls to Monitor service routines.

 Have any greeting program's first action be to determine if an 80-column text card is in the system (see Peripheral Card Firmware section below for identification methods).

- 2. Make sure that an 80-column card is installed before attempting to turn it on; otherwise, unpredictable system conditions may result.
- 3. To turn on the Apple Ile 80-column firmware, use PR#3 or the equivalent. The Apple 80-column firmware is associated with slot 3 for compatibility with the Apple Pascal Operating System.
- 4. Do not use PR#0 to turn off the 80-column firmware. To turn it off, issue a CONTROL-U (NAK character; decimal code 21).
- 5. Never have a program issue a PR#0 or IN#0 while the 80-column firmware is active.
- 6. Before sending output to devices other than the video display, issue a CONTROL-L (Form Feed character, decimal code 12) to clear the screen, then a CONTROL-U to turn off the 80-column firmware.
- If the 80-column firmware is active, look at location 49152 (\$C000) directly to check for a keypress. If you use the BASIC GET command or the Monitor KEYIN routine, each Esc keypress will be executed before its modifying escape code can be retrieved.
- 8. If the 80-column firmware is active, a program should not attempt to display flashing lowercase characters; they are not available in the alternate character set.
- 9. If your software turns on the 80-column firmware, be sure it turns it off before ending.

The Pascal Operating System automatically checks for the presence of an 80-column text card in slot 3 or the AUX CONNECTOR slot, and turns on the 80-column firmware if such a card is present.