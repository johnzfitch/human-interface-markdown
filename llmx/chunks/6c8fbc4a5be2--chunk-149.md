---
chunk_index: 3771
ref: "6c8fbc4a5be2"
id: "6c8fbc4a5be23bc67083eb86c0d0b005f65e88d801e630bc13eeb5d3bc461564"
slug: "chunk-149"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_149.md"
kind: "markdown"
lines: [1, 20]
token_estimate: 783
content_sha256: "6dfc01812a5b01c98a4237f8798aa441e0556a8fefa19b2348f7237e487a86b7"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 149 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 756 -->
| Find              |    |
|-------------------|----|
| Find Panel        | f  |
| Find Next         | g  |
| Find Previous     | d  |
| Enter Selection   | е  |
| Jump to Selection | j  |
| (add here)        | 1. |  
Applications that display large amounts of text are encouraged to include a Find menu like the one illustrated above. Other applications might also find this menu useful, but because it's designed most specifically for text, a variation of it might better meet their needs.  
| Command         | Action                                                                                                                                                                                                                                                                                       |
|-----------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Find Panel      | Brings up the Find panel, makes it the key window, and selects<br>everything in the text field labeled Find so that the user can easily<br>enter new text. If the panel is already on-screen, the command<br>brings it to the front, makes it the key window, and selects the<br>Find field. |
| Find Next       | Searches forwards for the next occurrence of the string in the panel's<br>Find field.                                                                                                                                                                                                        |
| Find Previous   | Searches backwards for the previous occurrence of the string in the<br>panel's Find field.                                                                                                                                                                                                   |
| Enter Selection | Enters the current selection into the panel's Find field so that Find<br>Next and Find Previous can search for it.                                                                                                                                                                           |  
Find Next and Find Previous begin searching at the current selection. If the search is successful, the text that's found is selected and becomes the starting point for the subsequent search. Neither command requires the Find panel to be on-screen. However, if the panel's Find field is empty, Find Next and Find Previous both bring up the Find panel, make it the key window, and select its Find field. This is exactly what the Find Panel command does. These other commands do it as a convenience to the user, who has  
Jump to Selection Scrolls to display the beginning of the current selection.  
The Find panel is further described in Chapter 5.  
indicated an intention to do a search.