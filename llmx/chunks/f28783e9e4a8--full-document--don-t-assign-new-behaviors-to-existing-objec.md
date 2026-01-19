---
chunk_index: 2668
ref: "f28783e9e4a8"
id: "f28783e9e4a8325c94271e7048d4754e52a7fc44037ab986314640712c62cb9e"
slug: "full-document--don-t-assign-new-behaviors-to-existing-objec"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [1096, 1111]
token_estimate: 345
content_sha256: "c648a9161c5af77f72f64571a393b6eef675c95ee5422b7ab3f9bc51af98ac5f"
compacted: false
heading_path: ["Extending the Interface","Don't Assign New Behaviors to Existing Objects"]
symbol: null
address: null
asset_path: null
---

## Don't Assign New Behaviors to Existing Objects

The previous section describes how to use elements from the existing user interface. When you do use existing interface building blocks, use them in the standard way. Make sure you do *not* change the behavior for standard elements. When you need a new behavior, design a new element for it. If elements behave differently in different situations, the interface becomes unpredictable and harder to figure out.

Consider an example of a palette that includes a subpalette. You might think of using the ellipsis character to indicate that the palette will display additional choices. However, using this symbol to indicate a subpalette gives it a meaning other than the standard meaning. In menus, the ellipsis character means that the user must provide more information before a command will operate. It doesn't mean that more information appears when the user chooses the item. This incorrect use of the ellipsis character is shown in Figure 3-3.

**Figure 3-3** An incorrect subpalette indicator

![](images/_page_63_Picture_3.jpeg)

A better idea would be to use a right-pointing triangle; using it to indicate a subpalette would be analogous to using it to indicate a submenu. Figure 3-4 shows a triangle being used to indicate a subpalette.

**Figure 3-4** A better subpalette indicator

![](images/_page_63_Picture_6.jpeg)