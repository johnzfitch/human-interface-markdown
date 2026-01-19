<!-- Chunk 127 | Source: 2001 Aqua Human Interface Guidelines (Preliminary).pdf | Est. Tokens: 589 -->
Mac OS X supports six standard font mappings.  
<span id="page-152-1"></span>**Table 9-1** Mac OS X standard fonts  
| Use                            | Font |
|--------------------------------|------|
| System font                    |      |
| System font (emphasized)       |      |
| Small system font              |      |
| Small system font (emphasized) |      |
| Application font               |      |
| Label font                     |      |
|                                |      |  
<span id="page-152-4"></span>**System font** is used for message text, or the main text, in all dialogs. It is also the default font for lists and tables. For an example of this font, look at the message text string in the Carbon Views Palette of Interface Builder.  
<span id="page-152-3"></span>**Small system font** is used for informative text, as described in ["Writing Good Alert](#page-181-0)  [Messages" \(page 182\).](#page-181-0) This is the default font for headers in lists and for Help Tags. You can also use it to provide additional information about settings in various windows, such as the QuickTime pane in System Preferences. For an example of this font, look at the informative text string in the Carbon Views Palette of Interface Builder.  
Fonts  
<span id="page-153-2"></span>**Label font** is used for labels with controls such as sliders and icon bevel buttons. You should rarely need to use this font in dialogs, but may find it useful in palettes. For an example of this font, click the Text-to-Speech tab in Speech preferences.  
<span id="page-153-0"></span>Use **emphasized system fonts** sparingly. You might use them to title a group of settings that appear without a group box, or for brief informative text below a text field. For an example of the emphasized system font, click the Date or Numbers tab in International preferences.  
<span id="page-153-1"></span>Carbon developers creating nonstandard element with text are responsible for drawing their own anti-aliased text, via the Appearance Manager DrawThemeText APIs or the Control Manager StaticText control. In Cocoa, all text is anti-aliased by default.  
<span id="page-154-4"></span><span id="page-154-0"></span>This chapter describes the overall philosophy behind Aqua icons and how to design application, document, toolbar, and other types of icons for Mac OS X.