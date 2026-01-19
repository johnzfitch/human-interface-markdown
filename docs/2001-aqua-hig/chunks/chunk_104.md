<!-- Chunk 104 | Source: 2001 Aqua Human Interface Guidelines.pdf | Est. Tokens: 627 -->
Alerts display messages to inform users of situations that are notable or potentially dangerous.  
<span id="page-95-0"></span>**Figure 6-2** A standard alert  
![](images/_page_95_Picture_3.jpeg)  
An alert should contain only the following elements:  
- *Alert message text.* This text, in emphasized (bold) system font, provides a short, simple summary of the error or condition that summoned the alert. Often the message is presented as a question.
- *Informative text.* This text appears in the small system font and provides a fuller description of the situation, its consequences, and how to get out of it. For example, a warning that an action cannot be undone is an appropriate use of informative text.
- <span id="page-95-2"></span>■ *Buttons* for addressing the alert. Button names should correspond to the action the user performs when pressing the button—for example, Erase, Save, or Delete.
- *The application icon.* Because of the new window layering model (described in ["What's New in Aqua" \(page 23\),](#page-22-0) an icon is necessary to make it clear to the user which application is displaying the alert.  
<span id="page-95-1"></span>In rare cases, you may want to display a caution icon in your alert, badged with the application icon as shown in Figure 6-3 (page 97). A badged alert is appropriate only if the user is performing a task, such as installing software, and a possible side effect of that task would be the inadvertent destruction of data.  
<span id="page-96-1"></span>Don't use a caution icon for tasks whose only purpose is to overwrite or remove data, such as Save or Empty Trash; too-frequent use of the caution icon dilutes its significance.  
#### **Important**  
Mac OS X dialogs should not use the different icons for "note," "caution," and "stop" alerts, as was done in Mac OS 9. Most alerts should simply show the application icon.  
<span id="page-96-0"></span>**Figure 6-3** A customized alert showing the caution icon badged with an application icon  
![](images/_page_96_Picture_6.jpeg)  
To produce the application icon, Carbon developers should use a standard alert with either the note or stop parameter, and Cocoa developers should use NSBeginAlertSheet. To produce the rare caution icon, Carbon developers should use the caution parameter and Cocoa developers should use NSBeginCriticalAlertSheet.  
For more information, see ["Layout Guidelines" \(page 143\)](#page-142-0) and ["Writing Good Alert](#page-231-1)  [Messages" \(page 232\)](#page-231-1).