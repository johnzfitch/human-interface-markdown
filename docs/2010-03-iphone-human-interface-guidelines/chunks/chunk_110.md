<!-- Chunk 110 | Source: 2010-03 iPhone Human Interface Guidelines.pdf | Est. Tokens: 1880 -->
iPhone OS 3.0 and later includes four predefined table-cell styles you can use to quickly and easily produce the most common layouts for table rows in both plain and grouped tables. Note that, programmatically, these styles are applied to a table view's cell, which is an object that tells the table how to draw its rows.  
When you use the standard table-cell styles, your application is consistent with the built-in applications, which benefits you in a couple of ways:  
- Users more quickly understand how your application works
- Your application remains consistent without a lot of extra work on your part, if the standard table-cell styles are enhanced in the future  
If you want to lay out your table rows in a nonstandard way, it's better to create a custom table-cell style than to significantly alter a standard one. "Customizing Cells" in *Table View Programming Guide for iPhone OS* helps you learn how to create your own cells.  
Be aware that text truncation is automatic in all table-cell styles. Generally speaking, you should ensure that your text is as succinct as possible to avoid displaying truncated words or phrases that are difficult for users to understand. Specifically, text truncation can be more or less of a problem, depending on which cell style you use and on where truncation occurs.  
iPhone OS provides the following standard table-cell styles:  
■ The **default** table-cell style (UITableViewCellStyleDefault) includes an optional image on the left, followed by a left-aligned text label in black.  
<span id="page-92-0"></span>**Figure 8-4** The default table-cell style in a grouped table (left) and a plain table (right)  
![](images/_page_92_Picture_3.jpeg)  
![](images/_page_92_Picture_4.jpeg)  
The text label's appearance implies that it represents an item name or title and its left-alignment makes the list easy to scan. This makes the default style good for displaying a list of items that do not need to be differentiated by supplementary information.  
Short text labels are best, but if truncation is unavoidable, try to ensure that the most important information is contained in the first few words.  
■ The **subtitle** table-cell style (UITableViewCellStyleSubtitle) includes an optional image on the left, followed by a left-aligned text label on one line and a left-aligned detail text label on the line below. The text label is in black and the detail text label is in a smaller, gray font.  
<span id="page-93-0"></span>**Figure 8-5** The subtitle table-cell style in a grouped table (left) and a plain table (right)  
![](images/_page_93_Picture_3.jpeg)  
![](images/_page_93_Picture_4.jpeg)  
The prominent appearance of the text label implies that it represents an item name or title, while the subtle appearance of the detail text label implies that it contains subsidiary information related to the item. The left-alignment of the text labels makes the list easy to scan. This table-cell style works well when list items might look similar, because users can use the additional information in the detail text labels to help distinguish items named in the text labels.  
Text labels should be short to avoid truncation. If truncation is unavoidable, focus on putting the most important information in the first few words. If the detail text label is truncated, users are not likely to mind too much because they view it as information that enhances or supplements the item named by the text label.  
■ The **value 1** table-cell style (UITableViewCellStyleValue1) displays a left-aligned text label in black on the same line with a right-aligned detail text label in a smaller, blue font. Images do not fit well in this style.  
<span id="page-94-0"></span>**Figure 8-6** The value 1 table-cell style in a grouped table (left) and a plain table (right)  
![](images/_page_94_Picture_3.jpeg)  
![](images/_page_94_Picture_4.jpeg)  
The appearance of the text label implies that it represents an item name or title, while the appearance of the detail text label implies that it provides important information that is closely associated with the item.  
The left-alignment and font of the text label help users scan the list for the item they want, and the right-alignment of the detail text label draws their attention to the related information it provides. This table-cell style works well to display an item's current value, possibly selected from a sublist.  
Text truncation can be difficult to avoid in this layout (because both labels are on the same line), but it's worth the effort. Otherwise, you lose the active space between the labels that helps users understand the relationship between the two pieces of information.  
Although you can use the value 1 table-cell style in either a plain or a grouped table, its appearance is better suited to a grouped table. For example, the Usage screen in Settings uses the value 1 style in grouped tables:  
<span id="page-95-0"></span>**Figure 8-7** The value 1 table-cell style looks best in a grouped table  
![](images/_page_95_Picture_3.jpeg)  
<span id="page-95-1"></span>■ The **value 2** table-cell style (UITableViewCellStyleValue2) displays a right-aligned text label in a small blue font, followed on the same line by a left-aligned detail text label in a larger, black font. Images do not fit well in this style.  
**Figure 8-8** The value 2 table-cell style in a grouped table (left) and a plain table (right)  
![](images/_page_95_Picture_6.jpeg)  
![](images/_page_95_Picture_7.jpeg)  
The right-alignment, constrained width, and font of the text label imply that it functions as a heading or caption for the important information in the more prominent, left-aligned detail text label.  
In this layout, the labels are aligned towards each other at the same location in every row. This creates a crisp, vertical margin between the text labels and the detail text labels in the list, which helps users focus on the first words of the detail text label. If you allow the text labels to be truncated, you lose the sharpness of this vertical strip, which can make it harder for users to scan the information in the detail text labels.  
<span id="page-96-0"></span>Although you can use the value 2 table-cellstyle in either a plain or a grouped table, it looks much better in a grouped table. For example, the Info screen in Contacts uses the value 2 table-cell style in grouped tables:  
![](images/_page_96_Picture_5.jpeg)  
**Figure 8-9** The value 2 table-cell style looks best in a grouped table  
**Note:** All standard table-cell styles also allow the addition of a table-view element, such as the checkmark or the disclosure indicator. Be aware that adding these elements decreases the width of the cell available for the title and subtitle.  
You might be able to avoid text truncation by increasing the height of a table row to accommodate text wrapping, but this can be problematic:  
- You have to programmatically check the text length and decide if wrapping might occur. You must make this determination for both portrait and landscape orientation, because the table width affects text wrapping.
- You should avoid displaying wrapped text in one orientation, but not the other.
- Variable row heights can negatively impact the overall table view performance in your application, regardless of table-view style.  
Table Views, Text Views, and Web Views  
Finally, although variable row heights are acceptable in grouped tables, they can make a plain table look cluttered and uneven.