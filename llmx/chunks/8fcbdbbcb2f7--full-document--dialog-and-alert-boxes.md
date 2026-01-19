---
chunk_index: 2061
ref: "8fcbdbbcb2f7"
id: "8fcbdbbcb2f74612a7802d056f60ff5d3895a011ca060e5ec089285d73f43be6"
slug: "full-document--dialog-and-alert-boxes"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/full_document.md"
kind: "markdown"
lines: [2732, 2745]
token_estimate: 190
content_sha256: "ae1cd2946fde881d040d5294ed61b746432b30d93a880a9a1190bb1930cdead2"
compacted: false
heading_path: ["Dialog and alert boxes"]
symbol: null
address: null
asset_path: null
---

# Dialog and alert boxes

Give text room to grow during localization. For example, don't create a screen-sized dialog box that is completely filled with text. Most languages require more characters than English does to convey equivalent messages.

When creating parameterized text, be sure the localizer will be able to rearrange the sentence as needed. For example, if an alert box sentence is to say

There was <sup>a</sup> problem doing ^0 to the M

then the localizer will be able to correctly order the noun and prepositional phrase for different languages.

Avoid hard-coding positions for drawing text or graphics. If possible, use a Userltem for positioning or dynamic display or PICT to display static graphics.

![](images/_page_143_Picture_0.jpeg)