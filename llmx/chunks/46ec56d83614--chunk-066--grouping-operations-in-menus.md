---
chunk_index: 1714
ref: "46ec56d83614"
id: "46ec56d83614859fa725933ebe1dc6d17ec447bb2a59fdbb6e58834fe2ed5971"
slug: "chunk-066--grouping-operations-in-menus"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/chunks/chunk_066.md"
kind: "markdown"
lines: [3, 11]
token_estimate: 550
content_sha256: "513f959e7beb232de108903fa6e32285fc3cde42cee6e7d377d02d59c04446bc"
compacted: false
heading_path: ["Grouping operations in menus"]
symbol: null
address: null
asset_path: null
---

#### Grouping operations in menus  
The most frequently used operations should be at the top of a menu. The least frequently used (such as Quit) should be at the bottom.  
As already mentioned, there are two kinds of menu items: actions (verbs) and attributes (adjectives). An attribute stays in effect until it's canceled, whereas an action ceases to be relevant after it has been performed. A single menu can contain both actions and attributes, but the actions should be grouped together and the attributes grouped together. The groups are separated by dotted lines (the dotted lines are actually disabled menu items that are "named" with <sup>a</sup> horizontal line; Figure 3-22 illustrates these visual features of menus).  
Another reason to group operations is to break up <sup>a</sup> menu so it's easier to read. Operations grouped for this reason are logically related, but independent. Operations that are actions are usually grouped this way, such as Cut, Copy, Paste, and Clear in the Edit menu.  
Attribute operations that are interdependent are grouped, either as mutually exclusive groups or as accumulating groups.  
In a mutually exclusive attribute group, only one item in the group is in effect at any one time. The item that's in effect is preceded in the menu by <sup>a</sup> check mark. If the user chooses <sup>a</sup> different item in the group, the check mark is moved to the new item. An example is the Finder's View menu, in which only one view at a time can be in effect (Figure 3-20). (Radio button controls, in which pressing one button in a group disables all the others, are also examples of mutually exclusive attribute groups.)  
![](images/_page_81_Picture_0.jpeg)  
Figure 3-20 View menu  
In an accumulating attribute group, any number of attributes can be in effect at the same time. One of the items in the group cancels all the others. An example is the standard Style menu, in which the user can choose any combination of Bold, Italic, Underline, Outline, or Shadow—but Plain Text cancels all the others. (Check-box controls, in which all, none, or any other number of the boxes may be in effect at a time, are also examples of accumulating attributes.)