---
chunk_index: 2922
ref: "f217ad1cd550"
id: "f217ad1cd550d6f56b795557bd5308386d05d585b6030924114735f1443ae67a"
slug: "full-document--when-to-use-a-help-balloon"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [5005, 5024]
token_estimate: 760
content_sha256: "3bf3522d53af6f3f7b8bc66db3ddeceae79b8fd3e21597a2f4eb68efe443ac55"
compacted: false
heading_path: ["Balloon Help","When to Use a Help Balloon"]
symbol: null
address: null
asset_path: null
---

## When to Use a Help Balloon

Balloon Help is designed always to be available to users, even when a modal dialog box is on the screen. This is so that users can get help when they need it, without having to stop what they are doing and look in a separate location for information about what they are doing.

![](images/_page_340_Picture_5.jpeg)

Use help balloons to explain elements of your application's interface that might confuse a new user or elements that could help a user become an expert user. The information provided in help balloons should identify interface elements in your application or explain how to use them. When considering whether or not to use a help balloon, try to think about the types of questions users are most likely to have about elements in your application. For example, are there any elements in your application that don't usually appear in other Macintosh applications? It's helpful to think about the types of users who will be using your application: are they novices or are they experienced computer users? And finally, think about the terminology used in your application that users may not be familiar with.

Help balloons should be short and easy to understand. Don't include lengthy instructions or numbered steps in balloons. Use clear, concise language in balloons. Write help messages that describe what an object in your application does; the user wants to know what will happen if he or she uses that particular object.

It's not necessary to name every object in your application in the balloons, especially if they're already named on screen. It's more important that the user find out how to use an object than it is for the user to know the object's exact name. Some exceptions to this guideline include items whose names help describe how to use the item. These include tools in palettes, controls on a ruler, controls in a paint program, or icons that don't already have names on the screen.

It's a good idea to provide separate help balloons for each state of a menu item or dialog item. For example, write separate balloons for the selected, unselected, and unavailable state of radio buttons and checkboxes. Where appropriate, use parallel wording for the balloons belonging to a single item.

Balloon Help **317**

It's especially important to write a separate help balloon for a situation the user might find difficult to figure out. For example, if a selection in a Preferences dialog box causes some menu command to be dimmed, a special balloon for that command should appear when that selection is on.

For groups of controls, it may make sense to use one help balloon to describe the whole group rather than providing a separate help balloon for each control. For example, the help balloon for a group of radio buttons used to set the margins of a document might describe all three options: left, right, and center. Help balloons can also describe a complicated dialog box by telling users what they can accomplish by using each of the features or options in the dialog box.