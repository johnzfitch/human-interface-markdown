---
chunk_index: 2641
ref: "ae72e0738bfa"
id: "ae72e0738bfa3f5e97ffa1a42b33f0142e20018156bd866ead21a5419cdabb87"
slug: "full-document--fonts"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [880, 889]
token_estimate: 318
content_sha256: "06834736427a077787bb8130dd3c3dc50cf78d49cc06fde65c6ee081ba00ab92"
compacted: false
heading_path: ["Worldwide Compatibility","Fonts"]
symbol: null
address: null
asset_path: null
---

## Fonts

When you write software that supports non-Roman scripts, don't make assumptions about font sizes; let the user choose them. For example, system or application fonts may be preset to 12 or 18 points. A font with a resource ID of 0 is not always set to Chicago, nor are system fonts always Chicago and Geneva. Use system and application fonts when the user cannot choose the font, but *don't* hard code Roman values. If you must assign font sizes, use the Script Manager to get a script system's appropriate fonts and sizes. Use the proper font names as defined by worldwide system software. Whenever possible, display font names in the proper script and font in your Font menu.

In some scripts and fonts, diacritical marks may extend beyond the ascent line. Other fonts, such as Japanese fonts, contain glyphs that extend to the boundaries of the enclosing rectangle of the font, or to *both* minimum-y and maximum-y lines. Leave room for space between lines of text and between the top and bottom lines of any enclosing rectangle. See *Inside Macintosh: Text*  for more information. Figure 2-6 shows some glyphs that demonstrate the boundaries you need to allow for in lines of text.

**Figure 2-6** The boundaries of a font

![](images/_page_47_Picture_4.jpeg)