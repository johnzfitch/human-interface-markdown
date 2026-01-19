<!-- Chunk 110 | Source: 1995 Macintosh Human Interface Guidelines.pdf | Est. Tokens: 528 -->
The Save As command saves a copy of the active document under a new name provided by the user. Figure 4-68 shows the Save As command and its dialog box.  
<span id="page-129-0"></span>**Figure 4-68** The Save As command and dialog box  
![](images/_page_129_Picture_5.jpeg)  
The Save As dialog box allows the user to provide a name for the document and to choose where it will be saved. Leave the document open and active.  
When the user opens a document, makes changes to it, and then chooses Save As, don't change the original document. Save the changed version of the document under the new name. The active document is no longer the one the user opened, but rather the new one with the new name.  
If the user uses the Save As command to make a new copy of a document, and made no changes to the original document, create a second document exactly like the first one. The user now has two identical documents with different names.  
<span id="page-130-0"></span>If your application supports stationery, include a Stationery option in the Save As dialog box. A stationery pad is a template of the original document with whatever information it contains. When a user opens a stationery document, open a copy of the template with the name untitled. When the user saves that document, display the Save As dialog box so that the user can name it.  
Don't use the Save a Copy command in your application. People may not understand the distinction between the Save As command and the Save a Copy command.  
![](images/_page_130_Picture_6.jpeg)  
#### Revert 4  
The Revert command discards all changes made to the active document since the last time it was saved or opened. The document that was last saved to the disk is reopened. When the user chooses Revert, display an alert box that warns the user about the potential data loss this operation will cause. Provide a cancel button so that the user has a way to back out of the situation. Figure 4-69 shows a File menu with the Revert command highlighted and an appropriate alert box.  
**Figure 4-69** The Revert command  
![](images/_page_130_Picture_10.jpeg)