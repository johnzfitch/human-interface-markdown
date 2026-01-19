<!-- Chunk 93 | Source: 2001 Aqua Human Interface Guidelines (Preliminary).pdf | Est. Tokens: 1188 -->
There are various kinds of controls that incorporate text:  
■ A **text input field**, also called an **editable text field**, is a rectangular area in which the user enters text or modifies existing text. The text input field can be active or disabled. It supports keyboard focus and password entry.  
Your application's text input fields should perform appropriate edit checks. For example, if the only legitimate value for a field is a string of digits, the application issue an alert if the user types nondigits. In most cases, the appropriate time to check the field is when the user clicks outside the field or presses the Return, Enter, or Tab key.  
Combination boxes are text input fields that also contain a menu or a list of choices. See ["Combination Boxes" \(page 96\).](#page-95-3)  
- Use a **static text field** for dialog text that the user can't modify. Static text fields have two states: active and dimmed.
- When it provides an obvious user benefit, static text should be selectable. Error message text, for example, could be selectable. Facilitating the copying of text (such as a serial number or a hostname) so that it can be pasted accurately into another context is another example.
- A **scrolling list** can contain as many items as necessary. Users can click an item to select it, or use Shift-click to select more than one item, or scroll through the list without selecting anything. Users can use the arrow keys to navigate through the list, and can quickly select an item by typing the first few characters.  
If an item is too long to fit in the list box, insert ellipses in the middle and preserve the beginning and end of the item. Users often add version numbers to the end of document names.  
Don't use scrolling lists to provide choices in a limited range. Since the full range may not be visible all at once, it can be difficult for users to understand the scope of their choices. Use sliders, discussed in ["Slider Controls" \(page 102\)](#page-101-3), instead.  
#### <span id="page-109-0"></span>Tools for Creating Lists  
<span id="page-109-2"></span>The Data Browser is new component of the Control Manager that provides a standard, easily customized list and column view. Using the Data Browser (available to Carbon applications) provides a convenient way to create consistent sortable, movable, and resizable columns. If your application uses the Data Browser to display lists, they will always look right in Mac OS 9 and Mac OS X. For an example of the Data Browser's column view, see one of the Navigation Services dialogs (Open, Save As) in Mac OS X.  
<span id="page-109-3"></span>Similar functionality is available to Cocoa developers through three classes of interface objects:  
- NSOutlineView. You can see an example in the Mailboxes drawer of the Mail application, which can show a multicolumn hierarchy with disclosure triangles.
- NSTableView. You can see an example in the list of contents of a mailbox in the Mail application. It is multicolumn and row-based.
- NSBrowser. You can see an example in the Open dialog of a Cocoa-based application. This class provides the same sort of hierarchical data as NSOutlineView in column format.  
For more information, see the Data Browser technical note, available at http:// developer.apple.com/technotes/tn/tn2009.html.  
#### <span id="page-109-1"></span>Text Input Field Specifications  
- **Height:** 22 pixels (to accommodate the system font, which is 16 pixels high without line spacing). If you specify the small system font, the text input field dimensions are reduced proportionally.
- **Selection rectangle:** 16 pixels high
- **Keyboard focus ring:** 2 pixels wide at top, 2 pixels wide on three other sides
- **Stacked text fields:** Leave a minimum of 12 pixels between stacked text fields (8 pixels between small stacked text fields).  
For more information about highlighting selections in text fields, see ["Keyboard](#page-140-0)  [Navigation and Focus" \(page 141\)](#page-140-0) and ["Selections in Text" \(page 146\)](#page-145-0).  
<span id="page-110-1"></span>**Figure 7-26** Text input field specifications for large system font  
![](images/_page_110_Figure_4.jpeg)  
<span id="page-110-2"></span>**Figure 7-27** Text input field specifications for small system font  
![](images/_page_110_Figure_6.jpeg)  
#### <span id="page-110-0"></span>List Specifications  
When you define dimensions, make sure that the list displays only full lines of text (don't cut text off vertically), and make sure that the scrolling increment is one list element.  
<span id="page-111-3"></span><span id="page-111-1"></span>**Figure 7-28** Scrolling list specifications  
![](images/_page_111_Figure_3.jpeg)  
![](images/_page_111_Figure_4.jpeg)