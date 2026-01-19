---
chunk_index: 521
ref: "1f407f61d844"
id: "1f407f61d8447ed00d74476ac46c6a46299a8e2f6d883ab11485cedaacf2a043"
slug: "full-document--palettes"
path: "marker/1985 Apple II Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [1104, 1111]
token_estimate: 357
content_sha256: "41ffda7f92849e750234d6545e61170e37e429dfb2851099b4582dc4a687a7ee"
compacted: false
heading_path: ["USING GRAPHICS","Icons","Palettes"]
symbol: null
address: null
asset_path: null
---

### Palettes

Some applications use palettes as a quick way for the user to change from one operation to another. A palette is a collection of small squares, each containing a symbol. A symbol can be an icon, a pattern, a character, or just a drawing, that stands for an operation. When the user clicks on one of the symbols, it's distinguished from the other symbols, such as by highlighting, and the previous symbol goes back to its normal state.

Typically, the symbol that's selected determines what operations the user can perform. Selecting a palette symbol puts the user into a mode. This use of modes can be justified because changing from one mode to another is almost instantaneous, and the use can always see at a glance which mode is in effect. Like all modal features, palettes should be used only when they're the most natural way to structure an application.

A palette can either be part of a window (as in MacDraw), or a separate window (as in MousePaint). Each system has its disadvantages. If the palette is part of the window, then parts of the palette might be concealed if the user makes the window smaller. On the other hand, if it's not part of the window, then it takes up extra space on the desktop. If an application supports multiple documents open at the same time, it might be better to put a separate palette in each window, so that a different palette symbol can be in effect in each document.