---
chunk_index: 546
ref: "a86dd55bc658"
id: "a86dd55bc658b2aa7dbde7d144f07aecdbcc5fc645430649ea1aafd4f5dc5b7e"
slug: "full-document--moving-dragging-a-window"
path: "marker/1985 Apple II Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [1455, 1466]
token_estimate: 306
content_sha256: "5e349e742af62a6d172755b814c11a1430d86037243e74d41089e10afb4b39f2"
compacted: false
heading_path: ["Moving (Dragging) a Window"]
symbol: null
address: null
asset_path: null
---

# Moving (Dragging) a Window

Each application initially places windows on the screen wherever it wants them. The user can move a window—to make more room on the desktop or to uncover a window it's overlapping—by dragging it by its title bar. As soon as the user presses in the title bar, that window becomes the active window. A dotted outline of the window follows the pointer until the user releases the mouse button. At the release of the button the full window is drawn in its new location. Moving a window doesn't affect the appearance of the document within the window.

If the user holds down the Open-Apple key while dragging the window outline, the window isn't made active; it moves in the same plane. (At the time of this writing, this feature had not been implemented in the Apple II mouse toolkits.)

The standard keyboard shortcut for dragging a window is Open-Apple-D . The user can then use the cursor keys to drag the window outline. The user exits by pressing ESC to cancel, RETURN to accept the new location, or any other valid Open-Apple combination to accept and begin the next operation.

The application should ensure that a window can never be moved completely off the screen.

1/15/85 Tognazzini