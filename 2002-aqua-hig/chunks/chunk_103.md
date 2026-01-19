<!-- Chunk 103 | Source: 2002 Aqua Human Interface Guidelines.pdf | Est. Tokens: 657 -->
Alerts display messages to inform users of situations that are notable or potentially dangerous.  
<span id="page-98-0"></span>**Figure 6-2** A standard alert  
![](images/_page_98_Picture_3.jpeg)  
An alert should contain only the following elements:  
- *Alert message text.* This text, in emphasized (bold) system font, provides a short, simple summary of the error or condition that summoned the alert. Often the message is presented as a question.
- *Informative text.* This text appears in the small system font and provides a fuller description of the situation, its consequences, and how to get out of it. For example, a warning that an action cannot be undone is an appropriate use of informative text.
- <span id="page-98-2"></span>■ *Buttons* for addressing the alert. Button names should correspond to the action the user performs when pressing the button—for example, Erase, Save, or Delete. For more information, see ["Push Buttons" \(page 120\)](#page-119-1).
- *The application icon.* Because of the Mac OS X window layering model (described in ["Window Layering" \(page 70\)](#page-69-0)), an icon is necessary to make it clear to the user which application is displaying the alert.  
<span id="page-98-1"></span>In rare cases, you may want to display a caution icon in your alert, badged with the application icon as shown in Figure 6-3. A badged alert is appropriate only if the user is performing a task, such as installing software, and a possible side effect of that task would be the inadvertent destruction of data. Don't use a  
<span id="page-99-1"></span>caution icon for tasks whose only purpose is to overwrite or remove data, such as Save or Empty Trash; too-frequent use of the caution icon dilutes its significance.  
#### **Important**  
Mac OS X dialogs should not use the different icons for "note," "caution," and "stop" alerts, as was done in Mac OS 9. Most alerts should simply show the application icon.  
<span id="page-99-0"></span>**Figure 6-3** A customized alert showing the caution icon badged with an application icon  
![](images/_page_99_Picture_6.jpeg)  
To display an alert with the application icon, Carbon developers should use a standard alert, and Cocoa developers should use the alert and sheet functions in NSPanel.h. To produce the caution icon, Carbon developers should use the kAlertCautionAlert with the StandardAlert function; Cocoa developers should use the NSBeginCriticalAlertSheet function.  
Also see ["Layout Guidelines" \(page 149\)](#page-148-0), especially [Figure 8-5 \(page 155\)](#page-154-0), and ["Writing Good Alert Messages" \(page 232\).](#page-231-1)