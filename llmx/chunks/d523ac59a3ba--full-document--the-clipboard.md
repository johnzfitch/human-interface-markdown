---
chunk_index: 575
ref: "d523ac59a3ba"
id: "d523ac59a3baaf8d3e5f5e11c28397d4124b4520d4433c7a03f7bfe38f8552b1"
slug: "full-document--the-clipboard"
path: "marker/1985 Apple II Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [1824, 1841]
token_estimate: 298
content_sha256: "ad9018577e1fe4e44787a25ceb8292b2793f1729b7d3d6b5299d7539d5e2269e"
compacted: false
heading_path: ["The Clipboard"]
symbol: null
address: null
asset_path: null
---

# The Clipboard

The Clipboard is a special kind of window with a well-defined function: it holds whatever is cut or copied from a document. Its contents stay intact when the user changes documents, opens a desk accessory, or leaves the application. An application can choose whether to have the Clipboard open or closed when the application starts up.

The Clipboard looks like a document window, with a close box but with no scroll bars. Its contents cannot be edited.

Every time the user performs a Cut or Copy on the current selection, a copy of the selection replaces the previous contents of the Clipboard. The previous contents are kept around in case the user chooses Undo.

The user can see the contents of the Clipboard but can't edit them. In most other ways the Clipboard behaves just like any other window.

There is only one Clipboard, which is present for all applications that support Cut, Copy, and Paste. The user can see the Clipboard window by choosing Show Clipboard from the Edit menu. If the window is already

1/15/85 Tognazzini

STANDARD MENUS 99

showing, it's hidden by choosing Hide Clipboard. (Show Clipboard and Hide Clipboard are a single, toggled command.)