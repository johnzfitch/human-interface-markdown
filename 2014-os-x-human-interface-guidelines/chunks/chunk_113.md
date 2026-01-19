<!-- Chunk 113 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 395 -->
A **disclosure button** expands a dialog or panel to display a wider range of choicesrelated to a specific selection control.  
![](images/_page_185_Picture_5.jpeg)  
**API Note:** To define a disclosure button in your code, create an NSButton object of type NSPushOnPushOffButton and set the bezel style to NSRoundedDisclosureBezelStyle.  
#### A disclosure button:  
- Contains a small triangular icon.
- Is in the closed position—that is, pointing down—by default. When the user clicks a disclosure button, the window expands to reveal the additional choices, and the disclosure button changes to point up.  
Use a disclosure button when you need to provide additional options that are closely related to a specific list of choices.  
**Don't use a disclosure button to display additional information or functionality, or to display subordinate items in a list.** If you need to display additional information or functionality related to the contents of a window or a section of a window, or if you need a way to reveal subordinate items in a hierarchical list, use a disclosure triangle instead. For more information on this control, see [Disclosure](#page-183-1) Triangle (page 184).  
**Place a disclosure button close to the control to which it's related.** Users need to understand how the expanded choices are related to their current task. For example, TextEdit puts a disclosure button close to the Save As text field, so that users understand that the expanded view of the dialog will help them choose a location for their document.  
![](images/_page_186_Picture_2.jpeg)