<!-- Chunk 281 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 1447 -->
<span id="page-337-1"></span>A **tab view** provides a convenient way to present information in a multipane format. The tab control is displayed horizontally centered across the top edge of a content area. Users click a tab to see the content associated with it. For example, QuickTime preferences provides five tabs, each of which displays a group of preference settings, as shown in Figure 15-84.  
**Figure 15-84** A tab view allows switching among multiple panes in a window  
![](images/_page_337_Picture_7.jpeg)  
#### Tab View Usage  
<span id="page-337-4"></span>Use a tab view when you want to present a small number of different content views in one place within a window. Depending on the size of the window, you can create a tab view that contains between two and about six tabs.  
The content area below a tab is called a **pane**, and each tab is attached to a specific pane. Within a pane, provide controls and information that affect only the objects contained in the pane, not objects in the rest of the window or in other panes.  
You can position a tab view in two different ways (see "Tab View [Specifications"](#page-338-0) (page 339) for examples of these styles):  
● Extend the side and bottom edges of the tab view to the window edges, so there is no window-body area visible to the sides or below the tab view.  
Use this style when you want the contents of the entire window-body area below the tab control to be managed by the tabs.  
● Inset the tab view in the window, so that a margin of window-body area is visible on all sides of the tab view.  
Use this style when you want to be able to provide controls that affect the entire window, not just the current pane. (The global controlsshould be in the window-body area below the tab view;see "Tab [View](#page-338-0) [Specifications"](#page-338-0) (page 339) for layout guidelines for this style.)  
**Note:** Multiple rows of tabs are not supported in Mac OS X.  
If you have too many tabs to fit into a window properly, it's acceptable, although not highly recommended, to use instead a pop-up menu to change the contents of a group box [\(Figure](#page-340-1) 15-87 (page 341) shows how this looks). Another alternative to a tab view is a segmented control, which also provides a way to switch among panes. A segmented control looks similar to a tab view, but it is not attached to the panes (see ["Segmented](#page-285-0) Controls" (page 286) for more information about segmented controls).  
#### Tab View Contents and Labeling  
Each tab requires a label that describes the contents of the attached pane. Nouns or very short noun phrases are generally best, although a verb (or short verb phrase) might make sense in some contexts. Tab labels should have title-style capitalization (see ["Capitalization](#page-135-0) of Interface Element Labels and Text" (page 136) for more information on this style).  
<span id="page-338-0"></span>Within a pane, you can use standard window-body controls, such as push buttons, checkboxes, sliders, and text fields. You can also provide icons and information displayed as static text fields, when necessary.  
#### Tab View Specifications  
**Control sizes**: Tab views are available in regular, small, and mini sizes. The tab height is fixed for each size, but you control the size of the pane area. The tab heights for each size are listed below:  
● Regular size: 20 pixels.  
● Small: 17 pixels.  
● Mini: 15 pixels.  
**Label spacing and fonts**: The tab labels should be in a font that's proportional to the size of the tab view control. In addition, the label should be placed so that there are equal margins of space before and after it. The guidelines below provide the specifications you should use for tab labels:  
- Regular size: System font. Center in tab, leaving 12 pixels on each side.
- Small: Small system font. Center in tab, leaving 10 pixels on each side.
- Mini: Mini system font. Center in tab, leaving 8 pixels on each side.  
**Control spacing**: Whether you decide to inset a tab view in a window or extend its edges to the window sides and bottom, you should place the top edge of the tab view 12 or 14 pixels below the bottom edge of the title bar (or toolbar, if there is one). If you choose to inset a tab view in a window, you should leave a margin of 20 pixels between the sides and bottom of the tab view and the sides and bottom of the window (although 16 pixels is also an acceptable margin-width). If you need to provide controls below the tab view, leave enough space below the tab view so the controls are 20 pixels above the bottom edge of the window and 12 pixels between the tab view and the controls. Figure 15-85 shows how an inset tab view should look.  
<span id="page-339-2"></span><span id="page-339-0"></span>**Figure 15-85** Tab panes inset from the edge of a window  
![](images/_page_339_Picture_4.jpeg)  
<span id="page-339-1"></span>If you choose to extend the tab view sides and bottom so that they meet the window sides and bottom, you should leave a margin of at least 20 pixels between the content in the tab view and the tab-view edges. Figure 15-86 shows how this should look.  
**Figure 15-86** Tab panes edge to edge  
![](images/_page_339_Picture_7.jpeg)  
If you need to use a pop-up menu at the top of a group box (because, for example, you have too many tabs to fit in the window), be sure to center the control along the top of the group box, as shown in Figure 15-87:  
<span id="page-340-1"></span>**Figure 15-87** Acceptable, but not recommended, usage of a pop-up menu to switch among panes  
![](images/_page_340_Picture_4.jpeg)  
#### Tab View Implementation  
Tab views are available in Interface Builder. To create one using Application Kit programming interfaces, use the NSTabView class.