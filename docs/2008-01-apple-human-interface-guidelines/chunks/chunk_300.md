<!-- Chunk 300 | Source: 2008-01 Apple Human Interface Guidelines.pdf | Est. Tokens: 734 -->
<span id="page-347-1"></span>A **group box**, like a separator (described in ["Separators"](#page-345-1) (page 346)), is used to break a window into distinct logical areas. A group box has a heavier look than a separator, which means that it provides a more pronounced differentiation of content. For example, the Expose pane in Expose & Spaces preferences uses group boxes to separate screen-corner functionality from keyboard and mouse shortcuts, as shown in Figure 15-90.  
**Figure 15-90** Group boxes can organize controls in a window  
![](images/_page_347_Picture_8.jpeg)  
#### Group Box Usage  
Use a group box when you want users to understand logical groupings of controls in a window. You can use group boxes in the window-body area, including within tab-view panes.  
Although group boxes are very useful for separatinglogical collections of content, avoid nestingthem when possible; nested group boxes use a lot of space, and it can be difficult to perceive individual boundaries when group boxes are nested too deeply. Instead, consider using a separator or white space togroup contentwithin agroup box. (See ["Separators"](#page-345-1) (page 346) for more information on using separators; see ["Grouping](#page-363-1) With White Space" (page 364) for guidance on using white space.) Strive to place roughly equal numbers of controls in each group box in a window, to create a visually balanced appearance.  
#### Group Box Contents and Labeling  
Group boxes can be untitled ortitled. If titled, they may have text-onlytitles, checkbox titles, or pop-up menu titles. If the group box uses a checkbox title, the items in the group box should be active only when the checkbox is selected.  
Group box titles should have sentence-style capitalization. See ["Capitalization](#page-135-0) of Interface Element [Labels](#page-135-0) and Text" (page 136) for more information on this style.  
#### Group Box Specifications  
**Control sizes**: There are no standard sizes for group boxes; you control the size of the boundaries based on the needs of your window. As you place a group box in your window, be sure to follow the spacing recommendations described below.  
**Label spacing and fonts**: Group box titles can use different font sizes, depending on the size of the rest of the controls and text in your window:  
<span id="page-348-0"></span>■ Regular size: System font ■ Small: Small system font  
■ Mini: Mini system font  
**Control spacing**: Leave at least 20 pixels from the edge of the group box to the edge of the window. Nesting group boxes isn't recommended, because it wastes space. However, if you decide to nest group boxes, see "A [Changeable](#page-354-0) Pane Dialog" (page 355) for some spacing guidelines.  
#### Group Box Implementation  
Group boxes are available in Interface Builder. To create one using Application Kit programming interfaces, use the NSBox class.  
#### **C HAPTER 1 5**  
Controls