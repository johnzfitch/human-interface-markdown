---
chunk_index: 906
ref: "1e16638e19f9"
id: "1e16638e19f99aac174b8cb6681230e1c2a2e20c218df96f13dafaf475074cba"
slug: "full-document--grouping-operations-in-menus"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/full_document.md"
kind: "markdown"
lines: [1333, 1352]
token_estimate: 681
content_sha256: "7ba08e0f390fe86d44a43785d0f93531c1e37bb6a30b5ae36549f9cda431a446"
compacted: false
heading_path: ["Menus","**The Menu Bar**","Choosing a Menu Item","Grouping Operations in Menus"]
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