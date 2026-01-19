<!-- Chunk 285 | Source: 2005-12 Apple Human Interface Guidelines.pdf | Est. Tokens: 600 -->
In the Print dialog, user options are provided via the features pop-up menu, which displays panes drawn and controlled by printing dialog extensions (PDEs). PDEs are provided by the operating system, printer modules, and applications. Apple provides a number of printing panes. The standard Print dialog is shown in Figure 13-46.  
<span id="page-220-0"></span>**Figure 13-46** A Print dialog (a sheet attached to a document window)  
![](images/_page_220_Picture_3.jpeg)  
Options for choosing paper type and print quality are displayed through the features pop-up menu. You can create custom print panes by following the interface guidelines provided throughout this document and the layout guidelines described in ["Positioning Full-Size Controls"](#page-282-1) (page 283). Here are some specific guidelines to keep in mind if you implement custom printing features:  
- Choose a menu item name that doesn't conflict with menu items already in the features pop-up menu.
- The menu item (the pane name) should help users easily determine the options the pane contains.
- Make sure the features you implement are appropriate for your application. For example, an option to print in reverse order should be provided by the operating system, not by your application. (Implementing this feature requires the application to know the hardware's capabilities.)
- Make interdependencies among options clear to users. For example, if a user selects double-sided printing, the option to print on transparencies should become unavailable.
- Separate more advanced features from frequently used features. When the user chooses to display the advanced features, there should be an "advanced options" title above the advanced controls.
- Provide visual feedback (such as the preview in the Layout pane of the Print dialog) when appropriate. A thumbnail showing the effect of changing a tone control, for example, helps users determine desired settings.
- <span id="page-220-1"></span>■ Save a user's printing preferences for a document, at least while the document is open. Provide a way for users to save custom settings.  
**Carbon:** You can write a PDE to customize panes in the Page Setup or Print dialogs. For more information, see *Extending Printing Dialogs* in Printing Documentation.  
**Cocoa:** You can implement an accessory view by using NSPageLayout and NSPrintPanel, both Application Kit classes.