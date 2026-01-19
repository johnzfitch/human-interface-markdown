---
chunk_index: 2816
ref: "cad75881ed37"
id: "cad75881ed374b2362c8a952cd4adc3530db99d82539560db61ab12ebd12c1c9"
slug: "full-document--an-icon-design-process"
path: "marker/1992 Macintosh Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [3645, 3672]
token_estimate: 1167
content_sha256: "2284fae5debbed4ea9f2ce2358e88fc7aafc102bd0939d284639d596c210b3c4"
compacted: false
heading_path: ["An Icon Design Process"]
symbol: null
address: null
asset_path: null
---

# An Icon Design Process

This section presents an icon design process used at Apple. Of course, there are many ways to complete a task, and you may work in a way that doesn't lend itself to using this process. However, you should read this section to find out important principles that contribute to successful and effective icons.

You can't design one icon in your icon family in isolation. All the icons in a family—large, small, and different color depths—are incarnations of the same icon, so the basic design must work for all of them. Be flexible in adapting your design to all bit depths and sizes. Icon design is an iterative process. During the design process, you may need to redesign one version of an icon when you find it doesn't translate well to another version.

If an icon represents hardware that users are familiar with, such as a printer or a disk drive, the icon should resemble the hardware as closely as possible. If the icon represents a desktop entity, such as a document or a folder, it should resemble its physical world counterpart. If you need to design an icon for a more conceptual entity, such as a network or some kind of memory, you can use one of the following approaches. Making the icon representative of the function of the software is a good approach. If the function is complex and hard for novice users to understand, think about how you could explain the idea to someone who doesn't use a computer and try to generate some images that way. Often the terms you use and the analogies you come up with to explain the concept can provide clues for visual images.

You can also make an icon representative of a product name. This may work for your product in one location, but remember that some product names, and thus product icons, are often not localizable. For example, in the United States, an icon for extensions could have something to do with an extension cord. In other languages, the word used for extension cords may have nothing to do with extensions, and therefore an icon based on the word *extension cord* would be meaningless. Another drawback to this approach is that product names are often not finalized until late in the development process, so you might not have much time in which to design an icon based on the final product name.

A final approach to designing conceptual icons is making the icon look like the window that results from opening the icon. For example, if a window that appears when the icon is opened is very distinct in appearance from other windows, you can make an icon look like that window. You need to be very careful that all your icons do not look like miniature windows.

![](images/_page_260_Picture_3.jpeg)

It is often easiest to create icons that represent objects (nouns) rather than actions (verbs). For example, the function of deleting a document is represented by a trash can (an object) rather than by some image of the action of deleting. Thinking of an object that is representative of the function of your icon is the key to good conceptual design. Remember that for every image you generate, you need to consider the advantages and disadvantages of the idea in regard to your audience before deciding on the final design.

Here's an outline of the suggested steps in an icon design process. The sections that follow go into the details of some icon design guidelines.

- 1. Start by designing the black-and-white version of the large (32-by-32 pixel) icon. Follow the guidelines given in the next section, "Black-and-White Icons."
- 2. Colorize the black-and-white version of your icon in 8-bit color. Use colors from the Apple icon colors palette (see the section "The Apple Icon Color Set" on page 240). For more information about creating color versions of black-and-white icons, see "Design for Black and White First" on page 263 in Chapter 9, "Color."
- 3. Translate the 8-bit version of your icon into 4-bit color. If you can't find appropriate colors in the 4-bit palette, try going back to step 2 and swap colors in the 8-bit version. You can use a dithered pattern of two colors to create the illusion of a new color for the 4-bit icon.
- 4. Create the mask.
- 5. Create matching small versions (16-by-16 pixel) of the black-and-white, 8-bit, and 4-bit icons.
- 6. Look at the icon family on different desktop backgrounds and with several effects such as selection and labeling to make sure that the icons look good.
- 7. Do some usability testing to make sure that your target audience understands your icons, doesn't confuse them with other icons, and identifies them as a family of icons.

ResEdit is a useful tool for accomplishing steps 3, 4, and 6.