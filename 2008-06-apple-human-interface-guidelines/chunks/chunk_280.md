<!-- Chunk 280 | Source: 2008-06 Apple Human Interface Guidelines.pdf | Est. Tokens: 1044 -->
Alerts display messages to inform users of situations that are notable or potentially dangerous. Alerts are modal dialogs. For an alert that applies to one document or in single-window applications, display the alert as a sheet. See "When to Use [Sheets"](#page-231-1) (page 232) for guidelines.  
Figure 14-47 shows the elements of an alert.  
<span id="page-232-0"></span>**Figure 14-47** A standard alert  
![](images/_page_232_Picture_3.jpeg)  
<span id="page-232-1"></span>See "A [Standard](#page-342-0) Alert" (page 343) for more information on laying out alerts.  
#### <span id="page-232-3"></span><span id="page-232-2"></span>**The Elements of an Alert**  
An alert should contain only the following elements:  
- <span id="page-232-7"></span>■ **Alert message text**. This text, in emphasized (bold) system font, provides a short, simple summary of the error or condition thatsummoned the alert. Thisshould be a complete sentence; often it is presented as a question. See "Writing Good Alert [Messages"](#page-233-3) (page 234) for more information.
- **Informative text**. This text appears in the small system font and provides a fuller description of the situation, its consequences, and ways to get out of it. For example, a warning that an action cannot be undone is an appropriate use of informative text.  
<span id="page-232-5"></span>**Important:** Do not leave out the informative text. What you think of as an intuitive alert message might be far from intuitive to your users. Use informative text to reword and expand on the alert message text.  
- <span id="page-232-4"></span>■ **Buttons for addressing the alert**. Button names should correspond to the action the user performs when pressing the button—for example, Erase, Save, or Delete. The rightmost button in the dialog, the action button, is the button that confirms the alert message text. The action button is usually, but not always, the default button. (Note that in Cocoa methods, the rightmost button is always referred to as the default button even though it might not be.) For more information, see ["Dismissing](#page-235-1) Dialogs" (page 236).
- **The application icon**. Because of the Mac OS X window layering model (described in ["Window](#page-216-0) [Layering"](#page-216-0) (page 217)), an icon is necessary to make it clear to the user which application is displaying the alert.  
<span id="page-232-6"></span>In rare cases, you may want to display a caution icon in your alert, badged with the application icon as shown in Figure 14-48. A badged alert is appropriate only if the user is performing a task,such asinstalling software, and a possible side effect of that task would be the inadvertent destruction of data. Don't use a caution icon for tasks whose only purpose is to overwrite or remove data, such as Save or Empty Trash; too-frequent use of the caution icon dilutes its significance.  
<span id="page-233-0"></span>**Figure 14-48** A customized alert showing the caution icon badged with an application icon  
![](images/_page_233_Picture_3.jpeg)  
#### <span id="page-233-4"></span><span id="page-233-3"></span>**Writing Good Alert Messages**  
<span id="page-233-1"></span>A good alert message states clearly what caused the alert to appear and what the user can do about it. Express everything in the user's vocabulary. Figure 14-49 shows an example of an alert message that provides little useful information.  
**Figure 14-49** A poorly written alert message  
![](images/_page_233_Picture_7.jpeg)  
<span id="page-233-2"></span>You could improve this message by describing the problem in the user's vocabulary asshown in Figure 14-50.  
**Figure 14-50** An improved alert message  
![](images/_page_233_Picture_10.jpeg)  
To make the alert really useful, provide a suggestion about what the user can do about the current situation. Even if the alert serves as a notification to the user and no further action is required, provide as much information as needed to describe the situation. Figure 14-51 shows the alert with additional information.  
<span id="page-234-1"></span>**Figure 14-51** A well-written alert message  
![](images/_page_234_Picture_3.jpeg)