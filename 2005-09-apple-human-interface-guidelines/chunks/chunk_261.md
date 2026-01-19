<!-- Chunk 261 | Source: 2005-09 Apple Human Interface Guidelines.pdf | Est. Tokens: 870 -->
Users can interrupt a quit operation with documents still unsaved. For example, if a user chooses Quit and a save alert (a sheet) opens for a document, the user can work on other documents or switch to another application without addressing the save alert.  
When a user quits an application in which all open documents have been saved, all documents close immediately and the application quits.  
#### **Quitting an Application That Is Not Document-Based**  
When a user attempts to quit an application that is not document-based but that has many windows whose contents are saved simultaneously, present an application-modal Save Changes alert, such as the one shown in Figure 13-42.  
<span id="page-214-0"></span>**Figure 13-42** A Save Changes alert for an application that is not document-based  
![](images/_page_214_Picture_3.jpeg)  
#### **Quitting an Application With Multiple Unsaved Documents Open**  
<span id="page-214-1"></span>When a user attempts to quit a document-based application and there is more than one document with unsaved changes open, present an application-modal Review Changes alert such as the one shown in Figure 13-43.  
<span id="page-214-2"></span>**Figure 13-43** The Review Changes (application modal) alert that appears when the user quits with more than one unsaved document open  
![](images/_page_214_Picture_7.jpeg)  
<span id="page-214-4"></span>The appropriate action for each button is as follows:  
- **Discard Changes.** Closes all documents without saving changes and quits the application.
- **Cancel.** Cancels the Quit command.
- **Review Changes.** All open documents (including those minimized in the Dock) come forward, with the unsaved documents on top. The active document presents the Save Before Quittingalert. If the user clicks Save, the Save dialog appears (if the document has not previously been saved). If the user clicks Don't Save, the next unsaved document comes forward with its Save Before Quitting alert. If the user dismisses the last Save Before Quitting alert with Save or Don't Save, all documents close and the application quits.  
<span id="page-214-3"></span>During the review, if the user activates another unsaved document, it should come forward with its Save Before Quittingsheet open. Save Before Quittingsheets on other documents remain open. During the review, if the user activates a saved document, the review process continues when the next unsaved document becomes active.  
If, in the midst of a quit operation, the user clicks the application icon in the Dock or chooses Bring All to Front from the Window menu, documents should appear in this order: documents with open sheets on top, unsaved documents next, and then saved documents.  
<span id="page-215-3"></span>At any time during the review process, the user can click Cancel to stop the quit operation. If the user initiates a Quit command during the review process, the process begins again with the application-modal alert shown in Figure 13-43.  
#### **Saving a Document With the Same Name as an Existing Document**  
<span id="page-215-4"></span><span id="page-215-1"></span>If the user types the name of a document that already exists in the same location into the Save As field of a Save dialog, and then clicks Save, present an application-modal alert in which the user can confirm whether or not to replace the previous document.  
**Figure 13-44** Alert for confirming replacing a file  
![](images/_page_215_Picture_6.jpeg)