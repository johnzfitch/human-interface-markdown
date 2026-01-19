<!-- Chunk 231 | Source: 2008-01 Apple Human Interface Guidelines.pdf | Est. Tokens: 2134 -->
<span id="page-238-1"></span>A **sheet** is a modal dialog attached to a particular document or window, ensuring that the user never loses track of which window the dialog applies to. Because a sheet is attached to the window from which it emerges, a sheet does not have its own title. Figure 14-46 shows an example of a sheet.  
**Figure 14-46** The Save Changes alert: An example of using a sheet to display a document-modal dialog  
![](images/_page_238_Picture_11.jpeg)  
The ability to keep a dialog attached to its pertinent window helps users take full advantage of the Mac OS X window layering model (see "Window [Layering"](#page-223-2) (page 224)). Sheets also allow users to perform other tasks before dismissing the dialog, with no sense of the system being "hijacked" by the application.  
Lay out sheets as you would any other dialog in Mac OS X. For guidelines on laying out a dialog, see "Positioning [Regular-Size](#page-350-1) Controls in a Window Body" (page 351).  
#### **Sheet Behavior**  
Sheets are displayed as an animation that appears to emerge from the window's title bar. When a sheet opens on a window near the edge of the screen and the sheet is wider than the window it's attached to, the sheet moves thewindowawayfrom the edge;when the sheet is dismissed, thewindow returns to its previous position.  
Only one sheet may be open for a window at any one time. A sheet prevents any other operation on that window until the sheet is dismissed. If, when the user responds to a sheet, another sheet for that document must open, the first sheet closes before the second one opens.  
<span id="page-239-1"></span>A sheet on an active documentwindowshould cover(appear on top of) anyactive panels (if necessary). However, if the user leaves a sheet open and clicks another document in the same application, the inactive window and its sheet should go *behind* any open panels.  
In an application that allows multiple windows for the same document (so that the user can see different parts of a document simultaneously), a sheet is not appropriate. Use an application modal dialog in this situation to make it clear that changes to one window affect other windows in the application.  
<span id="page-239-0"></span>In an application that displays multiple documents in a single window at different times, such as in a tabbed browser, a sheet is appropriate even though it applies to only the current document in the view. This is because, in a single-window situation, the user can't move the view and its sheet aside to handle later when choosing to view a different document. Rather, the user in effect dismisses the view's contents when choosing to view a different document. The user should therefore dismiss the sheet on the current view before selecting a different document.  
#### **When to Use Sheets**  
Use sheets for dialogs specific to a document when the user interacts with the dialog and dismisses it before proceeding with work. Here are some examples of when to use sheets:  
- A modal dialogfor an activitythat is specific to a particular document, such as savingor printing.
- A modal dialog that is specific to a single-window application that does not create documents. A single-windowutility program might use a sheet to request acceptance of a licensingagreement from the user, for example.
- Other window-specific dialogs that are typically dismissed by the user before proceeding. Use a sheet when a dialog benefits from being attached to the window as a modal dialog, even if you might otherwise design the dialog as a modeless dialog.  
#### **When Not to Use Sheets**  
Don't use sheets in the following situations:  
■ For dialogs that apply to several windows. Use sheets only when a particular dialog is associated with only one window.  
- For modeless operations in which the dialog should be left open to allow the user to observe the effects of changes applied. Such tasks (find and replace operations, for example) are better suited to modeless dialogs, panels, or drawers.
- <span id="page-240-6"></span>■ On a window that doesn't have a title bar. Sheets should emerge from a definite visual edge.
- When the user will need information in the window that is essential to filling in requested information in the dialog.  
#### <span id="page-240-5"></span><span id="page-240-1"></span>Alerts  
Alerts display messages to inform users of situations that are notable or potentially dangerous. Alerts are modal dialogs.For an alert that applies to one document orin single-windowapplications, display the alert as a sheet. See "When to Use [Sheets"](#page-239-0) (page 240) for guidelines.  
<span id="page-240-0"></span>Figure 14-47 shows the elements of an alert.  
**Figure 14-47** A standard alert  
![](images/_page_240_Picture_9.jpeg)  
<span id="page-240-3"></span><span id="page-240-2"></span>See "A [Standard](#page-357-0) Alert" (page 358) for more information on laying out alerts.  
#### <span id="page-240-4"></span>**The Elements of an Alert**  
<span id="page-240-7"></span>An alert should contain only the following elements:  
- **Alert message text**. This text, in emphasized (bold) system font, provides a short, simple summary of the error or condition that summoned the alert. This should be a complete sentence; often it is presented as a question. See "Writing Good Alert [Messages"](#page-241-2) (page 242) for more information.
- **Informative text**. This text appears in the small system font and provides a fuller description of the situation, its consequences, and ways to get out of it. For example, a warning that an action cannot be undone is an appropriate use of informative text.  
**Important:** Do not leave out the informative text. What you think of as an intuitive alert message might be far from intuitive to your users. Use informative text to reword and expand on the alert message text.  
- <span id="page-241-5"></span>■ **Buttons for addressingthe alert**. Button names should correspond to the action the user performs when pressingthe button—for example, Erase, Save, or Delete. The rightmost button in the dialog, the action button, is the button that confirms the alert message text. The action button is usually, but not always, the default button. (Note that in Cocoa methods, the rightmost button is always referred to as the default button even though it might not be.) For more information, see ["Dismissing](#page-243-0) Dialogs" (page 244).
- <span id="page-241-4"></span>■ **The application icon**. Because of the Mac OS X window layering model (described in ["Window](#page-223-2) [Layering"](#page-223-2) (page 224)), an icon is necessary to make it clear to the user which application is displaying the alert.  
<span id="page-241-6"></span>In rare cases, you may want to display a caution icon in your alert, badged with the application icon as shown in Figure 14-48. A badged alert is appropriate only if the user is performing a task, such as installing software, and a possible side effect of that task would be the inadvertent destruction of data. Don't use a caution icon for tasks whose only purpose is to overwrite or remove data, such as Save or Empty Trash; too-frequent use of the caution icon dilutes its significance.  
<span id="page-241-0"></span>**Figure 14-48** A customized alert showing the caution icon badged with an application icon  
![](images/_page_241_Picture_6.jpeg)  
#### <span id="page-241-3"></span><span id="page-241-2"></span>**Writing Good Alert Messages**  
<span id="page-241-1"></span>A good alert message states clearly what caused the alert to appear and what the user can do about it. Express everything in the user's vocabulary. Figure 14-49 shows an example of an alert message that provides little useful information.  
**Figure 14-49** A poorly written alert message  
![](images/_page_241_Picture_10.jpeg)  
You could improve this message by describing the problem in the user's vocabulary as shown in Figure 14-50.  
<span id="page-242-1"></span>**Figure 14-50** An improved alert message  
![](images/_page_242_Picture_3.jpeg)  
<span id="page-242-2"></span>To make the alert really useful, provide a suggestion about what the user can do about the current situation. Even if the alert serves as a notification to the user and no further action is required, provide as much information as needed to describe the situation. Figure 14-51 shows the alert with additional information.  
**Figure 14-51** A well-written alert message  
![](images/_page_242_Picture_6.jpeg)