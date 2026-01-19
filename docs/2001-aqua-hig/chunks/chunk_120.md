<!-- Chunk 120 | Source: 2001 Aqua Human Interface Guidelines.pdf | Est. Tokens: 454 -->
<span id="page-111-5"></span><span id="page-111-4"></span><span id="page-111-2"></span>Printing dialogs include the Print dialog and the Page Setup dialog. User options are provided in the features pop-up menu, which contains panes drawn and controlled by printing dialog extensions (PDEs). PDEs are provided by the operating system, printer modules, and applications. Apple provides a number of printing dialogs.  
<span id="page-112-0"></span>**Figure 6-13** A Print dialog  
![](images/_page_112_Picture_3.jpeg)  
If you create custom printing dialogs, follow the interface guidelines provided throughout this book and the layout guidelines described in ["Positioning Controls](#page-142-1)  [in Dialogs and Windows" \(page 143\).](#page-142-1) Here are some specific guidelines to keep in mind if you implement custom printing features.  
- Make sure the item name that appears in the pop-up menu doesn't conflict with already existing menu items.
- Make sure the pane name enables a user to easily determine the options it contains.
- If you include a help button, put it in the lower-right corner of the pane's group box. To help users distinguish between the purpose of your help button and the general one (the round button with a question mark), your help button should include an icon and a text label identifying your printer.
- Make sure the features you implement are appropriate for your application. For example, an option to print in reverse order should be provided by the operating system, not your application. (Implementing this feature requires the application to know the hardware's capabilities.)
- Make interdependencies among options clear to users. For example, if a user selects double-sided printing, the option to print on transparencies should become unavailable.  
Dialog Behavior **113**