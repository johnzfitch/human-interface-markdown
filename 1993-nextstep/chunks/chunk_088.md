<!-- Chunk 88 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 242 -->
If a window displays a document that can be saved, the title bar of the window should display the name of the document, followed by an em dash and the path of the folder where the document is located. The em dash is set off by two spaces on each side. For example:  
jobRecords — /Net/machine/home/records  
The title bar is not usually a good place to show status, such as what the application is currently doing. It's usually clearer to display this status in the window or in a panel. Status within a window is often displayed in small, dark gray text (as in the Workspace Manager File Viewer).  
#### **Programming Note: Implementing Titles of Document Windows**  
You should use the **setTitleAsFilename**: method of the Window class to set the title of a document window. For example, to produce the window title  
jobRecords — /Net/machine/home/records  
you should send a **setTitleAsFilename**: message with the argument "/Net/machine/home/records/jobRecords".