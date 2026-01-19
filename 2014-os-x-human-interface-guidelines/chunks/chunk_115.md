<!-- Chunk 115 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 356 -->
The **Help button** opens a window that displays app-specific help.  
![](images/_page_187_Picture_6.jpeg)  
**APINote:** To define a Help button in your code, use the setBezelStyle: method of NSButtonCell with NSHelpButtonBezelStyle as the argument.  
The Help button is always a clear, circular button. The Help button is available in a single size and it always contains the standard OS X question mark graphic.  
When users click a Help button, the system-provided Help Viewer app opens to a page in the current app's help book. An app can determine whether the help book should open to a top-level page or to a page that is appropriate for the context of the button.  
Don't create a custom button to perform the function of the standard Help button.  
In dialogs (including preferences windows) and drawers, the Help button can be located in either bottom corner. In a dialog that includes OK and Cancel buttons (or other buttons used to dismiss the dialog), the Help button should be in the lower-left corner, vertically aligned with the buttons. In a dialog that doesn't include OK and Cancel buttons, such as a preferences window, the Help button should be in the lower-right corner. For example, the Mail Signatures preference pane displays a Help button in the lower-right corner.  
![](images/_page_188_Picture_2.jpeg)  
For information on providing help in your app, see User [Assistance](#page-270-0) (page 271).