---
chunk_index: 4055
ref: "816fef4426f0"
id: "816fef4426f0529a08a5dd3d988d1c8014ff8b4cdc7d272334969925aacde9d1"
slug: "full-document--using-the-miniaturize-button-cj"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [1464, 1471]
token_estimate: 291
content_sha256: "6de7e64fad82f65c55d67a6d890a15bfce8add4109a4b43130bb50d7f56c4c2a"
compacted: false
heading_path: ["The Window Interface to Applications","**Using the Miniaturize Button [CJ**"]
symbol: null
address: null
asset_path: null
---

## **Using the Miniaturize Button [CJ**

Except when an application is useless without a particular standard window, each standard window should have a miniaturize button. When a window is miniaturized, it should remain miniaturized until the user explicitly unminiaturizes it.

Because a miniaturized window isn't likely to be foremost in the user's thoughts, the application should never alter a miniaturized window without the user's knowledge. However, it's fine for an application to continue doing some work in a miniaturized window, as long as the user requested that the work be done. For example, the Terminal application completes commands that the user entered in a Terminal window. But it's unacceptable, for example, to change the font in a miniaturized window unless the user specified a font change for *all* windows.

The miniaturize button has a counterpart command in the Windows menu that miniaturizes the key window. You can also provide a command in the Document menu that miniaturizes several related windows into a single mini window. See "The Windows Menu" and "The Document Menu" in Chapter 6 for information on how these commands work.