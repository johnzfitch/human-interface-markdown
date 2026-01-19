<!-- Chunk 51 | Source: 1986-12 Human Interface Guidelines (Final Draft).pdf | Est. Tokens: 1021 -->
Selecting the single object of an operation then choosing a menu command works well whenever operations are simple and act on only one object. For those times when a command requires more than one object or needs additional information before it can be executed, the Apple Desktop Interface provides:  
- Dialogs, to allow the user to provide the needed additional information before a command is executed
- Alerts, to notify the user whenever an unusual situation occurs  
Because dialogs and alerts often use controls, controls are described in this section, even though they're also used in other kinds of windows.  
#### **Controls**  
When actions are performed indirectly, the user's sense of direct manipulation is reduced. To give users the feeling that they're in control of their computers, many of an application's features can be implemented with **controls**: graphic objects that, when manipulated with the mouse, cause instant action with visible or audible results. Controls also can change settings to modify future actions.  
There are many types of controls. Buttons, check boxes, radio buttons, and scroll bars are all available from the Macintosh Toolbox. You can also design your own controls, such as the thermometer and gauge shown in Figure 19.  
![](images/_page_60_Figure_1.jpeg)  
Figure 19 Controls  
#### **Buttons**  
A **button** is a small screen object usually labeled with text. Clicking or pressing a button performs the action described by the button's label. Button labels should be unambiguous. Often, a label describing the *result* of pressing the button ("Erase," "Revert," or "Don't Save" for example) is clearer than just "Yes," "No," or "OK." If one button the default button (that is, if pressing Return or Enter has the same result as pressing this button), then it is doubly outlined to distinguish it from the other buttons.  
Buttons usually perform instantaneous actions, such as completing operations defined by a dialog box or acknowledging error messages. They can also perform continuous actions, in which case the effect of *pressing* on the button (rather than just clicking it) would be the same as the effect of clicking it repeatedly.  
Two particular buttons, OK and Cancel, are especially important in dialogs and alerts. They're discussed under "Dialogs" and "Alerts."  
#### Check boxes and radio buttons  
Check boxes and radio buttons let the user choose among alternatives.  
Check boxes act like toggle switches (comparable to the text attributes in the Style menu). Use check boxes to indicate the state of an option that must be either off or on. The option is on if the box is checked; otherwise it's off. The check boxes appearing together in a given context are independent of each other—any number of them can be off or on. In Figure 19, check boxes 1 and 2 are on; if a user clicked box 3, all three boxes would be on.  
Radio buttons typically occur in groups. They're called radio buttons because they act like the buttons on a car radio. They're mutually exclusive—at any given time, exactly one button in the group is on. Clicking one button in a group turns off whichever button was on before. In Figure 19, radio button 2 is on; if a user clicked button 3, button 2 would go off.  
If more than one group of buttons is visible at one time, the groups must be made distinct from one another.  
Both check boxes and radio buttons are accompanied by text that identifies what each button does.  
#### Dials  
A **dial** displays the value, magnitude, or position of something in the application or system. Some dials also allow the user to alter that value. Dials are predominantly analog devices, displaying their values graphically and sometimes allowing the user to change the value by dragging an **indicator**. Dials may also have a digital display.  
The most common example of a dial is the scroll bar. The indicator of the scroll bar is the scroll box that represents the relative position of the window over the whole length of the document. The user can drag the scroll box to change that position.