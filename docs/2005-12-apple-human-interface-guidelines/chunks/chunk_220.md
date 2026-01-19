<!-- Chunk 220 | Source: 2005-12 Apple Human Interface Guidelines.pdf | Est. Tokens: 785 -->
<span id="page-161-1"></span>If your application provides functions for formatting text, you can include a**Format menu** as a top-level menu or as a submenu of the Edit menu. It may be appropriate to group some items that are in the Format menu into submenus, such as Font, Text, or Style.  
**Figure 12-18** A Format menu  
![](images/_page_161_Picture_8.jpeg)  
<span id="page-161-6"></span><span id="page-161-4"></span><span id="page-161-3"></span>**Show Fonts (Command-T).** The first item in the Format menu should be Show Fonts, which displays the Fonts window.  
**Carbon:** Use the FPShowHideFontPanel function. See the *Fonts Window Services Reference* in Text & International Documentation.  
**Cocoa:** Use NSFontPanel.  
<span id="page-161-2"></span>**Show Colors (Command-Shift-C).** Displays the Colors window.  
**Carbon:** Use the NPickColor function to implement a Colors window. See *Color Picker Manager Reference* in Carbon Graphics & Imaging Documentation.  
**Cocoa:** Use the NSColorPanel class. See *Color Programming Topics for Cocoa* in Cocoa Graphics & Imaging Documentation.  
**Bold (Command-B).** Boldfaces the selected text or toggles boldfaced text on and off. If used as a toggle, indicate when it is on by having a checkmark next to the command in the menu.  
<span id="page-162-8"></span>**Italic (Command-I).** Italicizes the selected text or toggles italic text on and off. If used as a toggle, indicate when it is on by having a checkmark next to the command in the menu.  
<span id="page-162-11"></span>**Underline (Command-U).** Underlines the selected text or toggles underlined text on and off. If used as a toggle, indicate when it is on by having a checkmark next to the command in the menu.  
<span id="page-162-5"></span><span id="page-162-3"></span>**Bigger (Command–Shift–equal sign).** Causes the selected item to increase in size in defined increments.  
<span id="page-162-9"></span>**Smaller (Command-hyphen).** Causes the selected item to decrease in size in defined increments.  
<span id="page-162-10"></span>**Copy Style (Command-Option-C).** Copies the style—font, color, and size for text—of the selected item. It may be appropriate to put this item in a Style submenu along with related items.  
<span id="page-162-1"></span>**Paste Style (Command-Option-V).** Applies the style of one object to the selected object.  
<span id="page-162-4"></span>**Align Left (Command-{).** Left-aligns a selection.  
<span id="page-162-12"></span>**Center (Command-|).** Center-aligns a selection.  
<span id="page-162-13"></span><span id="page-162-2"></span>**Justify.** Evenly spaces a selection.  
<span id="page-162-6"></span>**Align Right (Command-}).** Right-aligns a selection.  
**Show Ruler.** Displays a formatting ruler.  
<span id="page-162-7"></span>**Copy Ruler (Command-Control-C).** Copies formatting settings such as tabs and alignment for a selection to apply to a another selection and stores them on the Clipboard.  
<span id="page-162-0"></span>**Paste Ruler (Command-Control-V).** Applies formatting settings (that have been saved to the Clipboard) to the selected object.