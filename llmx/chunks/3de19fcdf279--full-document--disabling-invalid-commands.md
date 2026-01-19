---
chunk_index: 4121
ref: "3de19fcdf279"
id: "3de19fcdf279489fe5f7d028f5809c927ecdd9fad9b9dc4c7cb9be238520c4f5"
slug: "full-document--disabling-invalid-commands"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [2156, 2165]
token_estimate: 187
content_sha256: "b76cd7a6e5cb70f5dc3ee896fd54c91e2163f760408f8040b17865f4b24ea629"
compacted: false
heading_path: ["5 *Panels*","**Disabling Invalid Commands**"]
symbol: null
address: null
asset_path: null
---

## **Disabling Invalid Commands**

When a menu command won't work, it should either be disabled or bring up an explanatory panel. For example, when a text editor has no documents open, it should disable its Save and Close commands, as shown below.

![](images/_page_122_Picture_2.jpeg)

When a disabled command is chosen using a keyboard alternative, a beep occurs. This helps the user know that the command isn't valid, even if the command isn't visible.

If an invalid command brings up an explanatory panel, the panel should explain why the command is inappropriate and offer assistance. The panel must provide more information than just that the command won't work, since that information can more directly be conveyed by disabling the command.