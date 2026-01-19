---
chunk_index: 2638
ref: "2b4b1474120a"
id: "2b4b1474120abadd54762578e88bd3c27ff381cc45cfd3b8a518cf78dec4b0b1"
slug: "full-document--text-display-and-text-editing"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [825, 837]
token_estimate: 323
content_sha256: "6e8541b85c64befbe408e7963a30cb5a5b4954a5bb134b4ec3a6b5d4441a0c08"
compacted: false
heading_path: ["Worldwide Compatibility","Text Display and Text Editing"]
symbol: null
address: null
asset_path: null
---

## Text Display and Text Editing

Macintosh system software allows users to display different scripts at the same time. A script system consists of resources that support a writing system for a human language. Writing systems may differ in the direction in which their characters and lines flow, the size of the character set used, and whether certain characters are context dependent. Whenever a user installs a non-Roman script system, at least two scripts are available, the Roman script that is present on all Macintosh computers and the non-Roman script.

No matter what level of worldwide text support you provide, it's important to avoid four common assumptions:

- Characters aren't necessarily 1 byte; they can be 2 bytes.
- Text isn't always left-aligned and read from left to right.
- Text isn't always read by a person; it may be spoken through a text-to-speech converter.
- System and application fonts aren't always Chicago and Geneva.

For specific instructions on how to handle 2-byte character codes, cursor controls, multiple sets of numerals, tokens, and highlighting mixed-directional text, see *Inside Macintosh: Text.* In addition, see that book and the chapter on worldwide software in *Inside Macintosh: Overview*  for thorough discussions of text display and editing.