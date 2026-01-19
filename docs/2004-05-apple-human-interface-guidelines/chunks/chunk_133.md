<!-- Chunk 133 | Source: 2004-05 Apple Human Interface Guidelines.pdf | Est. Tokens: 1105 -->
<span id="page-135-7"></span>Alerts display messages to inform users of situations that are notable or potentially dangerous. Alerts are modal dialogs. For an alert that applies to one document or in single-window applications, display the alert as a sheet. See ["When to Use Sheets"](#page-134-0) (page 135) for guidelines.  
<span id="page-135-1"></span>Figure 9-2 shows the elements of an alert.  
<span id="page-135-2"></span>**Figure 9-2** A standard alert  
![](images/_page_135_Picture_6.jpeg)  
<span id="page-135-4"></span><span id="page-135-3"></span>See ["A Standard Alert"](#page-210-0) (page 211) for more information on laying out alerts.  
#### <span id="page-135-5"></span>The Elements of an Alert  
An alert should contain only the following elements:  
- <span id="page-135-8"></span>■ **Alert message text.** This text, in emphasized (bold) system font, provides a short, simple summary of the error or condition that summoned the alert. This should be a complete sentence; often it is presented as a question. See ["Writing Good Alert Messages"](#page-136-1) (page 137) for more information.
- **Informative text.** This text appears in the small system font and provides a fuller description of the situation, its consequences, and ways to get out of it. For example, a warning that an action cannot be undone is an appropriate use of informative text.  
#### **Important**  
<span id="page-135-6"></span>Do not leave informative text out. What you think of as an intuitive alert message might be far from intuitive to your users. Use informative text to reword and expand on the alert message text.  
■ **Buttons for addressing the alert.** Button names should correspond to the action the user performs when pressing the button—for example, Erase, Save, or Delete. The rightmost button in the dialog, the action button, is the button that confirms the alert message text. The action button is usually, but not always, the default button. Note that in Cocoa methods, the rightmost  
button is always referred to as the default button even though it might not be. For more information, see ["Dismissing Dialogs"](#page-139-0) (page 140).  
<span id="page-136-3"></span>■ **The application icon.** Because of the Mac OS X window layering model (described in ["Window Layering"](#page-119-1) (page 120)), an icon is necessary to make it clear to the user which application is displaying the alert.  
<span id="page-136-4"></span>In rare cases, you may want to display a caution icon in your alert, badged with the application icon as shown in Figure 9-3. A badged alert is appropriate only if the user is performing a task, such as installing software, and a possible side effect of that task would be the inadvertent destruction of data. Don't use a caution icon for tasks whose only purpose is to overwrite or remove data, such as Save or Empty Trash; too-frequent use of the caution icon dilutes its significance.  
#### **Important**  
<span id="page-136-0"></span>The note, caution, and stop alerts used in Mac OS 9 should not be used in Mac OS X.  
**Figure 9-3** A customized alert showing the caution icon badged with an application icon  
![](images/_page_136_Figure_8.jpeg)  
<span id="page-136-1"></span>**Carbon:** See *Dialog Manager Reference* in Carbon User Experience Documentation.  
**Cocoa:** See *Dialogs and Special Panels* in Cocoa User Experience Documentation.  
#### <span id="page-136-2"></span>Writing Good Alert Messages  
A good alert message states clearly what caused the alert to appear and what the user can do about it. Express everything in the user's vocabulary. Figure 9-4 shows an example of an alert message that provides little useful information.  
<span id="page-137-0"></span>**Figure 9-4** A poorly written alert message  
![](images/_page_137_Picture_3.jpeg)  
<span id="page-137-1"></span>You could improve this message by describing the problem in the user's vocabulary as shown in Figure 9-5.  
**Figure 9-5** An improved alert message  
![](images/_page_137_Picture_6.jpeg)  
<span id="page-137-2"></span>To make the alert really useful, provide a suggestion about what the user can do to get out of the current situation. Figure 9-6 shows the alert with additional information.  
**Figure 9-6** A well-written alert message  
![](images/_page_137_Picture_9.jpeg)  
**Note:** The examples in these figures would probably be sheets in a real application.