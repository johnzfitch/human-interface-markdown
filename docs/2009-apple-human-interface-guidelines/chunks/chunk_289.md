<!-- Chunk 289 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 571 -->
When you need to allow users to view or manipulate a potentially large set of items in a dialog, you can use a list view to display them. (To learn more about using a list view in a window, see "List [Views"](#page-332-0) (page 333); to learn about the different types of buttonsin a dialog,see ["Dismissing](#page-240-1) Dialogs" (page 241).) The layout guidelines in this section differ slightly, depending on whether the dialog displays an icon.  
**Note:** The layout guidelinesin thissection apply to all dialogsthat contain a list view, regardless of the dialog type. See ["Dialogs"](#page-234-0) (page 235) for more information on the types of dialogs that are available.  
To achieve a clean, well-balanced layout of a list view in a dialog that does not contain an icon, follow these guidelines:  
- If there is introductory text above the list, left-align the list view with it.
- Left-align the leftmost dialog button (or Help button, if there is one) with the list view.
- Right-align the rightmost button with the list view.  
Figure 16-11 shows a dialog that does not display any text above the list view. Note that the buttons below the list are aligned with the list's side edges and that the margins on both sides of the window are equal in width (the dialog in Figure 16-11 uses 20-pixel wide side margins).  
<span id="page-354-0"></span>**Figure 16-11** Example layout of a list view in a dialog without an icon  
![](images/_page_354_Picture_3.jpeg)  
If you need to display an icon in a dialog with a list view, follow these guidelines:  
- Place the icon to the left of the introductory text. If there is no introductory text, place the icon to the left of the list view.
- Left-align the introductory text, list view, and leftmost button.
- If you need to include a Help button, left-align it with the icon. Note that this is the only user interface element that should appear directly below the icon.  
<span id="page-354-1"></span>Figure 16-12 shows an example of how a list view in a dialog with an icon might look. Note that the margins on both sides of the window are equal in width (the dialog in Figure 16-12 uses 20-pixel wide side margins).  
**Figure 16-12** Example layout of a list view in a dialog with an icon  
![](images/_page_354_Picture_10.jpeg)