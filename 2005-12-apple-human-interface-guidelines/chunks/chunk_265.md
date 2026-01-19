<!-- Chunk 265 | Source: 2005-12 Apple Human Interface Guidelines.pdf | Est. Tokens: 972 -->
<span id="page-203-7"></span>An alert should contain only the following elements:  
- **Alert message text.** This text, in emphasized (bold) system font, provides a short, simple summary of the error or condition that summoned the alert. This should be a complete sentence; often it is presented as a question. See ["Writing Good Alert Messages"](#page-204-1) (page 205) for more information.
- **Informative text.** This text appears in the small system font and provides a fuller description of the situation, its consequences, and ways to get out of it. For example, a warning that an action cannot be undone is an appropriate use of informative text.  
**Important:** Do not leave informative text out. What you think of as an intuitive alert message might be far from intuitive to your users. Use informative text to reword and expand on the alert message text.  
- <span id="page-204-3"></span>■ **Buttons for addressing the alert.** Button names should correspond to the action the user performs when pressing the button—for example, Erase, Save, or Delete. The rightmost button in the dialog, the action button, is the button that confirms the alert message text. The action button is usually, but not always, the default button. Note that in Cocoa methods, the rightmost button is always referred to as the default button even though it might not be. For more information, see ["Dismissing](#page-207-1) [Dialogs"](#page-207-1) (page 208).
- <span id="page-204-2"></span>■ **The application icon.** Because of the Mac OS X window layering model (described in ["Window](#page-189-1) [Layering"](#page-189-1) (page 190)), an icon is necessary to make it clear to the user which application is displaying the alert.  
<span id="page-204-4"></span>In rare cases, you may want to display a caution icon in your alert, badged with the application icon as shown in Figure 13-30. A badged alert is appropriate only if the user is performing a task, such as installing software, and a possible side effect of that task would be the inadvertent destruction of data. Don't use a caution icon for tasks whose only purpose is to overwrite or remove data, such as Save or Empty Trash; too-frequent use of the caution icon dilutes its significance.  
<span id="page-204-0"></span>**Important:** The note, caution, and stop alerts used in Mac OS 9 should not be used in Mac OS X.  
**Figure 13-30** A customized alert showing the caution icon badged with an application icon  
![](images/_page_204_Figure_7.jpeg)  
<span id="page-204-1"></span>**Carbon:** See *Dialog Manager Reference* in Carbon User Experience Documentation.  
**Cocoa:** See *Dialogs and Special Panels* in Cocoa User Experience Documentation.  
#### <span id="page-204-5"></span>**Writing Good Alert Messages**  
A good alert message states clearly what caused the alert to appear and what the user can do about it. Express everything in the user's vocabulary. Figure 13-31 shows an example of an alert message that provides little useful information.  
<span id="page-205-0"></span>**Figure 13-31** A poorly written alert message  
![](images/_page_205_Picture_3.jpeg)  
<span id="page-205-1"></span>You could improve this message by describing the problem in the user's vocabulary as shown in Figure 13-32.  
**Figure 13-32** An improved alert message  
![](images/_page_205_Picture_6.jpeg)  
<span id="page-205-2"></span>To make the alert really useful, provide a suggestion about what the user can do about the current situation. Even if the alert serves as a notification to the user and no further action is required, provide as much information as needed to describe the situation. Figure 13-33 shows the alert with additional information.  
**Figure 13-33** A well-written alert message  
![](images/_page_205_Picture_9.jpeg)  
**Note:** The examples in these figures would probably be sheets in a real application.