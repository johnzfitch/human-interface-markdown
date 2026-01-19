---
chunk_index: 217
ref: "cf2a9d370ce0"
id: "cf2a9d370ce00a7994ceb29d55f545a12d9df612313cefc64456e98fdbf038a3"
slug: "full-document--notes"
path: "marker/1982 Apple IIe Design Guidelines/full_document.md"
kind: "markdown"
lines: [687, 706]
token_estimate: 389
content_sha256: "c94e01ed2c889da46d49e11cc9496ab757e28c0bb33bf37c09ed17aa368aed5b"
compacted: false
heading_path: ["The (Pascal) Solid-box Cursor","The New Insert/Delete Cursor","Apple II Series","**Notes**"]
symbol: null
address: null
asset_path: null
---

#### **Notes**

Because this input is new to Apple II and Apple II+ users, it is particularly inportant that you expressly state on the display that CTRL-D is used to delete characters. (Apple IIe users have been trained how to use this input on the APPLE PRESENTS...APPLE diskette, but a reminder to use the DELETE key would be helpful.)

Typing any printing character will automatically insert that character into the input line at the current cursor position.

Pressing RETURN with the cursor anywhere within the input line will accept the entire input.

Default responses are displayed with the cursor at the end of the response.

| RETURN      | will accept that response.                                                                                                |
|-------------|---------------------------------------------------------------------------------------------------------------------------|
| LEFT-ARROW  | will move cursor back into the default response, enabling the user to edit it.                                            |
| RIGHT-ARROW | will signal that you wish to append material to the response.                                                             |
| CTRL-D      | (Apple II & II+) will delete a single character from the end of a response and signal that you wish to edit the response. |

DELETE (Apple IIe) will delete a single character from the end of the response and signal that you wish to edit the response.

Pressing any other key will clear the default response and begin a new response in its place.