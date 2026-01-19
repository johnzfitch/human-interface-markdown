---
chunk_index: 734
ref: "4fbc46b38619"
id: "4fbc46b38619bf7b576ea220d59cf38f65f7e201cf5b0abc60222eb9f8deef1d"
slug: "chunk-055--grouping-operations-in-menus"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/chunks/chunk_055.md"
kind: "markdown"
lines: [22, 31]
token_estimate: 683
content_sha256: "abbc02e9c0c71a9acc584f38c7f446dbb5e14b46ec66fd1b338ae2d64998585c"
compacted: false
heading_path: ["**The Menu Bar**","Choosing a Menu Item","Appearance of Menu Items","Grouping Operations in Menus"]
symbol: null
address: null
asset_path: null
---

#### Grouping Operations in Menus  
As mentioned earlier, menu items can be divided into two kinds: verbs (actions) and adjectives (attributes). An attribute stays in effect until it's canceled, while an action ceases to be relevant after it has been performed. A single menu can contain both actions and attributes, but the actions should be grouped together and the attributes grouped together. The two groups are separated by dotted lines.  
Another reason to group operations is to break up a menu so it's easier to read. Operations grouped for this reason are logically related, but independent. Operations that are actions are usually grouped this way, such as Cut, Copy, Paste, and Clear in the Edit menu.  
Attribute operations that are interdependent are grouped, either as mutually exclusive groups or as accumulating groups.  
In a mutually exclusive attribute group, only one item in the group is in effect at any one time. The item that's in effect is preceded in the menu by a check mark. If the user chooses a different item in the group, the check mark is moved to the new item. An  
example is MacWrite's Font menu, where only one font at a time can be in effect for a particular selection. Radio button controls, where pressing one button disables all the others, are also mutually exclusive.  
In an accumulating attribute group, any number of attributes can be in effect at the same time. One of the items in the group cancels all the others. An example is MacWrite's Style menu, where the user can choose any combination of Bold, Italic, Underline, Outline, or Shadow—but Plain Text cancels all the others. Check-box controls, in which all, none, or any other number of the boxes may be in effect at a time, are also examples of accumulating attributes.  
Another way to show the presence or absence of an attribute is by a **toggled operation**. In this case, an attribute has two states, and a single menu item allows the user to toggle between the states. You can show the user that an operation is toggled either with check marks or by changing the wording.  
MacWrite's View menu is a good example of check marks that indicate the state of a toggled attribute. When View by Icon has been chosen, there is a check mark to the left of "by Icon" and all other views in the menu are not checked.  
Here's an example of changing the wording in a toggled menu item. When rulers are showing in a program that uses rulers, one item in the Format menu is Hide Rulers. If the user chooses this item, the rulers are hidden, and the name changes to Show Rulers. Use this technique only when the wording of the items makes it obvious that they're opposite sides of the same thing—Undo and Redo are another good example.