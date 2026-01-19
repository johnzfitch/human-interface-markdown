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