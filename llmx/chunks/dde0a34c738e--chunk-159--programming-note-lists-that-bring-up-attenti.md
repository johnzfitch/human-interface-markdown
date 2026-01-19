---
chunk_index: 3794
ref: "dde0a34c738e"
id: "dde0a34c738e753a8282f431aab6e35348787220cf1d7d4995d03387cc6defdc"
slug: "chunk-159--programming-note-lists-that-bring-up-attenti"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_159.md"
kind: "markdown"
lines: [22, 23]
token_estimate: 149
content_sha256: "d23a6bc8bb9599aaa00e83777d1c8805ebee4d3b0c733113930b5e6351b5d680"
compacted: false
heading_path: ["Implementing Pop-Up and Pull-Down Lists","Programming Note: Lists that Bring Up Attention Panels"]
symbol: null
address: null
asset_path: null
---

#### Programming Note: Lists that Bring Up Attention Panels  
When an item in a pop-up or pull-down list opens an attention panel, the list by default stays up until the panel is dismissed. Because lists are in a higher window tier than attention panels, they can obscure attention panels. To avoid this, you should dismiss the list before bringing up the attention panel. One way of doing this is to have the list item call the perform:with:afterDelay:canceIPrevious: method to schedule the execution of a method 1 millisecond in the future. This method should then bring up the attention panel.