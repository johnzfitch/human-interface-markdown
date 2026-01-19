<!-- Chunk 283 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 777 -->
A **separator** is a thin vertical or horizontal line. Separators have a lightweight appearance that's good for separating controls into categories or subgroups of related functionality. For example, the Appearance preferences pane (shown in Figure 15-88) provides controls that determine a wide range of high-level appearance characteristics,such as highlight color and the placement ofscroll arrows. Although each control affects some aspect of the Mac OS X appearance, the window uses separators to create four subgroups of related controls.  
<span id="page-341-1"></span>**Figure 15-88** Separators divide controls into subgroups or categories  
![](images/_page_341_Picture_6.jpeg)  
#### Separator Usage  
Use a separator to divide a window body into distinct visual parts. You can place separators either vertically or horizontally, depending on the overall layout of your window.  
**Note:** The separator control is not used in a toolbar; the vertical separator you can see in a toolbar is an NSToolbarSeparatorItem object (which is available in Interface Builder).  
In general, you should avoid stretching a separator to span the entire width or height of a window; a separator that spans a window can give the appearance of slicing a window into unrelated rows or columns. If the categories of content in your window are completely unrelated, and it might be confusing to see all categories simultaneously, it might be better to display each category in a pane of a tab view instead (see ["Tab](#page-337-0) [Views"](#page-337-0) (page 338) for more information about using a tab view).  
#### Separator Labeling  
A label can accompany a separator, but it is not required. A separator labelshould have title-style capitalization (see ["Capitalization](#page-135-0) of Interface Element Labels and Text" (page 136) for information on this style).  
The separator line should be at the base of the text of the label. [Figure](#page-316-0) 15-62 (page 317)shows how thislooks.  
#### Separator Specifications  
<span id="page-342-0"></span>**Control sizes**: Separators are available in a single thickness, but you determine their length. Figure 15-89 shows a vertical and a horizontal separator.  
![](images/_page_342_Figure_9.jpeg)  
**Label spacing and fonts**: Separator labelsshould be in a font that correspondsto the controlsin the window. Specifically, separator labels should use:  
- System font, when other controls are regular size.
- Small system font, when other controls are small.
- Mini system font, when other controls are mini.  
Separator labels should be 2 pixels from the beginning of the separator control.  
**Control spacing**: Separators should be at least 10 pixels away from other controls. Both ends of a separator should be an equal distance from the window edges. If you use more than one separator in a window, be sure every separator with the same orientation (vertical or horizontal) is the same length.  
#### Separator Implementation  
Separators are available in Interface Builder. To create one using Application Kit programming interfaces, use the NSBox class.