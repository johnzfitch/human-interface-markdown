<!-- Chunk 216 | Source: 1995 Macintosh Human Interface Guidelines.pdf | Est. Tokens: 1052 -->
The Finder displays default icons for fonts, keyboard layouts, and sounds, also known as movable resources. The icon looks like a document icon reversed in orientation. The user installs these resources by dragging the icon to the System Folder icon. The user can remove a movable resource by opening the System file icon (or Font Folder icon) in the System Folder and dragging its icon out of the System file. TrueType fonts have a character in three sizes on the icon, whereas bitmapped fonts only have a single character. When a user opens a font icon, the Finder displays a window with a sample of the font in it. Figure 8-44 shows some font icons.  
**Figure 8-44** Font icons  
![](images/_page_275_Picture_5.jpeg)  
![](images/_page_275_Picture_6.jpeg)  
Bitmapped font TrueType font  
Sound icons have a speaker symbol on them, as shown in Figure 8-45. When a user opens the sound icon, the sound plays.  
**Figure 8-45** A sound icon  
![](images/_page_275_Picture_11.jpeg)  
Keyboard Icons 8  
A keyboard icon represents a localized keyboard layout or input method. If you develop keyboards, input methods, script systems, or keyboard resources, you need to provide icons. (Keyboard icons appear in the Keyboard menu and in the Keyboard control panel.) You need to create a 16-by-16 pixel icon in 1-bit and 4-bit color. If you don't create a keyboard icon, then the system provides a default icon. Figure 8-46 shows the default keyboard layout icon and the default input method icon.  
<span id="page-276-0"></span>**Figure 8-46** The default keyboard layout and input method icons  
![](images/_page_276_Picture_4.jpeg)  
![](images/_page_276_Picture_5.jpeg)  
Default keyboard layout icon  
Default input method icon  
Keyboard icons are a special case of icons. Since they represent a specific type of software they follow design rules different from those for other icons users see on the desktop. The guidelines presented in this section apply only to keyboard icons.  
For a keyboard icon, use a solid symbol to represent a keyboard layout for a region that is larger or smaller than an area that can be represented by the flag of a country or province. For example, a diamond represents the Roman Script System, which is used in the United States, Central America, South America, Australia, New Zealand, and most of Europe. Use the flag of a country or province if the keyboard layout is used primarily in that area. For example, the Union Jack represents the keyboard layout localized for use in the United Kingdom. Be sure to use the colors that appear on the nation's flag. Figure 8-47 shows some keyboard icons for script systems and localized keyboard layouts.  
**Figure 8-47** Examples of keyboard icons  
![](images/_page_276_Picture_11.jpeg)  
<span id="page-277-0"></span>You can also add a visual indicator to the keyboard icon to show some modification. Use a superscript diamond to indicate a QWERTY transliteration, which is a mapping of sounds from a language to the Roman keyboard layout. Figure 8-48 shows some flag symbols with additional indicators.  
**Figure 8-48** Examples of modification indicators on keyboard icons  
![](images/_page_277_Picture_4.jpeg)  
When you design the black-and-white version of a flag icon, use black and a 50 percent gray pattern. These choices provide the best contrast and legibility. To avoid confusion between flags of similar design, use the pattern substitutions for colors shown in Table 8-2.  
**Table 8-2** Pattern substitutions for colors in keyboard icons  
![](images/_page_277_Picture_7.jpeg)  
<span id="page-278-0"></span>Figure 8-49 shows some keyboard icons that use the correct pattern substitutions.  
**Figure 8-49** Enlarged keyboard icons with correct color substitutions  
![](images/_page_278_Picture_6.jpeg)  
See the section "The Keyboard Menu" beginning on page 125 in Chapter 4, "Menus," and *Inside Macintosh: Text* for information on the Keyboard menu. See the chapter "Finder Interface" in *Inside Macintosh: Macintosh Toolbox Essentials* for more information about displaying custom icons. That chapter also provides information on how to use the bundle resource to associate these icons with your application.