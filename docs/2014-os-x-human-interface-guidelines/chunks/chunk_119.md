<!-- Chunk 119 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 425 -->
A **scrolling list** is a list that uses scroll bars to reveal its contents.  
![](images/_page_194_Picture_7.jpeg)  
**API Note:** To define a scrolling list in your code, use the NSTableView class.  
A scrolling list is a single-column rectangular view of any height.  
**Note:** Scrolling lists, like other scrolling areas, are governed by the user's scroll direction setting in System Preferences.  
Use a scrolling list to display an arbitrarily large number of items from which users can choose. Although scrolling lists aren't directly editable, you can implement editing functionality that allows users to provide additional list items.  
**In general, don't use a scrolling list to provide choices in a limited range.** A scrolling list might not display all items at once, which can make it difficult for users to grasp the scope of their choices. If you need to display a limited range of choices, a pop-up menu (described in [Pop-Up](#page-189-1) Menu (page 190)) might be a better choice.  
**Insert an ellipsis in the middle of an item that is too long to fit in the list.** Inserting the ellipsis in the middle allows you to preserve the beginning and end of the item name, which tend to be more distinct and recognizable.  
**Consider using a striped background to help users scan a long list.** For example, users can lose their place in a very long list in which most of the items look similar. In this case, it can be easier for users to scan the list and find specific items when the background is striped.  
<span id="page-195-0"></span>**In general, provide an introductory label for a scrolling list.** A label helps users understand the types of items that are available to them.