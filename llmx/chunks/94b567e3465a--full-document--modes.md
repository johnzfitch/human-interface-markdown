---
chunk_index: 3957
ref: "94b567e3465a"
id: "94b567e3465a4031d34219e6db9d2074173f2ee2915892d523ac0e0eca1b9539"
slug: "full-document--modes"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [498, 507]
token_estimate: 245
content_sha256: "e83872048633a78b4bf719b8bdb15300669b7a456a9fa86c3f6a2d6d938d6cee"
compacted: false
heading_path: ["*Introduction*","**Modes**"]
symbol: null
address: null
asset_path: null
---

## **Modes**

In particular, applications should avoid setting up arbitrary modes, periods when only certain actions are permitted. Modes often make programming tasks easier, but they usurp the users' prerogative of deciding what will be done. They can thus feel annoying and unreasonable to users who aren't concerned with implementation details.

On occasion, however, modes are a reasonable approach to solving a problem. Because they let the same action have different results in different contexts, they can be used to extend functionality. When permitted, a mode should be freely chosen, provide an easy way out, be visually apparent, and keep the user in control. In the NeXTSTEP user interface, modes are used in only three situations:

- In the modal tool paradigm, discussed under "Action Paradigms" later in this chapter
- In attention panels, discussed in Chapter 5, "Panels"
- In "spring-loaded" modes that last only while the user holds a key or mouse button down