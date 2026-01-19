<!-- Chunk 114 | Source: 1995 Macintosh Human Interface Guidelines.pdf | Est. Tokens: 643 -->
The **Edit menu** provides commands that allow people to change, or edit, the contents of their documents. It also provides the commands that allow people to share data, within and between applications, via the Clipboard or the Edition Manager. All applications should support the Undo, Cut, Copy, Paste, and Clear commands. These commands provide standard text-editing abilities, which need to be available in modal dialog boxes such as the Save As dialog box, even though your application itself may not handle these features. You can include a Select All command and its keyboard equivalent if it makes sense for your application.  
<span id="page-133-0"></span>Figure 4-72 shows an example of a standard, simple Edit menu.  
**Figure 4-72** A standard Edit menu for an application  
![](images/_page_133_Picture_4.jpeg)  
You can add other commands to this menu if they're essential to your application and involve changing user content. You must add the commands after the standard menu commands without changing their order. Figure 4-73 shows how to incorporate commands into the Edit menu without disrupting the standard order.  
**Figure 4-73** Adding commands to the Edit menu  
![](images/_page_133_Picture_7.jpeg)  
In addition to the standard commands, if your application implements the capabilities of the Edition Manager, include its commands in the Edit menu, separated from the standard commands by a gray line. Figure 4-74 shows a sample Edit menu that includes the required Edition Manager commands.  
<span id="page-134-0"></span>**Figure 4-74** A sample Edit menu with Edition Manager commands  
| Edit         |        |
|--------------|--------|
| Undo         | ₩Z     |
| Cut          | жX     |
| Сору         | жc     |
| Paste        | æυ     |
| Clear        |        |
| Create Publi | isher  |
| Subscribe To | )      |
| Publisher Op | otions |
| Show Clipbo  | ard    |  
If you find that you need all of the available space in the Edit menu for your application's commands, another way to accommodate the Edition Manager commands is by implementing a submenu. Include a Publishing command in the Edit menu as the title of the submenu. Use the standard indicator for a hierarchical menu, as shown in Figure 4-75, which also shows the submenu with the Edition Manager commands. Because hierarchical menus increase the complexity of your application, it's best to use this approach only when you have no other alternative.  
**Figure 4-75** A sample hierarchical Edit menu with Edition Manager commands  
![](images/_page_134_Picture_8.jpeg)