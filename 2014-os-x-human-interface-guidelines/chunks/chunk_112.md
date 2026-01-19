<!-- Chunk 112 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 449 -->
A **disclosure triangle** displays(or discloses) information or functionality associated with the primary information in a window.  
![](images/_page_183_Picture_15.jpeg)  
**API Note:** To define a disclosure button in your code, create an NSButton object of type NSPushOnPushOffButton and set the bezel style to NSDisclosureBezelStyle.  
A disclosure triangle is in the closed position (that is, pointing to the right) by default. When the user clicks a disclosure triangle, it points down and the additional information is displayed.  
Use a disclosure triangle when you want to provide a simple default view of something while also allowing usersto view more details or perform additional actions atspecific times. For example, you can use a disclosure triangle to:  
- Reveal more information in dialogs that have a minimal state and an expanded state. For example, you might want to use a disclosure triangle to hide explanatory information about a choice that most users aren't interested in seeing.
- Revealsubordinate itemsin a hierarchical list. For example, the Mail Photo Browser panel uses a disclosure triangle to reveal specific iPhoto categories.  
![](images/_page_184_Figure_6.jpeg)  
**Supply a label for a disclosure triangle in a dialog.** The label should indicate what is disclosed or hidden and it should change, depending on the position of the disclosure triangle. For example, when the disclosure triangle is closed the label might be "Show advanced settings;" when the disclosure triangle is open the label can change to "Hide advanced settings."  
**Don't use a disclosure triangle to display additional choices associated with a specific control.** If you need to do this, use a disclosure button instead. For more information about this control, see Disclosure Button.