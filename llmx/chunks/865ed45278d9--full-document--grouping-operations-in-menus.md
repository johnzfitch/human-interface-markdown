---
chunk_index: 1342
ref: "865ed45278d9"
id: "865ed45278d9eafbfc2f22f8c9ea133293d94722c292d7270b9bec2f65518c45"
slug: "full-document--grouping-operations-in-menus"
path: "marker/1986-12 Human Interface Guidelines (Final Draft)/full_document.md"
kind: "markdown"
lines: [1025, 1038]
token_estimate: 517
content_sha256: "d874b5f286ef70fb1a2451480285a19adafa06d977b0b19d106fa5d01e1166eb"
compacted: false
heading_path: ["Grouping operations in menus"]
symbol: null
address: null
asset_path: null
---

# Grouping operations in menus

The most frequently used operations should be at the top of a menu. The least frequently used (such as Quit) should be at the bottom.

As already mentioned, there are two kinds of menu items: actions (verbs) and attributes (adjectives). An attribute stays in effect until it's canceled, whereas an action ceases to be relevant after it has been performed. A single menu can contain both actions and attributes, but the actions should be grouped together and the attributes grouped together. The groups are separated by dotted lines (the dotted lines are actually disabled menu items that are "named" with a horizontal line). Figure 27 illustrates these visual features of menus.

Another reason to group operations is to break up a menu so it's easier to read. Operations grouped for this reason are logically related, but independent. Operations that are actions are usually grouped this way, such as Cut, Copy, Paste, and Clear in the Edit menu.

Attribute operations that are interdependent are grouped, either as mutually exclusive groups or as accumulating groups.

In a mutually exclusive attribute group, only one item in the group is in effect at any one time. The item that's in effect is preceded in the menu by a check mark. If the user chooses a different item in the group, the check mark is moved to the new item. An example is the standard Font menu, in which only one font at a time can be in effect. (Radio button controls, in which pressing one button in a group disables all the others, are also examples of mutually exclusive attribute groups.)

In an accumulating attribute group, any number of attributes can be in effect at the same time. One of the items in the group cancels all the others. An example is the standard Style menu, in which the user can choose any combination of Bold, Italic, Underline, Outline, or Shadow—but Plain Text cancels all the others. (Checkbox controls, in which all, none, or any other number of the boxes may be in effect at a time, are also examples of accumulating attributes.)