---
chunk_index: 2824
ref: "d5c9b1436627"
id: "d5c9b1436627580d30a9da03d05229113a1c8d9fc2bbaf69db22f7afee0e8861"
slug: "full-document--anti-aliasing"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [3763, 3782]
token_estimate: 388
content_sha256: "e87f5bba8ad2b4685baa8881b63f5ccd8632d07d367d834e915c15a01d7ebed6"
compacted: false
heading_path: ["Anti-Aliasing"]
symbol: null
address: null
asset_path: null
---

# Anti-Aliasing

A technique for enhancing the appearance of your icons is to smooth angular or curved lines by coloring pixels on jagged edges. This technique is called *anti-aliasing*. Change the pixel color where you can see a visual break in the outline of a black-and-white icon. Figure 8-27 shows an icon before anti-aliasing, after anti-aliasing, and then in the context of a control panel icon.

**Figure 8-27** Correct anti-aliasing

![](images/_page_266_Picture_10.jpeg)

![](images/_page_266_Picture_11.jpeg)

![](images/_page_266_Picture_12.jpeg)

![](images/_page_266_Picture_13.jpeg)

Color Icons **243**

In anti-aliasing, you typically add pixels to an outline shape. Since the Finder uses only one mask for each size in the icon family, make sure that all your icons have the same outline shape. That is, when you anti-alias icons, don't add pixels or shadows to the outline shape of color icons. Figure 8-27 shows how anti-aliasing works well within an icon. The Finder uses the icon mask for alignment and transformation effects, so make sure that the mask and all your icons are appropriate for each other.

If you add too much anti-aliasing to the icons, they appear smooth, but also more fuzzy. While some people prefer this appearance, the Macintosh desktop appearance relies on crisp-looking icons. Gray outlines create a fuzzy image on the desktop. If people perceive something fuzzy on their screen, they may assume that something is wrong with their eyes or their display. Avoid creating this appearance if at all possible.