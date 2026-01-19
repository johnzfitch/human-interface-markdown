---
chunk_index: 2686
ref: "bb6856b31f59"
id: "bb6856b31f5905aeb9305ae1383875b85ff7d4b5464d8abe6b9a237648d62f82"
slug: "full-document--the-interface-elements"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [1221, 1253]
token_estimate: 730
content_sha256: "65383ccd39a94d6c0edeaebd71efb9a4c26e05387f6b003619cc7d2f7376a49e"
compacted: false
heading_path: ["The Interface Elements"]
symbol: null
address: null
asset_path: null
---

# The Interface Elements

The second part of *Macintosh Human Interface Guidelines* defines the elements and behaviors of the Macintosh interface. It presents examples of each concept and examples of the right and wrong ways to use interface elements and behaviors. Use this section to find specific implementation information while you're creating a product. This part of this book also shows how to combine the pieces of the interface with behaviors, aesthetics, and language to create a superior product.

This part contains the following chapters:

- Menus
- Windows
- Dialog Boxes
- Controls
- Icons
- Color
- Behaviors
- Language

![](images/_page_72_Picture_2.jpeg)

This chapter describes the kinds of menus you can implement in your application—pull-down menus, scrolling menus, hierarchical menus, pop-up menus, palettes, and tear-off menus. It also describes in detail the appearance and behavior of these menu types including how menu items should be worded and what symbols you can use in menus. This chapter defines the items in the standard menus most applications use and the standard keyboard equivalents for those menu items.

Menus present lists of menu items—commands, attributes, or states. The user can browse through menus or choose an item. Menus appear in several forms in the interface. Pull-down menus are available in the menu bar. Hierarchical menus include submenus that descend from pull-down menu items. Some menus can be torn off from the menu bar to become palettes. Pop-up menus generally appear in dialog boxes. See *Inside Macintosh: Macintosh Toolbox Essentials* for information about implementing menus in your application.

In the Macintosh interface, people use a specific syntax for completing actions. First they select an object, then they choose a command to act on that object. This order of operation occurs in the Finder and in applications. Figure 4-1 shows this standard syntax.

**Figure 4-1** The standard order of actions

![](images/_page_74_Picture_3.jpeg)

![](images/_page_74_Picture_5.jpeg)

![](images/_page_75_Picture_2.jpeg)

Menus are based on the principle of see-and-point. People don't have to remember command names because they can see all the options at any time and choose any available option. The menu bar also reflects the principles of perceived stability and aesthetic integrity. The menu bar provides a stable location for people to look for commands. It remains at the top of the screen no matter what the user is doing. To maintain the visual clarity of the interface, only the menu bar is visible until the user pulls down a menu to look at its contents. This feature allows people to concentrate on the main attraction, the content of the screen, while giving them easy access to the menus. Each application, each desk accessory, and the Finder have their own menu bars, containing standard menus and their own application-specific menus.