---
chunk_index: 4000
ref: "64b487428b19"
id: "64b487428b1925506d0b82e842888d8e5e7975d2eac9333d004da5a2e0546854"
slug: "full-document--using-the-alternate-key"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [917, 928]
token_estimate: 270
content_sha256: "af4e7b5973ffdcfb69a60e61e3ab35546152f287ae147b30e6dba7406be5aa20"
compacted: false
heading_path: ["*Introduction*","**Creating Application-Specific Keyboard Alternatives**","**Choosing the Character**","**Using the Alternate Key·**"]
symbol: null
address: null
asset_path: null
---

#### **Using the Alternate Key·**

If necessary, your application can use the Alternate key with the Command key for keyboard alternatives. Using the Alternate key is not desirable. You should first exhaust all reasonable possibilities using the Command key alone or in combination with the Shift key before resorting to the Alternate key.

But, when necessary, a keyboard alternative requiring the Alternate key can be used. It should be displayed in italic.

![](images/_page_50_Picture_1.jpeg)

The character displayed in italic is the one that would be typed if the Command and Alternate keys were not held down, not the character that's produced when the Alternate key is held down.

**Note:** Recognizing keyboard alternatives produced with the Alternate key is difficult to implement, and the meaning of italic characters in menus isn't explained in the NeXTSTEP user documentation. If you nevertheless choose to implement keyboard alternatives with the Alternate key, make sure that the documentation for your application explains the meaning of the italicized character.