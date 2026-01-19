<!-- Chunk 6 | Source: 2000 Adopting the Aqua Interface.pdf | Est. Tokens: 271 -->
Do not use sheets for dialogs that apply to several windows. For example, the Save Changes alert that your application displays when the user attempts to quit with unsaved work should be a standard movable modal dialog (as shown in [Figure 1-2](#page-5-0)), because it may pertain to several open windows. Sheets are strictly intended to be used in situations when a particular dialog is associated only with the window to which it is attached.  
<span id="page-5-0"></span>**Figure 1-2** Example of a modal alert used in preference to a sheet  
![](images/_page_5_Picture_10.jpeg)  
#### **CHAPTER 1**  
#### Adopting the Aqua Interface  
Sheets are not appropriate for modeless operations where the dialog should be left open to allow the user to observe the effects of changes applied. Such tasks are better suited to separate modeless dialogs or palettes.  
Sheets should not be used in place of a preference dialog. Most applications use multiple panes to display preferences to the user. Application preferences should be presented in a consistent manner across all applications.