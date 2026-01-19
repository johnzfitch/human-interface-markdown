<!-- Chunk 10 | Source: 1996 Human Interface Guidelines for Mac OS 8 (WWDC Release).pdf | Est. Tokens: 722 -->
In Mac OS 8, there are two sizes of fonts used in all human interface elements. The big system font replaces Chicago 12. It is used for most headings and text. The small system font replaces Geneva 10 and Geneva 9 which were used for some labels and explanatory text. There is also an emphasized version of the small system font which can be used for headings of group boxes [\(page 17\)](#page-16-0).  
There are multiple system fonts. There is a constant set of system fonts that the user cannot change by adding or removing fonts. You need to use the system fonts for display in any and all interface elements. Special characters that appear in the interface, such as keyboard glyphs (the character that represents the Command key), are available through the system fonts. Therefore, you shouldn't create custom menus to display special characters, but use the existing characters. Each theme specifies a default font to appear in all of its elements. The user can change which font is displayed using a control panel.  
For layout purposes when you are designing your dialog boxes, you can use Chicago 12 as a guide because each big system font uses the same metrics. You can use Geneva 10 for layout purposes for the small system font.  
When you create your dialog boxes, specify the big system font or the small system font, then regardless of which font a theme specifies or the user has installed and chooses, your dialog boxes appear appropriately. Don't call fonts by name. If you feel you must override a panel's default font, see the "Introduction to the Mac OS 8 Toolbox" chapter in the document *Human Interface Toolbox* for more information. [Figure 29](#page-31-0) shows examples of the small system font and the big system font in a dialog box using one of the system fonts.  
Fonts **31**  
**Figure 29** Examples of system fonts  
<span id="page-31-0"></span>![](images/_page_31_Figure_2.jpeg)  
Don't use Geneva 9 point font any longer. It doesn't have the non-Roman characters necessary for use on localized systems, the keyboard glyphs, or Unicode support. Instead, use the small system font wherever you were using Geneva 9 point.  
All system fonts print well at 300 dpi and 600 dpi. The big system font is a bold-like font that dithers on a black-and-white monitor so that it is readable. This Apple manual was written, edited, and composed on a desktop publishing system using Apple Macintosh computers and FrameMaker software. Line art was created using Adobe ™ Illustrator and Adobe Photoshop.  
Text type is Palatino<sup>®</sup> and display type is Helvetica<sup>®</sup>. Bullets are ITC Zapf Dingbats<sup>®</sup>. Some elements, such as program listings, are set in Adobe Letter Gothic.  
WRITER
Lori E. Kaplan  
DEVELOPMENTAL EDITOR
Laurel Rezeau  
ILLUSTRATOR
Sandee Karr  
PRODUCTION EDITOR
Gerri Gray  
Special thanks to  
Pat Coleman and Elizabeth Moller