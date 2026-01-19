<!-- Chunk 219 | Source: 2001 Aqua Human Interface Guidelines.pdf | Est. Tokens: 663 -->
Mac OS X supports six standard fonts for interface elements.  
<span id="page-188-2"></span><span id="page-188-1"></span>**Figure 10-1** Mac OS X standard fonts  
| Font |
|------|
|      |
|      |
|      |
|      |
|      |
|      |
|      |  
<span id="page-188-8"></span><span id="page-188-3"></span>The **system font** is used for text in menus, modeless dialogs, and titles of document windows. For an example of this font, open a Finder menu.  
<span id="page-188-7"></span><span id="page-188-4"></span>**Note:** For text in lists and tables, you can use 12-point Lucida Grande Regular instead of the system font.  
<span id="page-188-6"></span>The **small system font** is used for informative text in alerts (see [Figure 6-2 \(page 96\).](#page-95-0) It is also the default font for headers in lists, for help tags, and for text in the small versions of many controls. You can also use it to provide additional information about settings in various windows, such as the QuickTime pane in System Preferences.  
Fonts  
If your application creates text documents, use the **application font** as the default for user-created content.  
<span id="page-189-4"></span><span id="page-189-3"></span>The **label font** is used for labels with controls such as sliders and icon bevel buttons. You should rarely need to use this font in dialogs, but may find it useful in palettes. For an example of this font used to label a slider control, click the Text-to-Speech tab in Speech preferences.  
Use **emphasized system fonts** sparingly. Emphasized (bold) system font is used in only two places in the interface: the application name in an About window (see ["The About Window" \(page 88\)](#page-87-0)) and the message text in an alert (see [Figure 6-2](#page-95-0) [\(page 96\)\)](#page-95-0). You might use emphasized small system font to title a group of settings that appear without a group box, or for brief informative text below a text field. For an example of the emphasized small system font, click the Date or Numbers tab in International preferences.  
<span id="page-189-2"></span><span id="page-189-1"></span><span id="page-189-0"></span>Carbon developers creating nonstandard elements with text are responsible for drawing their own anti-aliased text, via the Appearance Manager DrawThemeTextBox functions or the Control Manager static text control. In Cocoa, all text is anti-aliased by default.  
<span id="page-190-5"></span><span id="page-190-4"></span><span id="page-190-0"></span>This chapter describes the overall philosophy behind Aqua icons and how to design application, document, toolbar, and other types of icons for Mac OS X.