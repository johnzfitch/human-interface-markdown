<!-- Chunk 107 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 546 -->
<span id="page-176-2"></span>A small subset of controls have a display style that makes them suitable for use in the window-frame areas (that is, in the toolbar or a bottom bar); these controls are listed in Table 36-1.  
**Table 36-1** Control and style combinations designed for use in window-frame areas  
| Control (API name)                                                  | Style                             | Example |
|---------------------------------------------------------------------|-----------------------------------|---------|
| Round<br>textured<br>button<br>(NSButton)                           | NSTexturedRounded<br>BezelStyle   |         |
| Textured<br>rounded<br>segmented<br>control<br>(NSSegmentedControl) | NSSegmentStyle<br>TexturedRounded |         |  
![](images/_page_177_Picture_1.jpeg)  
\*Note that you can use the NSTexturedRoundedBezelStyle style of pop-up menu to place an Action menu in a toolbar. For more information about Action menus, see [Action](#page-191-0) Menu (page 192).  
You can see examples of most of these types of window-frame controls in the Mail toolbar.  
![](images/_page_177_Picture_4.jpeg)  
**Don't use the window frame–specific control styles in the window body.** The control and style combinations listed Table 36-1 are specially designed to look good on the window-frame, whether it's translucent or opaque. *These control styles don't look good in the window body* . In particular, these control styles can use inactive and other appearances that don't harmonize with standard control styles.  
**Don't use window-body controls or styles in the window frame.** All system-provided controls and styles other than those listed in Control and style combinations designed for use in the window frame are designed to look good in the window body and its content regions, and *should not be used in the window frame* . (If you want to create a freestanding, full-color toolbar icon button, use NSToolbarItem; for additional guidelines on designing toolbars, see [Designing](#page-136-0) a Toolbar (page 137).)  
If your window includes a bottom bar (which is not typical), you can use window-frame controls in the bottom bar.