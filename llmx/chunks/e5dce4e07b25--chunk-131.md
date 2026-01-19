---
chunk_index: 3747
ref: "e5dce4e07b25"
id: "e5dce4e07b258f7b650384fb8f61d8eb30997c84d532f519bc3d1749a27fe7fe"
slug: "chunk-131"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_131.md"
kind: "markdown"
lines: [1, 6]
token_estimate: 334
content_sha256: "b10cce0eb6786e6bbda86f36089ba57951f406b4715eb0cfba7bab7d5e05083e"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 131 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 307 -->
When designing your application's menu hierarchy, you should start with the standard menus described later in this chapter-in particular, the main menu. Having standard menus, as much as possible, is one of the easiest and best ways to ensure consistency between applications.  
Since menus need to be easily accessible to the user, you should try to keep your application's menu hierarchy as shallow as possible. In general, a menu should be located no more than two steps away from the main menu. It's even better to have menus no more than one step away, as long as they don't grow too long or confusing as a result.  
![](images/_page_118_Picture_10.jpeg)  
A menu should never have fewer than two commands unless it grows and shrinks dynamically and happens to shrink to fewer than two. If an application has a menu with only one item in it, that item should be bumped up one level and replace the command that brings up the menu. (A specific example of this is discussed later in this chapter under "The Info Menu.")  
A menu can have as many submenus as it has commands, although only one at a time can be attached to the menu. A menu should appear only once in the menu hierarchy-it should not be the submenu of two menus.