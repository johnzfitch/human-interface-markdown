<!-- Chunk 70 | Source: 1987 Apple Human Interface Guidelines - The Apple Desktop Interface.pdf | Est. Tokens: 2159 -->
Desk accessories are mini-applications that are always available, via the Apple menu, while the Finder or any other application is in use. The list of installed desk accessories is usually alphabetized (Figure 3-26).  
![](images/_page_87_Picture_4.jpeg)  
Figure 3-26 The Apple menu  
Only those desk accessories installed in the current System file can appear in the Apple menu. There are some desk accessories that are linked to <sup>a</sup> particular application—for example, spelling checkers that appear in the Apple menu only when <sup>a</sup> word processing application is active. The list of desk accessories is expanded or reduced according to what's available. There can be more than one accessory on the desktop at one time, as shown in Figure 3-27.  
![](images/_page_88_Picture_0.jpeg)  
Figure 3-27 Some desk accessories  
The Apple menu also contains the About... menu item. Choosing this item brings up a dialog box with the name, version number, and copyright information for the current application, as well as any other information the application developer wants to display. The Help item is also commonly in the Apple menu. In some applications, the Help and About... functions are combined in one menu item.  
#### The File menu  
The File menu lets the user perform certain simple filing operations without leaving the application and returning to the Finder (Figure 3-28). It also contains Print and Quit. All of these operations are described below.  
![](images/_page_88_Picture_5.jpeg)  
Figure 3-28 Standard File menu  
#### New  
Opens a new, untitled document for the current application. The user names the document the first time it's saved. New is disabled when the maximum number of documents allowed by the application is already open.  
#### Open  
Opens an existing document. A dialog box lets the user select *which* document. This dialog box shows a list of all the documents on the disk whose name is displayed that can be handled by the current application (Figure 3-29 and Figure 3-30). Which dialog box appears depends on the file system on the disk. With the Macintosh File System (MFS), used on 400K disks, all the documents are displayed together in one list; folders are ignored.  
![](images/_page_89_Picture_4.jpeg)  
Figure 3-29 MFS Open dialog box  
With the Hierarchical File System (HFS) on the Macintosh, the user, when opening a document, can browse through all levels of folders, forward and backward. The Eject and Drive buttons allow the user to look at documents on another disk or to eject a disk. When no disk is available to look at or to eject, these buttons are dimmed.  
![](images/_page_89_Picture_7.jpeg)  
Figure 3-30 HFS Open dialog box  
Using Open from an application, the user can open only <sup>a</sup> document that can be processed by that application. To open a document that can be processed only by some other application, the user must ordinarily leave the application and return to the Finder. Using Open from the Finder, the user can open any document—the appropriate application is automatically opened as well.  
When an application starts up by putting an empty untitled document on the screen, the Open option can remain enabled (not dimmed) even ifthe application allows only one open document at <sup>a</sup> time. In this case, choosing Open from the File menu simultaneously closes the empty document (why save an empty document?) and opens another.  
#### Close  
Closes the active window, which may be <sup>a</sup> document window, <sup>a</sup> desk accessory, or any other type of window. Clicking in a window's close box isthe same as choosing Close.  
When the user chooses Close, and the active document has been changed since the last save, the Close dialog box appears, asking "Save changes before closing?" A great deal of work can be lost if <sup>a</sup> user mistakenly clicks No instead of Yes. To avoid confusion, all applications should use the same standard Close dialog box (Figure 3-31). This is especially important to users who often move from one application to another and become less aware of subtle differences between applications.  
![](images/_page_90_Picture_5.jpeg)  
Figure 3-31 Standard Close dialog box  
Yes and No, the two direct responses to the question, are placed together on the left side of the box. Yes is the default button. Cancel, which cancels Close, is to the right, separate from Yes and No.  
The text of the question is generally "Save changes before closing?" but if the user sees this message after choosing Quit, the text would instead be "Save changes before quitting?" If the application supports multiple windows, the text is "Save changes to [document name] before closing?" Regardless of the text of the question, the box should always look the same and appear in the same place on the screen.  
#### Save  
Lets the user save the active document to a disk, including any changes made to that document since the last time it was saved. The document remains open. Users appreciate seeing, at this point, a message telling them the document is indeed being saved.  
If the user chooses Save for a new untitled document (one the user hasn't named yet), the application presents the Save As dialog box (described next). This dialog box allows the user to name the document and choose where it will be saved before the application continues with the save. The active document remains active.  
If there's not enough room on the disk to save the document, the application says so. The application then suggests that the user can choose Save As instead, to save the document on another disk.  
#### Save As  
Saves a copy of the active document under a new name provided by the user. When the user opens a document, makes changes to it, and then chooses Save As, the changes are not made to the original document. The changed version of the document is saved under the new name. The active document is no longer the one the user opened, but rather the new one with the new name.  
If no changes had been made to the original document when Save As was chosen, then there are two identical documents having different names.  
In applications that support stationery, the Save As dialog box includes a Stationery option. A document that is saved as stationery becomes a template containing whatever information was in the original document. Figure 3-32 shows a Save As dialog box with a Stationery option.  
![](images/_page_91_Figure_8.jpeg)  
Figure 3-32 A Save As dialog box  
If stationery called "Memo" is opened, a document with the default name "Memo #1" is opened (then "Memo #2" and so on). When this document is saved, the Save As dialog box appears again, so that the user can rename the document if desired.  
#### Revert to Saved  
Discards all changes made to the active document since the last time it was saved or opened. The document on disk is reopened. Before all this happens, a dialog box lets the user confirm that this is what he or she really wants. (This follows the principles that users should be allowed to make informed decisions and to change their minds.) Figure 3-33 shows a Revert to Saved dialog box.  
![](images/_page_92_Picture_3.jpeg)  
Figure 3-33 A Revert to Saved dialog box  
#### Page Setup  
Lets the user specify printing parameters such as the paper size and printing orientation (different applications will provide different options as needed). These parameters are saved with the document when the document is saved. Figure 3-34 shows a Page Setup dialog box.  
![](images/_page_92_Picture_7.jpeg)  
Figure 3-34 A Page Setup dialog box  
#### Print  
Lets the user specify various parameters, such as print quality and number of copies, and then prints the document. The parameters apply only to the current printing operation and are not saved with the document. Figure 3-35 shows a Print dialog box.  
| Print                                                               |                      |
|---------------------------------------------------------------------|----------------------|
| ®<br>fill O<br>Q <br>Pages:<br>From:<br>Copies:<br>fu:              | Cancel^<br>[<br>Help |
| ®<br>No O<br>O<br>Page<br>first Page<br>Couer<br>Page:<br>Last      | SI<br>[<br>]         |
| O<br>Manual<br>Feed<br>Paper<br>Paper<br>Cassette<br>Source:<br>(5) |                      |  
Figure 3-35 A Print dialog box  
#### Quit  
Lets the user leave the application and return to the Finder. If any open documents have been changed since the last time they were saved, the application presents the "Save changes?" dialog box, once for each open document.