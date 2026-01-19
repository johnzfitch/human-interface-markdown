<!-- Chunk 284 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 730 -->
A **group box**, like a separator (described in ["Separators"](#page-341-0) (page 342)), is used to break a window into distinct logical areas. A group box has a heavier look than a separator, which meansthat it provides a more pronounced differentiation of content. For example, the Exposé pane in Exposé & Spaces preferences uses group boxes to separate screen-corner functionality from keyboard and mouse shortcuts, as shown in Figure 15-90.  
<span id="page-343-1"></span>**Figure 15-90** Group boxes can organize controls in a window  
![](images/_page_343_Picture_7.jpeg)  
#### Group Box Usage  
Use a group box when you want users to understand logical groupings of controls in a window. You can use group boxes in the window-body area, including within tab-view panes.  
Although group boxes are very useful for separating logical collections of content, avoid nesting them when possible; nested group boxes use a lot ofspace, and it can be difficult to perceive individual boundaries when group boxes are nested too deeply. Instead, consider using a separator or white space to group content within a group box. (See ["Separators"](#page-341-0) (page 342) for more information on using separators; see ["Grouping](#page-360-1) With White [Space"](#page-360-1) (page 361) for guidance on using white space.) Strive to place roughly equal numbers of controls in each group box in a window, to create a visually balanced appearance.  
#### Group Box Contents and Labeling  
Group boxes can be untitled or titled. If titled, they may have text-only titles, checkbox titles, or pop-up menu titles. If the group box uses a checkbox title, the items in the group box should be active only when the checkbox is selected.  
Group box titles should have sentence-style capitalization. See ["Capitalization](#page-135-0) of Interface Element Labels and [Text"](#page-135-0) (page 136) for more information on this style.  
#### Group Box Specifications  
**Control sizes**: There are no standard sizes for group boxes; you control the size of the boundaries based on the needs of your window. As you place a group box in your window, be sure to follow the spacing recommendations described below.  
<span id="page-344-0"></span>**Label spacing and fonts**: By default, the font size for a group box title is small system font. You can use a different font size if it coordinates better with the overall design of your window.  
**Control spacing**: Leave at least 20 pixels from the edge of the group box to the edge of the window. Nesting group boxes isn't recommended, because it wastes space. However, if you decide to nest group boxes, see "A [Changeable](#page-349-0) Pane Dialog" (page 350) for some spacing guidelines.  
#### Group Box Implementation  
Group boxes are available in Interface Builder. To create one using Application Kit programming interfaces, use the NSBox class.  
#### **CHAPTER 15**  
Controls