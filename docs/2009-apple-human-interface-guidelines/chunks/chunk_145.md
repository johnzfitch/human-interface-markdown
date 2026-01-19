<!-- Chunk 145 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 1103 -->
<span id="page-128-4"></span><span id="page-128-3"></span>Mac OS X supports standard fonts for interface elements. Whenever your application specifies a font, use the system-defined constants shown in [Table](#page-129-1) 10-1 (page 130); avoid using a specific font and point size. Using the system constants ensuresthat your application always displaysthe appropriate fontsregardless of changes to the Mac OS.  
<span id="page-128-2"></span>The **system font** (Lucida Grande Regular 13 point) is used for text in menus, dialogs, and full-size controls.  
<span id="page-128-5"></span>Use the **emphasized system font** (Lucida Grande Bold 13 point) sparingly. It is used for the message text in alerts (see [Figure](#page-237-0) 14-47 (page 238)).  
The **small system font** (Lucida Grande Regular 11 point) is used for informative text in alerts (see [Figure](#page-237-0) [14-47](#page-237-0) (page 238)). It is also the default font for column headings in lists, for help tags, and for small controls. You can also use it to provide additional information about settings in various windows, such as in the QuickTime preferences.  
Use the **emphasized small system font** (Lucida Grande Bold 11 point) sparingly. You might use it to title a group of settings that appear without a group box, or for brief informative text below a text field.  
The **mini system font** (Lucida Grande Regular 9 point) is used for mini controls. It can also be used for panel labels and text.  
An **emphasized mini system font** (Lucida Grande Bold 9 point) is available for casesin which the emphasized small system font is too large.  
<span id="page-128-7"></span><span id="page-128-6"></span>If your application creates text documents, use the **application font** (Lucida Grande Regular 13 point) as the default font for user-created content.  
The **label font** (Lucida Grande Regular 10 point) is used for the labels on toolbar buttons and to label tick marks on full-size sliders. You should rarely need to use this font. For an example of this font used to label a slider control, see the Dock size slider in Dock preferences.  
Use the **view font** (Lucida Grande Regular 12 point) as the default font of text in lists and tables.  
Note that the Lucida Grande font family includes mono-spaced numeric characters and variably-spaced alphabetics.  
Fonts **129**  
All user-visible text in your application should be anti-aliased, which is automatic if you use one of the standard system fonts.  
<span id="page-129-1"></span>Table 10-1 shows the constants to use in Carbon functions and the NSFont methods to use in Cocoa.  
**Table 10-1** Carbon constants and Cocoa methods for system fonts  
| Font                            | Carbon constants                    | Cocoa methods                                                                                   |
|---------------------------------|-------------------------------------|-------------------------------------------------------------------------------------------------|
| System font                     | kThemeSystemFont                    | [NSFont systemFontOfSize:[NSFont<br>systemFontSizeForControlSize:<br>NSRegularControlSize]]     |
| Emphasized system<br>font       | kThemeEmphasized<br>SystemFont      | [NSFont boldSystemFontOfSize:[NSFont<br>systemFontSizeForControlSize:<br>NSRegularControlSize]] |
| Small system font               | kThemeSmallSystemFont               | [NSFont systemFontOfSize:[NSFont<br>systemFontSizeForControlSize:<br>NSSmallControlSize]]       |
| Emphasized small<br>system font | kThemeSmall<br>EmphasizedSystemFont | [NSFont boldSystemFontOfSize:[NSFont<br>systemFontSizeForControlSize:<br>NSSmallControlSize]]   |
| Mini system font                | kThemeMiniSystemFont                | [NSFont systemFontOfSize:[NSFont<br>systemFontSizeForControlSize:<br>NSMiniControlSize]]        |
| Emphasized mini<br>system font  | Not Available                       | [NSFont boldSystemFontOfSize:[NSFont<br>systemFontSizeForControlSize:<br>NSMiniControlSize]]    |
| Application font                | kThemeApplicationFont               | [NSFont userFontOfSize:0.0]                                                                     |
| Label font                      | kThemeLabelFont                     | [NSFont labelFontOfSize:[NSFont<br>labelFontSize]]                                              |