<!-- Chunk 113 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 1274 -->
(UITableViewCellStyleValue1). The value 1 style displays a left-aligned title with, on the same line, a right-aligned subtitle in a lighter font.  
**Value 2** (UITableViewCellStyleValue2). The value 2 style displays a right-aligned title in a blue font, followed on the same line by a left-aligned subtitle in a black font. Images don't fit well in this style.  
In the value 2 layout, the crisp vertical margin between the text and the detail text helps users focus on the first words of the detail text label.  
| Value 2 Cell Style                   |  |
|--------------------------------------|--|
| Text Label Detail text label         |  |
| Dahlia This is a dahlia              |  |
| Daisies These are daisies            |  |
| Dandelion This is a dandelion        |  |
| Echinacea This is echinacea          |  |
| Lavender This is a field of lavender |  |  
**Note:** All fourstandard table-cellstyles allow the addition of table view elements,such as a checkmark or disclosure indicator. Adding these elements decreases the width of the cell available for the title and subtitle.  
Use a table view to display large or small amounts of information cleanly and efficiently. For example:  
- **Provide a list of options from which users can select.** You can use the checkmark to show users the currently selected options in the list.
- Use either a plain or a grouped table view to display a list of choices that appears when users tap an item in a table row. Use a plain table view to display a list of choices that appears when users tap a button or other UI element that is *not* in a table row.
- **Display hierarchical information.** The plain table style is well suited for displaying a hierarchy of information. Each list item can lead to a different subset of information displayed in another list. Users follow a path through the hierarchy by selecting one item in each successive list. The disclosure indicator tells users that tapping anywhere in the row reveals the subset of information in a new list.
- **Display conceptually grouped information.** Both table view styles allow you to provide context by supplying header and footer views between sections of information.  
In iOS 6.0 and later, you can use a header-footer view—that is, an instance of UITableViewHeaderFooterView—to display text or a custom view in a header or footer. To learn how to use a header-footer view in your code, see *UITableViewHeaderFooterView Class Reference* .  
Follow these guidelines when you use table views:  
**Always provide feedback when users select a list item.** Users expect a table row to become highlighted briefly when they tap a selectable item in it. After tapping, users expect a new view to appear (or the row to display a checkmark) to indicate that the item has been selected or enabled.  
**If table content is extensive or complex, avoid waiting until all the data is available before displaying anything.** Instead, fill the onscreen rows with textual data immediately and display more complex data—such as images—as they become available. This technique gives users useful information right away and increases the perceived responsiveness of your app.  
**Consider displaying "stale" data while waiting for new data to arrive.** Although this technique isn't recommended for appsthat handle frequently changing data, it can help more static apps give userssomething useful right away. Before you decide to do this, gauge how often the data changes and how much users depend on seeing fresh data quickly.  
**If the data is slow loading or complex, show users that processing is continuing.** If a table contains only complex data, it may be difficult to display anything useful right away. In these rare cases, it's important to avoid displaying empty rows, because empty rows can imply that your app hasstalled. Instead, the table should display a spinning activity indicator, along with an informative label (such as "Loading…") centered in the screen. This behavior reassures users that processing is continuing.  
**If appropriate, use a custom title for the Delete button.** If it helps users to better understand the way your app works, you can create a title to replace the system-provided Delete title.  
**As much as possible, use succinct text labels to avoid truncation.** Truncated words and phrases can be difficult for users to scan and understand. Text truncation is automatic in all table cell styles, but it can present more or less of a problem, depending on which cell style you use and on where truncation occurs.  
**Avoid combining an index with table view elements that are displayed on the right edge of the table.** Table view elementsthat are displayed on the right edge of the table—such asthe disclosure indicator—interfere with the index.  
**Create a custom table cell style if you want to lay out your table rows in a nonstandard way.** It's better to create a custom table cell style than to significantly alter a standard one. To learn how to create your own cells, see "Customizing Cells" in *Table View Programming Guide for iOS* .