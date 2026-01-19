<!-- Chunk 222 | Source: 2002 Aqua Human Interface Guidelines.pdf | Est. Tokens: 1660 -->
Mac OS X supports seven standard fonts for interface elements (in Roman systems). Whenever your application specifies a font, use the system-defined constants shown in Table 10-1 (page 199); avoid naming a specific font and point size. Using the system constants ensures that your application always displays the appropriate fonts, regardless of changes to the OS.  
<span id="page-196-0"></span>**Figure 10-1** Mac OS X standard fonts  
| Use                            | Font and size |  |
|--------------------------------|---------------|--|
| System font                    |               |  |
| System font (emphasized)       |               |  |
| Small system font              |               |  |
| Small system font (emphasized) |               |  |
| Application font               |               |  |
| Label font                     |               |  |
| Mini system font               |               |  |
|                                |               |  |  
<span id="page-196-4"></span><span id="page-196-1"></span>The **system font** is used for text in menus, modeless dialogs, and titles of document windows. For an example of this font, open a Finder menu.  
<span id="page-196-2"></span>**Note:** For text in lists and tables, you can use 12-point Lucida Grande Regular instead of the system font.  
Fonts  
<span id="page-197-3"></span><span id="page-197-2"></span>The **small system font** is used for informative text in alerts (see [Figure 6-2](#page-98-0) [\(page 99\)\)](#page-98-0). It is also the default font for headings in lists, for help tags, and for text in the small versions of many controls. You can also use it to provide additional information about settings in various windows, such as the QuickTime pane in System Preferences.  
If your application creates text documents, use the **application font** as the default for user-created content.  
<span id="page-197-5"></span><span id="page-197-4"></span>The **label font** is used for labels with controls such as sliders and icon bevel buttons. You should rarely need to use this font in dialogs, but may find it useful in utility windows when space is at a premium. For an example of this font used to label a slider control, click the Text-to-Speech tab in Speech preferences.  
If necessary, the **mini system font** can be used for utility window labels and text. (Use it wherever you used 9-point Geneva in Mac OS 9.)  
Use **emphasized system fonts** sparingly. Emphasized (bold) system font is used in only two places in the interface: the application name in an About window (see ["The About Window" \(page 92\)](#page-91-0)) and the message text in an alert (see [Figure 6-2](#page-98-0) [\(page 99\)\)](#page-98-0). You might use emphasized small system font to title a group of settings that appear without a group box, or for brief informative text below a text field. For an example of the emphasized small system font, click the Date or Numbers tab in International preferences.  
<span id="page-197-1"></span><span id="page-197-0"></span>To have the Aqua look and feel, all user-visible text in your application should be anti-aliased. this can be achieved by using one of the system fonts listed. Carbon developers creating nonstandard interface elements with text or displaying any user-visible text are responsible for drawing their own anti-aliased text via the Appearance Manager DrawThemeTextBox functions or the Control Manager static text control. In Cocoa, all text is anti-aliased by default.  
#### **CHAPTER 10**  
#### Fonts  
<span id="page-198-2"></span><span id="page-198-1"></span>For user-created text, Carbon developers should use the Multilingual Text Engine (MLTE) functions and Apple Type Services for Unicode Imaging (ATSUI) to provide text-editing support. Carbon developers can use the NSTextField or NSTextView classes. Table 10-1 shows the constants to use in Carbon functions and the NSFont methods to use in Cocoa.  
<span id="page-198-0"></span>**Table 10-1** Font constants and methods in Carbon and Cocoa  
| Font                            | Appearance Manager constants    | Application Kit methods                                          |
|---------------------------------|---------------------------------|------------------------------------------------------------------|
| System font                     | kThemeSystemFont                | [NSFont systemFontOfSize:[NSFont<br>systemFontSize]]             |
| Emphasized system<br>font       | kThemeEmphasizedSystemFont      | [NSFont<br>boldsystemFontOfSize:[NSFont<br>systemFontSize]]      |
| Small system font               | kThemeSmallSystemFont           | [NSFont systemFontOfSize:[NSFont<br>smallSystemFontSize]]        |
| Emphasized small<br>system font | kThemeSmallEmphazisedSystemFont | [NSFont<br>boldSystemFontOfSize:[NSFont<br>smallSystemFontSize]] |
| Label font                      | kThemeLabelFont                 | [NSFont labelFontOfSize:[NSFont<br>labelFontSize]]               |
| Mini system font                | kThemeUtilityWindowTitleFont    | [NSFont paletteFontOfSize:0]                                     |  
**CHAPTER 10**  
Fonts  
<span id="page-200-1"></span><span id="page-200-0"></span>This chapter describes the overall philosophy behind Aqua icons and how to design application, document, toolbar, and other types of icons for Mac OS X.  
Icon design in Mac OS X is significantly different from previous versions of the Mac OS. In Mac OS 9 and earlier, graphic limitations constrained designers to use a highly symbolic style. Icons consisted of "jaggy" illustrations that emphasized straight lines rotated in increments of 45 degrees.  
**Figure 11-1** Traditional application icon and Mac OS X icon  
![](images/_page_200_Picture_5.jpeg)  
![](images/_page_200_Picture_6.jpeg)  
![](images/_page_200_Picture_7.jpeg)  
Aqua offers a new photo-illustrative icon style—it approaches the realism of photography, but uses the features of illustrations to convey a lot in a small space. Icons can be represented in 128 x 128 pixels to allow ample room for detail. Anti-aliasing makes curves and nonrectilinear lines possible. Alpha channels and translucency allow for complex shading and dimensionality. All of these qualities pave the way for lush imagery that enables you to create vibrant icons that communicate in ways never before possible.  
<span id="page-201-1"></span>To represent your application in Mac OS X, it's essential to create high-quality Aqua-style application icons that scale well in the various places the icon appears the Dock, Finder previews, alert dialogs, and so on.