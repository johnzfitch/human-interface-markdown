<!-- Chunk 77 | Source: 2004-08 Apple Human Interface Guidelines.pdf | Est. Tokens: 1101 -->
<span id="page-50-4"></span>Mac OS X supports standard fonts for interface elements. Whenever your application specifies a font, use the system-defined constants shown in [Table 4-1](#page-51-1) (page 52); avoid using a specific font and point size. Using the system constants ensures that your application always displays the appropriate fonts regardless of changes to the Mac OS.  
The **system font** (Lucida Grande Regular 13 pt) is used for text in menus, dialogs, and full-size controls.  
<span id="page-50-6"></span>Use the **emphasized system font** (Lucida Grande Bold 13 pt) sparingly. It is used for the message text in alerts (see [Figure 9-2](#page-135-2) (page 136)).  
The **small system font** (Lucida Grande Regular 11 pt) is used for informative text in alerts (see [Figure](#page-135-2) [9-2](#page-135-2) (page 136)). It is also the default font for column headings in lists, for help tags, and for small controls. You can also use it to provide additional information about settings in various windows, such as the QuickTime pane in System Preferences.  
Use the **emphasized small system font** (Lucida Grande Bold 11 pt) sparingly. You might use it to title a group of settings that appear without a group box, or for brief informative text below a text field.  
<span id="page-50-3"></span>The **mini system font** (Lucida Grande Regular 9 pt) is used for mini controls. It can also be used for utility window labels and text.  
An **emphasized mini system font** (Lucida Grande Bold 9 pt) is available for cases in which the emphasized small system font is too large.  
If your application creates text documents, use the **application font** (Lucida Grande Regular 13 pt) as the default font for user-created content.  
Fonts **51**  
Text  
<span id="page-51-2"></span>The **label font** (Lucida Grande Regular 10 pt) is used for the labels on toolbar buttons and to label tick marks on full-size sliders. You should rarely need to use this font. For an example of this font used to label a slider control, see the Spoken User Interface pane in Speech preferences.  
<span id="page-51-3"></span>Use the **view font** (Lucida Grande Regular 12pt) as the default font of text in lists and tables.  
Note that the Lucida Grande font family includes mono-spaced numeric characters and variably-spaced alphabetics.  
All user-visible text in your application should be anti-aliased, which is automatic if you use one of the standard system fonts.  
Table 4-1 shows the constants to use in Carbon functions and the NSFont methods to use in Cocoa.  
**Table 4-1** Carbon constants and Cocoa methods for system fonts  
<span id="page-51-1"></span><span id="page-51-0"></span>  
| Font                            | Carbon constants                | Cocoa methods                                                                                      |
|---------------------------------|---------------------------------|----------------------------------------------------------------------------------------------------|
| System font                     | kThemeSystemFont                | [NSFont<br>systemFontSizeForControlSize:<br>NSRegularControlSize]                                  |
| Emphasized system<br>font       | kThemeEmphasizedSystemFont      | [NSFont<br>boldsystemFontOfSize:[NSFont<br>systemFontSizeForControlSize:<br>NSRegularControlSize]] |
| Small system font               | kThemeSmallSystemFont           | [NSFont<br>systemFontSizeForControlSize:<br>NSSmallControlSize]                                    |
| Emphasized small<br>system font | kThemeSmallEmphazisedSystemFont | [NSFont<br>boldSystemFontOfSize:[NSFont<br>systemFontSizeForControlSize:<br>NSSmallControlSize]]   |
| Mini system font                | kThemeMiniSystemFont            | [NSFont<br>systemFontSizeForControlSize:<br>NSMiniControlSize]                                     |
| Emphasized mini<br>system font  | Not Available                   | [NSFont<br>boldSystemFontOfSize:[NSFont<br>systemFontSizeForControlSize:<br>NSMiniControlSize]]    |
| Application font                | kThemeApplicationFont           | [NSFont userFontOfSize:0.0]                                                                        |
| Label font                      | kThemeLabelFont                 | [NSFont<br>labelFontOfSize:[NSFont<br>labelFontSize]]                                              |