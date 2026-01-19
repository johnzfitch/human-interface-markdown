<!-- Chunk 115 | Source: 2004-08 Apple Human Interface Guidelines.pdf | Est. Tokens: 796 -->
<span id="page-91-1"></span>If your application provides functions for formatting text, you can include a **Format menu** as a top-level menu or as a submenu of the Edit menu. It may be appropriate to group some items that are in the Format menu into submenus, such as Font, Text, or Style.  
**Figure 7-18** A Format menu  
![](images/_page_91_Picture_10.jpeg)  
<span id="page-91-8"></span><span id="page-91-6"></span><span id="page-91-5"></span>**Show Fonts (Command-T)**. The first item in the Format menu should be Show Fonts, which displays the Fonts window.  
**Carbon:** Use the FPShowHideFontPanel function. See the *Fonts Window Services Reference* in Text & International Documentation.  
**Cocoa:** Use NSFontPanel.  
**Show Colors (Command-Shift-C)**. Displays the Colors window.  
**Carbon:** Use the NPickColor function to implement a Colors window. See *Color Picker Manager Reference* in Carbon Graphics & Imaging Documentation.  
**Cocoa:** Use the NSColorPanel class. See *Using Color* in Cocoa Graphics & Imaging Documentation.  
<span id="page-92-9"></span><span id="page-92-4"></span>**Bold (Command-B)**. Boldfaces the selected text or toggles boldfaced text on and off. If used as a toggle, indicate when it is on by having a checkmark next to the command in the menu.  
<span id="page-92-12"></span>**Italic (Command-I).** Italicizes the selected text or toggles italic text on and off. If used as a toggle, indicate when it is on by having a checkmark next to the command in the menu.  
<span id="page-92-3"></span>**Underline (Command-U)**. Underlines the selected text or toggles underlined text on and off. If used as a toggle, indicate when it is on by having a checkmark next to the command in the menu.  
<span id="page-92-6"></span>**Bigger (Command–Shift–equal sign)**. Causes the selected item to increase in size in defined increments.  
<span id="page-92-10"></span>**Smaller (Command-hyphen)**. Causes the selected item to decrease in size in defined increments.  
<span id="page-92-11"></span>**Copy Style (Command-Option-C)**. Copies the style—font, color, and size for text—of the selected item. It may be appropriate to put this item in a Style submenu along with related items.  
<span id="page-92-5"></span><span id="page-92-1"></span>**Paste Style (Command-Option-V)**. Applies the style of one object to the selected object.  
<span id="page-92-13"></span>**Align Left (Command-{)**. Left-aligns a selection.  
<span id="page-92-2"></span>**Center (Command-|)**. Center-aligns a selection.  
<span id="page-92-14"></span>**Justify**. Evenly spaces a selection.  
<span id="page-92-7"></span>**Align Right (Command-})**. Right-aligns a selection.  
<span id="page-92-8"></span>**Show Ruler**. Displays a formatting ruler.  
<span id="page-92-15"></span>**Copy Ruler (Command-Control-C)**. Copies formatting settings such as tabs and alignment for a selection to apply to a another selection and stores them on the Clipboard.  
<span id="page-92-18"></span><span id="page-92-16"></span><span id="page-92-0"></span>**Paste Ruler (Command-Control-V)**. Applies formatting settings (that have been saved to the Clipboard) to the selected object.