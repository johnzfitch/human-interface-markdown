<!-- Chunk 120 | Source: 2011 iOS Human Interface Guidelines.pdf | Est. Tokens: 1917 -->
A table view displays data in rows that can be divided by section or separated into groups. Users flick or drag to scroll through rows or groups of rows. Users tap a table row to select it and use table view controls to add or remove rows, select multiple rows, see more information about a row item, or reveal another table view. A table row highlights briefly when the user taps a selectable item.  
#### **CHAPTER 7**  
iOS UI Element Usage Guidelines  
If a row selection results in navigation to a new screen, the selected row highlights briefly as the new screen slides into place. When the user navigates back to the previous screen, the originally selected row again highlights briefly to remind the user of their earlier selection (it does not remain highlighted).  
iOS defines two styles of table views, which are distinguished mainly by appearance.  
**Plain** tables display rows that extend from side edge to side edge of the screen. Rows can be separated into labeled sections and an optional index can appear vertically along the right edge of the view. A header can appear before the first item in a section and a footer can appear after the last item. By default, the row background is white.  
![](images/_page_107_Picture_5.jpeg)  
**Grouped** tables display groups of rows that are inset from the side edges of the screen. A grouped table view always contains at least one group of list items (one list item per row), and each group always contains at least one item. A group can be preceded by header text and followed by footer text. By default, groups are displayed on a distinctive blue-striped background; inside a group, row background is white. A grouped table view does not include an index.  
![](images/_page_108_Picture_2.jpeg)  
<span id="page-108-0"></span>iOS includes some **table-view elements** that can extend the functionality of table views. Unless noted otherwise, these elements are suitable for use with table views only.  
**Table 7-1** Table-view elements  
| Element | Name                     | Description                                                                                                                                                              |
|---------|--------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|         | Checkmark                | Indicates that the row is selected                                                                                                                                       |
|         | Disclosure indicator     | Displays another table associated with the row                                                                                                                           |
|         | Detail disclosure button | Displays additional details about the row in a new view (for<br>information on how to use this element outside of a table, see<br>"Detail Disclosure Button" (page 126)) |
|         | Row reorder              | Indicates that the row can be dragged to another location in the<br>table                                                                                                |
|         | Row insert               | Adds a new row to the table                                                                                                                                              |
|         | Delete button control    | In an editing context, reveals and hides the Delete button for a row                                                                                                     |
|         | Delete button            | Deletes the row                                                                                                                                                          |  
iOS 3 and later defines four table-cell styles that implement the most common layouts for table rows in both plain and grouped tables. Each cell style is best suited to display a different type of information.  
**Note:** Programmatically, these styles are applied to a table view's cell, which is an object that tells the table how to draw its rows.  
**Default** (UITableViewCellStyleDefault). The default cell style includes an optional image in the left end of the row, followed by a left-aligned title in black.  
![](images/_page_109_Picture_4.jpeg)  
![](images/_page_109_Picture_5.jpeg)  
In the default cell style, the text label's appearance implies that it represents an item name or title and its left-alignment makes the list easy to scan. This makes the default style good for displaying a list of items that do not need to be differentiated by supplementary information.  
**Subtitle** (UITableViewCellStyleSubtitle). The subtitle style includes an optional image in the left end of the row, followed by a left-aligned title on one line and a left-aligned subtitle on the line below. The title is in black and the subtitle is in a smaller, gray font.  
![](images/_page_109_Picture_8.jpeg)  
![](images/_page_109_Picture_9.jpeg)  
In the subtitle cell style, the prominent appearance of the text label implies that it represents an item name or title, whereas the subtle appearance of the detail text label implies that it contains subsidiary information related to the item. The left-alignment of the text labels makesthe list easy to scan. Thistable-cellstyle works well when list items look similar, because users can use the additional information in the detail text labels to help distinguish items named in the text labels.  
**Value 1** (UITableViewCellStyleValue1). The value 1 style displays a left-aligned title in black on the same line with a right-aligned subtitle in a smaller, blue font. Images do not fit well in this style.  
![](images/_page_109_Picture_12.jpeg)  
| Value 1    | Cell Style        |
|------------|-------------------|
| Text Label | Detail text label |
| Dahlia     | This is a dahlia  |
| Daisies    | These are daisies |  
In the value 1 cell style, the appearance of the text label implies that it represents an item name or title, whereas the appearance of the detail text label implies that it provides important information that is closely associated with the item.  
The left-alignment and font of the text label help users scan the list for the item they want, and the right-alignment of the detail text label draws their attention to the related information it provides. This table-cell style works well to display an item's current value, possibly selected from a sublist.  
**Value 2** (UITableViewCellStyleValue2). The value 2 style displays a right-aligned title in a small, blue font, followed on the same line by a left-aligned subtitle in a larger, black font. Images do not fit well in this style.  
![](images/_page_110_Picture_5.jpeg)  
![](images/_page_110_Picture_6.jpeg)  
In the value 2 cellstyle, the right-alignment, constrained width, and font of the text label imply that it functions as a heading or caption for the important information in the more prominent, left-aligned detail text label.  
In this layout, the labels are aligned towards each other at the same location in every row. This creates a crisp, vertical margin between the text labels and the detail text labels in the list, which helps users focus on the first words of the detail text label.  
**Note:** All fourstandard table-cellstyles also allow the addition of a table-view element,such asthe checkmark or the disclosure indicator. Adding these elements decreases the width of the cell available for the title and subtitle.