---
chunk_index: 3688
ref: "5709f0dfead4"
id: "5709f0dfead49ced19d62f2d363b7396ccfd19f58bb473b5388899fff9c35ef7"
slug: "chunk-090"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_090.md"
kind: "markdown"
lines: [1, 4]
token_estimate: 307
content_sha256: "fd10d82f97fe283eb8947e69e1097a4c55149765c68a924b85a7f6a857089be9"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 90 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 280 -->
Except when an application is useless without a particular standard window, each standard window should have a miniaturize button. When a window is miniaturized, it should remain miniaturized until the user explicitly unminiaturizes it.  
Because a miniaturized window isn't likely to be foremost in the user's thoughts, the application should never alter a miniaturized window without the user's knowledge. However, it's fine for an application to continue doing some work in a miniaturized window, as long as the user requested that the work be done. For example, the Terminal application completes commands that the user entered in a Terminal window. But it's unacceptable, for example, to change the font in a miniaturized window unless the user specified a font change for *all* windows.  
The miniaturize button has a counterpart command in the Windows menu that miniaturizes the key window. You can also provide a command in the Document menu that miniaturizes several related windows into a single mini window. See "The Windows Menu" and "The Document Menu" in Chapter 6 for information on how these commands work.