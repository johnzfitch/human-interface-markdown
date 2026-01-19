<!-- Chunk 282 | Source: 2005-12 Apple Human Interface Guidelines.pdf | Est. Tokens: 636 -->
When a user attempts to quit a document-based application and there is more than one document with unsaved changes open, present an application-modal Review Changes alert such as the one shown in Figure 13-43.  
<span id="page-217-1"></span><span id="page-217-0"></span>**Figure 13-43** The Review Changes (application modal) alert that appears when the user quits with more than one unsaved document open  
![](images/_page_217_Picture_3.jpeg)  
The appropriate action for each button is as follows:  
- <span id="page-217-3"></span>■ **Discard Changes.** Closes all documents without saving changes and quits the application.
- **Cancel.** Cancels the Quit command.
- **Review Changes.** All open documents (including those minimized in the Dock) come forward, with the unsaved documents on top. The active document presents the Save Before Quitting alert. If the user clicks Save, the Save dialog appears (if the document has not previously been saved). If the user clicks Don't Save, the next unsaved document comes forward with its Save Before Quitting alert. If the user dismisses the last Save Before Quitting alert with Save or Don't Save, all documents close and the application quits.  
During the review, if the user activates another unsaved document, it should come forward with its Save Before Quitting sheet open. Save Before Quitting sheets on other documents remain open. During the review, if the user activates a saved document, the review process continues when the next unsaved document becomes active.  
<span id="page-217-2"></span>If, in the midst of a quit operation, the user clicks the application icon in the Dock or chooses Bring All to Front from the Window menu, documents should appear in this order: documents with open sheets on top, unsaved documents next, and then saved documents.  
At any time during the review process, the user can click Cancel to stop the quit operation. If the user initiates a Quit command during the review process, the process begins again with the application-modal alert shown in Figure 13-43.  
#### <span id="page-217-4"></span>**Saving a Document With the Same Name as an Existing Document**  
If the user types the name of a document that already exists in the same location into the Save As field of a Save dialog, and then clicks Save, present an application-modal alert in which the user can confirm whether or not to replace the previous document.  
<span id="page-218-1"></span>**Figure 13-44** Alert for confirming replacing a file  
![](images/_page_218_Picture_3.jpeg)