<!-- Chunk 120 | Source: 2002 Aqua Human Interface Guidelines.pdf | Est. Tokens: 1174 -->
<span id="page-114-5"></span><span id="page-114-4"></span>Printing dialogs include the Print dialog and the Page Setup dialog. In the Print dialog, user options are provided via the features pop-up menu, which contains panes drawn and controlled by printing dialog extensions (PDEs). PDEs are provided by the operating system, printer modules, and applications.  
Apple provides a number of printing panes. The standard Print dialog is shown in Figure 6-14.  
Dialog Behavior **115**  
#### **CHAPTER 6**  
Dialogs  
**Figure 6-14** A Print dialog (a sheet attached to a document window)  
![](images/_page_115_Picture_3.jpeg)  
Options for choosing paper type and print quality should look like the dialog in Figure 6-15. You can customize the quality descriptions. If you want to provide more options, make them visible only when the user clicks a disclosure triangle.  
**Figure 6-15** Options for choosing paper type and print quality  
![](images/_page_115_Picture_6.jpeg)  
Figure 6-16 shows an example of a Print dialog with its advanced features visible. Most users won't need access to controls for specifying precise percentages of cyan, yellow, and magenta; the dialog opens initially displaying only the top portion of the dialog. The user must click a disclosure triangle to display the advanced options.  
<span id="page-116-0"></span>Advanced options should always have a title. Use help tags when necessary to explain options (see ["Help Tags" \(page 238\)\)](#page-237-0).  
**Figure 6-16** The expanded Color Options pane, showing advanced options  
![](images/_page_116_Figure_5.jpeg)  
If you create custom printing dialogs, follow the interface guidelines provided throughout this book and the layout guidelines described in ["Positioning Controls](#page-148-1)  [in Dialogs and Windows" \(page 149\).](#page-148-1) Here are some specific guidelines to keep in mind if you implement custom printing features.  
- Make sure the item name that appears in the features pop-up menu doesn't conflict with already existing menu items.
- Make sure the menu item (the pane name) helps users easily determine the options the pane contains.
- Make sure the features you implement are appropriate for your application. For example, an option to print in reverse order should be provided by the operating system, not your application. (Implementing this feature requires the application to know the hardware's capabilities.)
- Make interdependencies among options clear to users. For example, if a user selects double-sided printing, the option to print on transparencies should become unavailable.
- Separate more advanced features from frequently used features. When the user chooses to display the advanced features, there should be an "advanced options" title above the advanced controls.
- Provide visual feedback (such as the preview in the Layout pane of the Print dialog) when appropriate. A thumbnail showing the effect of changing a tone control, for example, helps users determine desired settings.
- Save a user's printing preferences for a document, at least while the document is open. Provide a way for users to save custom settings.  
<span id="page-117-1"></span><span id="page-117-0"></span>If you are a Carbon application developer, you can write a PDE to customize panes in the Page Setup or Print dialogs. For more information, see *Inside Mac OS X: Extending Printing Dialogs,* [available on the Mac OS X developer documentation](http://developer.apple.com/techpubs/macosx/Carbon/graphics/CarbonPrintingManager/carbonprintingmgr.html)  [website. If you are a Cocoa application developer, you can implement an accessory](http://developer.apple.com/techpubs/macosx/Carbon/graphics/CarbonPrintingManager/carbonprintingmgr.html)  view by using NSPageLayout and NSPrintPanel, both Application Kit classes.  
<span id="page-118-4"></span><span id="page-118-0"></span>**Controls** are graphic objects that cause instant actions or visible results when the user manipulates them with the mouse. Standard controls include push buttons, scroll bars, radio buttons, checkboxes, sliders, and pop-up menus.  
<span id="page-118-3"></span><span id="page-118-2"></span><span id="page-118-1"></span>For Carbon developers, the Control Manager determines the overall appearance of all controls. For Cocoa developers, the overall appearance of interface elements is provided by the Application Kit. You are responsible for positioning the controls within your windows, according to the guidelines given here.  
For implementation information, Carbon developers should see *Inside Mac OS X: Handling Carbon Windows and Controls,* available on the Mac OS X developer documentation website.