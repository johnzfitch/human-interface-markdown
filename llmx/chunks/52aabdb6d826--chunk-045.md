---
chunk_index: 2210
ref: "52aabdb6d826"
id: "52aabdb6d826a7c2788af97ab7e22514cf3f65040686c65dbeee544abc9ed133"
slug: "chunk-045"
path: "marker/1992 Macintosh Human Interface Guidelines/chunks/chunk_045.md"
kind: "markdown"
lines: [1, 7]
token_estimate: 555
content_sha256: "c1c2d4fee9376c1939db910f01cb8dcc2ddaaf1b5238b0b7eef26c4563aa2b98"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 45 | Source: 1992 Macintosh Human Interface Guidelines.pdf | Est. Tokens: 531 -->
As stated previously, users can install multiple script systems. If the Operating System determines that all conditions are met, it enables the script system, making it available to users. A script system can contain more than one keyboard layout that maps character codes to keys on a physical keyboard, and it can support more than one attached physical keyboard. Double-byte scripts contain input methods (which allow users to enter double-byte characters) and keyboard layouts. See *Inside Macintosh: Text* for information on installing and enabling script systems and keyboard resources.  
The Operating System adds a Keyboard menu when more than one script system is present or a localizable resource flag is set. This menu simplifies the user's access to input methods, keyboards, and scripts. The icon for the Keyboard menu appears between the icons for the Help menu and the Application menu. A small keyboard icon appears next to each keyboard layout name, and the icon of the active keyboard layout appears in the menu bar. As Figure 2-5 shows, the Keyboard menu displays a list of installed keyboard layouts for each enabled script system. For double-byte scripts, the Keyboard menu displays a list of input methods instead of keyboard layouts.  
A keyboard icon represents a localized keyboard layout or an input method. If you develop keyboards, keyboard resources, or input methods, you must provide customized icons like these. For detailed guidelines about how to design a keyboard icon, see "Keyboard Icons" on page 252 in Chapter 8, "Icons."  
The Keyboard menu groups the keyboard layouts and input methods by script system. These groups are separated by dotted lines on black-and-white screens or gray lines on color screens. Figure 2-5 shows an example of the Keyboard menu with the keyboard icon and layout for the active script system, and the script boundary area of the menu. Only one keyboard layout or input method, and one physical keyboard are active at a time; the active condition is indicated by a checkmark in the menu.  
**Figure 2-5** The Keyboard menu  
![](images/_page_46_Picture_3.jpeg)