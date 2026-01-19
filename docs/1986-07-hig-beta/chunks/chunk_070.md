<!-- Chunk 70 | Source: 1986-07 Human Interface Guidelines (Second Beta Draft).pdf | Est. Tokens: 2827 -->
(  
(  
Performing actions on a system in an indirect fashion reduces the user's sense of direct manipulation. To give users the feeling that they're in control of their computers, many of an application's features are implemented with controls: graphic objects that, when manipulated with the mouse, cause instant action with visible or audible results. Controls also can change settings to modify future actions.  
There are several types of controls. Buttons, check boxes, radio buttons, and scroll bars are all available from the Macintosh Toolbox. You can also design your own controls, such as the thermometer and gauge shown in Figure 44.  
![](images/_page_88_Picture_9.jpeg)  
Figure 45. Controls  
#### Buttons  
A button is a small object labeled with text. Clicking or pressing a button performs the action described by the button's label. Label each button according to the *result* of pressing it. If the question is *Save Changes?* then *Save* and *Don't Save* are more meaningful than *Yes* and *No*. If one button in a group is the default button, it has a darker border than the other(s).  
Buttons usually perform instantaneous actions, such as completing operations defined by a dialog box or acknowledging error messages. They can also perform continuous actions, in which case the effect of pressing on the button (holding it down) would be the same as the effect of clicking it repeatedly.  
Two particular buttons, OK and Cancel, are especially important in dialogs and alerts. They're discussed under "Dialogs" and "Alerts."  
#### Check Boxes and Radio Buttons  
Whereas buttons perform instantaneous or continuous actions, check boxes and radio buttons let the user choose among alternative values for a parameter.  
Check boxes act like toggle switches (comparable to the text attributes in the Style menu). Check boxes are used to indicate the state of a parameter that must be either off or on. The parameter is on if the box is checked; otherwise it's off. The check boxes appearing together in a given context are independent of each other—any number of them can be off or on.  
Radio buttons typically occur in groups. They're called radio buttons because they act like the buttons on a car radio. They're mutually exclusive—at any given time, exactly one button in the group is on. Clicking one button in a group turns whichever button was on before.  
Both check boxes and radio buttons are accompanied by text that identifies what each button does.  
#### Dials  
A dial displays the value, magnitude, or position of something in the application or system. Some dials also allow the user to alter that value. Dials are predominantly analog devices, displaying their values graphically and allowing the user to change the value by dragging an indicator. Dials may also have a digital display.  
The most common example of a dial is the scroll bar. The indicator of the scroll bar is the scroll box that represents the relative position of the window over the whole length of the document. The user can drag the scroll box to change that position.  
#### Dialogs  
Commands in menus normally act on only one object. If a command needs more information before it can be performed, it presents a dialog box to gather the additional  
information from the user. The user can tell which commands bring up dialog boxes because they're followed by an ellipsis (...) in the menu.  
A dialog box is a rectangle that may contain text, controls, and icons. There should be some text in the box that indicates which command caused the dialog box to appear and what the function of the box is.  
The user sets controls and text fields in the dialog box to provide the needed information. When the application puts up the dialog box, it should set the controls to some default setting and fill in the text fields with default values, if possible. One of the text fields (the "first" field) should be highlighted, so that the user can change its value just by typing in the new value. If all the text fields are blank, there should be an insertion point in the first field.  
Editing text fields in a dialog box should conform to the guidelines detailed under "Text Editing."  
When the user is through editing an item,  
- Pressing the Tab key accepts the changes made to the item and selects the next item in sequence.
- Clicking in another item accepts the changes made to the previous item and selects the newly clicked item.  
Dialog boxes are either modal or modeless.  
A modal dialog box is one that the user must explicitly dismiss before doing anything else, such as making a selection outside the dialog box or choosing a command.  
![](images/_page_90_Figure_10.jpeg)  
Figure 46. A Modal Dialog Box  
Because it restricts the user's freedom of action, this type of dialog box should be used only sparingly. In particular, the user can't choose a menu item while a modal dialog box is up and therefore can do only the simplest kinds of text editing. For these reasons, the main use of a modal dialog box is when it's important for the user to complete an operation before doing anything else.  
A modal dialog box usually has at least two buttons: OK and Cancel. OK dismisses the dialog box and performs the original command according to the information provided; it can be given a more descriptive name than "OK." Cancel dismisses the dialog box and cancels the original command. It should always be called "Cancel."  
A dialog box can have other kinds of buttons as well. These may or may not dismiss the dialog box. The **default button** (the safest or most likely choice in the current situation) is boldly outlined to call attention to it. The default button is the one that takes effect if the user presses Return or Enter on the keyboard instead of one of the screen buttons. Pressing the Return or Enter key has the same effect as clicking the default button. If there's no default button, Return and Enter have no effect.  
A special type of modal dialog box is one with no buttons. This type of box just informs the user of a situation without eliciting any response. It usually describe the progress of an ongoing operation. Because it has no buttons, the user has no way to dismiss it. Therefore, the application must display it long enough for the user to read it before taking it down.  
A modeless dialog box allows the user to perform other operations without dismissing the dialog box.  
![](images/_page_91_Picture_4.jpeg)  
Figure 47. A Modeless Dialog Box  
A modeless dialog box is dismissed by clicking in the close box or by choosing Close. The dialog box is also dismissed implicitly when the user chooses Quit. It's usually a good idea for the application to remember the contents of the dialog box after it's dismissed, so that, when it's opened again, it can be restored exactly as it was.  
Controls work the same way in modeless dialog boxes as in modal dialog boxes, except that buttons never dismiss the dialog box. In this context, the OK button means "go ahead and perform the operation, but leave the dialog box up," whereas the Cancel button usually terminates an ongoing operation.  
A modeless dialog box can also have text fields. Because the user can choose menu commands, the full range of editing capabilities can be made available.  
#### Alerts  
Every user of every application is liable to do something that the application won't understand or can't cope with in a normal manner. Alerts give applications a way to respond to errors not only in a consistent manner, but in stages according to the severity of the error, the user's level of expertise, and the particular history of the error. The two kinds of alerts are beeps and alert boxes.  
Beeps are used for errors that are both minor and immediately obvious. For example, if the user tries to backspace past the left boundary of a text field, the application could beep instead of displaying an alert box.  
An alert box looks like a modal dialog box, except that it's somewhat narrower and appears lower on the screen. An alert box is primarily a one-way communication from the system to the user. The only way the user can respond is by clicking buttons or by pressing Enter or Return. Alert boxes, therefore, might contain dials and buttons but usually not text fields, radio buttons, or check boxes.  
![](images/_page_92_Picture_3.jpeg)  
Figure 48. A Typical Alert Box  
There are three types of alert boxes:  
- Note. A minor mistake that wouldn't have any disastrous consequences if left as is.
- Caution. An operation that may or may not have undesirable results if it's allowed to continue. The user is given the choice whether or not to continue.
- Stop. A serious problem or other situation that requires remedial action by the user.  
An application can define different responses for each of several stages of an alert, so that if the user persists in the same mistake, the application can issue increasingly helpful (or sterner) messages. A typical sequence is for the first two occurrences of the mistake to result in a beep, and for subsequent occurrences to result in an alert box. This type of sequence is especially appropriate when the mistake is one that has a high probability of being accidental (for example, when the user chooses Cut when there's no text selection).  
How the buttons in an alert box are labeled depends on the nature of the box. If the box presents the user with a situation in which no alternative actions are available, the box has a single button that's labeled OK. Clicking this button means "I've read the alert." If the user is given alternatives, then typically the alert is phrased as a question that can be answered "yes" or "no." In this case, buttons labeled Yes and No are appropriate, although variations such as Save and Don't Save are also acceptable. OK and Cancel can be used, as long as their meanings aren't ambiguous.  
The default button is boldly outlined and takes effect if the user presses Return or Enter.  
Use icons whenever possible. Graphics can better describe some error situations than words, and familiar icons help users better distinguish between alternatives. Icons should contain no words, and they should contain no symbols unique to a particular culture.  
Generally, it's better to be polite than abrupt, even if it means lengthening the message. The role of the alert box is to be helpful and make constructive suggestions, not to give orders. But its focus is to help the user solve the problem, not to give an academic (no  
matter how interesting) description of the problem itself. It's important to phrase messages in alert boxes so that users aren't left guessing the real meaning. Avoid computer jargon.  
Make alert messages self-explanatory. The user should never have to refer to a book or reference card to fmd out what an alert message means. Test your alert messages to be sure they tell the user exactly what needs to be done.  
The best way to make an alert message understandable is to think carefully through the error condition itself. Can the application handle this without an error? Is the error specific enough so that the user can fix the situation? What are the recommended solutions? Can the exact item causing the error be displayed in the alert message?  
*i'*(