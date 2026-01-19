<!-- Chunk 132 | Source: 1985 Apple II Human Interface Guidelines.pdf | Est. Tokens: 644 -->
A modeless dialog box allows the user to perform other operations without dismissing the dialog box. Figure 26 shows a modeless dialog box.  
![](images/_page_126_Picture_7.jpeg)  
Figure 26. A Modeless Dialog Box  
A modeless dialog box is dismissed by clicking in the close box or by choosing Close when the dialog is active. The dialog box is also dismissed implicitly when the user chooses Quit. It's usually a good idea for the application to remember the contents of the dialog box after it's dismissed, so that when it's opened again, it can be restored exactly as it was.  
Controls work the same way in modeless dialog boxes as in modal dialog boxes, except that buttons never dismiss the dialog box. In this  
1/15/85 Tognazzini  
DIALOGS 111  
context, the OK button means "go ahead and perform the operation, but leave the dialog box up", while Cancel usually terminates an ongoing operation.  
A modeless dialog box can also have text fields; since the user can choose menu commands, the full range of editing capabilities can be made available.  
Alerts  
An alert box looks like a modal dialog box, except that it's somewhat narrower and appears lower on the screen. An alert box is primarily a one-way communication from the system to the user; the only way the user can respond is by clicking buttons. Therefore alert boxes might contain dials and buttons, but usually not text fields, radio buttons, or check boxes. Figure 27 shows a typical alert box.  
![](images/_page_127_Picture_6.jpeg)  
Figure 27. An Alert Box  
How the buttons in an alert box are labeled depends on the nature of the box. If the box presents the user with a situation in which no alternative actions are available, the box has a single button that says OK. Clicking this button means "I have read the alert." If the user is given alternatives, then typically the alert is phrased as a question that can be answered "yes" or "no". In this case, buttons labeled Yes and No are appropriate, although some variation such as Save and Don't Save is also acceptable. OK and Cancel can be used, as long as their meaning isn't ambiguous.  
[As noted above, the following paragraph needs to be excised if we go with the "OK equals Return" scheme.]  
The preferred (safest) button to use in the current situation is boldly outlined. This is the alert's default button; its effect occurs if the user presses Return or Enter.  
For further information on beeps, the types of alert messages, and how and when to write one, read Alert Messages in the Generic Interface  
1/15/85 Tognazzini  
section.