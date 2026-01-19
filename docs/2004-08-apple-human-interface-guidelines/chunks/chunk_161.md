<!-- Chunk 161 | Source: 2004-08 Apple Human Interface Guidelines.pdf | Est. Tokens: 674 -->
An alert should contain only the following elements:  
- <span id="page-135-8"></span>■ **Alert message text.** This text, in emphasized (bold) system font, provides a short, simple summary of the error or condition that summoned the alert. This should be a complete sentence; often it is presented as a question. See ["Writing Good Alert Messages"](#page-136-1) (page 137) for more information.
- **Informative text.**This text appears in the small system font and provides a fuller description of the situation, its consequences, and ways to get out of it. For example, a warning that an action cannot be undone is an appropriate use of informative text.  
#### <span id="page-135-6"></span>**Important**  
Do not leave informative text out. What you think of as an intuitive alert message might be far from intuitive to your users. Use informative text to reword and expand on the alert message text.  
■ **Buttons for addressing the alert.** Button names should correspond to the action the user performs when pressing the button—for example, Erase, Save, or Delete. The rightmost button in the dialog, the action button, is the button that confirms the alert message text. The action button is usually, but not always, the default button. Note that in Cocoa methods, the rightmost button is always referred to as the default button even though it might not be. For more information, see ["Dismissing Dialogs"](#page-139-0) (page 140).  
<span id="page-136-3"></span>■ **The application icon.**Because of the Mac OS X window layering model (described in ["Window](#page-119-1) [Layering"](#page-119-1) (page 120)), an icon is necessary to make it clear to the user which application is displaying the alert.  
<span id="page-136-4"></span>In rare cases, you may want to display a caution icon in your alert, badged with the application icon as shown in Figure 9-3. A badged alert is appropriate only if the user is performing a task, such as installing software, and a possible side effect of that task would be the inadvertent destruction of data. Don't use a caution icon for tasks whose only purpose is to overwrite or remove data, such as Save or Empty Trash; too-frequent use of the caution icon dilutes its significance.  
#### **Important**  
<span id="page-136-0"></span>The note, caution, and stop alerts used in Mac OS 9 should not be used in Mac OS X.  
**Figure 9-3** A customized alert showing the caution icon badged with an application icon  
![](images/_page_136_Figure_7.jpeg)  
<span id="page-136-1"></span>**Carbon:** See *Dialog Manager Reference* in Carbon User Experience Documentation.  
**Cocoa:** See *Dialogs and Special Panels* in Cocoa User Experience Documentation.