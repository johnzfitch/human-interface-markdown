<!-- Chunk 89 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 654 -->
Users initiate an Undo operation by shaking the device, which displays an alert that allows them to:  
- Undo what they just typed
- Redo previously undone typing
- Cancel the undo operation  
![](images/_page_138_Picture_5.jpeg)  
You can support the Undo operation in a more general way in your app by specifying:  
- The actions users can undo or redo
- The circumstances under which your app should interpret a shake event as the shake-to-undo gesture
- How many levels of undo to support  
To learn how to implement this behavior in code, see *Undo Architecture* . If you support undo and redo in your app, follow these guidelines to provide a good user experience.  
**Supply brief descriptive phrases thattell users precisely whatthey're undoing orredoing.** iOS automatically supplies the strings "Undo " and "Redo " (including a space after the word) for the undo alert button titles, but you need to provide a word or two that describes the action users can undo or redo. For example, you might supply the text Name or Address Change, to create button titles such as "Undo Name" or "Redo Address Change." (Note that the Cancel button in the alert cannot be changed or removed.)  
![](images/_page_139_Picture_3.jpeg)  
**Avoid supplying text that is too long.** A button title that is too long is truncated and is difficult for users to decipher. And because this text is in a button title, use title-style capitalization and do not add punctuation.  
**Avoid overloading the shake gesture.** Even though you can programmatically set when your app interprets a shake event as shake to undo, you run the risk of confusing users if they also use shake to perform a different action. Analyze user interaction in your app and avoid creating situations in which users can't reliably predict the result of the shake gesture.  
**Use the system-provided Undo and Redo buttons only if undo and redo are fundamental tasks in your app.** Remember that the shake gesture is the primary way users initiate undo and redo, and that it can be confusing to offer two different ways to perform the same task. If you decide it's important to provide explicit, dedicated controls for undo and redo, you can place the system-provided buttons in the navigation bar. (To learn more about these buttons, see "Toolbar and [Navigation](#page-147-0) Bar Buttons" (page 148).)  
**Clearly relate undo and redo capability to the user's immediate context, and not to an earlier context.** Consider the context of the actions you allow to be undone or redone. In general, users expect their changes and actions to take effect immediately.