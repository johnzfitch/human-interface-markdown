---
chunk_index: 196
ref: "3892124e7268"
id: "3892124e72680f2a092078fc6b158929c8439869b536bbaa6c0abfa3051395a9"
slug: "full-document--consistency"
path: "marker/1982 Apple IIe Design Guidelines/full_document.md"
kind: "markdown"
lines: [531, 540]
token_estimate: 446
content_sha256: "0f2fbf5bcabcaa91e6d59db8ae4733dbccc0d6e1bfe9640a68f4f26730a8e5b6"
compacted: false
heading_path: ["A Planning and Testing Methodology","Consistency"]
symbol: null
address: null
asset_path: null
---

## Consistency

All programs written for a given computer should have as great a commonality as is practical. The purpose of these guidelines and standards is to achieve a level of consistency across all products designed to run on the Apple, a level that will make learning your product easier, but not be so rigid as to stifle your ability to create the specific human interface best suited to your particular application.

All programs produced by a given software house should perform the same function in the same way. The same key sequence must not do the opposite thing in different products (E=edit, E=eradicate). Many software houses have their own guidelines, guidelines from which we drew in preparing this document. These individual guidelines tend to outline in far greater detail the program "personality" that the software house wants to project. If you have not yet put together such a document, may we suggest you do so. It is a very effective way to eliminate those interface battles that tend to occur about three days before release to production—or three days after.

All software should be self-consistent: menu formats should be identical. If GET or READKEY is used for one input, it should be used for all inputs. If the LEFT-ARROW key deletes characters in one part of the program, it

should delete characters in all parts of the program. If you are working on a large project, be sure to spend enough time in team meetings being sure that everyone is on the same track—all too often the three or four sections of a program end up with an entirely different "feel." At the same time, avoid rigidity: human interfaces must be tested on real people. The agreed-upon interface at the beginning will undoubtedly need changing, once you try it out on real people.