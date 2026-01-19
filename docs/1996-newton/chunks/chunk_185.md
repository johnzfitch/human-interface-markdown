<!-- Chunk 185 | Source: 1996 Newton 2.0 User Interface Guidelines.pdf | Est. Tokens: 1797 -->
If you want users to be able to file data in your application, it must include a Filing button, which is a picture button that looks like a an ordinary file folder. Tapping a Filing button displays a Filing slip, which enumerates the available filing options. Figure 8-13 shows a sample Filing button and Filing slip.  
**Figure 8-13** A Filing slip names available folders and storage locations  
![](images/_page_255_Picture_7.jpeg)  
<span id="page-256-0"></span>The filing options that a user selects in a Filing slip apply to the data in the view that contains the Filing button. If the view contains multiple data items that can be individually selected, such as the items listed in an overview, then the filing options selected by the user apply to the currently selected items.  
If there is nothing to file when a user taps a Filing button—for example, the user taps the Filing button in an overview without first selecting any items the Filing service displays the message "There is nothing to file."  
#### A Filing Button's Location 8  
Where you put a Filing button in your application's views depends on how much data the Filing button affects. If a Filing button affects all the data in a view, then it should go at the bottom right corner of the view, next to the view's Action button. For example, the main view of the Names File application has one Filing button, and it affects all data in the view. Figure 8-14 shows examples of views with one Filing button each.  
**Figure 8-14** A Filing button at the bottom of a view affects the entire view  
![](images/_page_256_Picture_7.jpeg)  
Filing **8-15**  
<span id="page-257-0"></span>In a view where a Filing button can affect only one data item of several that may be displayed in the view (perhaps by scrolling the view), there should be a Filing button above each item, at the right side of the view. Generally such a view has a separator bar above each data item, and a Filing button should be at the right end of each separator bar. For example, each note in the Notepad application has its own Filing button, which applies just to that note. Figure 8-15 shows an example of Filing buttons above each data item in a view.  
**Figure 8-15** A Filing button above an item affects only that item  
![](images/_page_257_Figure_4.jpeg)  
#### A Filing Slip's Contents 8  
A Filing slip contains one or two clusters of radio buttons, one for selecting a storage location and one for selecting a folder. An application can suppress either cluster. For example, the built-in Date Book application suppresses the cluster for selecting a folder. Furthermore, the system suppresses the cluster for selecting a storage location if the Newton has only one storage location. However, the Filing slip always contains at least one cluster of radio buttons. If your application suppresses the folders cluster, the system does not suppress the storage-locations cluster even if there is only one storage location available. [Figure 8-16](#page-258-0) illustrates several configurations of the Filing slip.  
<span id="page-258-0"></span>**Figure 8-16** A Filing slip can include storage locations, folders, or both  
![](images/_page_258_Picture_3.jpeg)  
A Filing slip should open with the current folder and storage location selected. Your application can override this behavior if it cannot determine a useful initial filing state, such as when a user has selected multiple items for filing from an overview.  
A Filing slip includes folders that are visible only in the current application as well as folders that are visible everywhere. All the folders are listed together, in alphabetical order. If necessary, you can have your application suppress the display of either type of folder. For example, the built-in Extras Drawer application only displays folders specific to it. Note that this option to suppress folders should not be a user preference, but should be decided when the application is designed.  
Applications provide the headings for the radio button clusters in a Filing slip. The wording your application should use for headings depends on the how many items a user is filing and on whether the Filing slip includes both folders and storage locations or just one of them. [Table 8-1](#page-259-0) specifies the wording to use in each case.  
Filing **8-17**  
<span id="page-259-0"></span>**Table 8-1** Headings for radio button clusters in Filing slips  
| Heading for<br>storage locations | Heading for folders        | Number of<br>items being filed |
|----------------------------------|----------------------------|--------------------------------|
| File this Item on                | —                          | one                            |
| File this Item on                | And file in                | one                            |
| File the selected Items on       | —                          | multiple                       |
| File the selected Items on       | And file in                | multiple                       |
| —                                | File this Item in          | one                            |
| —                                | File the selected Items in | multiple                       |  
NOTE In these headings the word Item is capitalized and may be replaced with the specific type of item being filed, such as Note, Name, Date, Task, Call, and so on. None of these headings ends with a colon or has any other punctuation.  
In addition to radio buttons for selecting filing options, all Filing slips have a File button for initiating the filing operation and a large Close box for canceling the filing operation.  
#### Editing Folders 8  
If a Filing slip contains radio buttons for selecting a folder, the slip also includes New and Edit Folder buttons for creating new folders and editing the names of existing ones. Tapping either button displays a slip for entering and editing a folder name. [Figure 8-17](#page-260-0) shows examples of the slips used for entering and editing folder names.  
In a slip for creating a new folder, the slip includes a checkbox for designating where the folder can be seen—in all applications (everywhere) or just in the application where the folder was created. In a slip for editing an existing folder, the checkbox is replaced by a message stating where the folder name is shown. The same message appears instead of a checkbox when creating a new folder in an application that suppresses the display of folders specific to it or the display of folders visible everywhere (as described earlier in ["A](#page-257-0)  [Filing Slip's Contents" on page 8-16\)](#page-257-0).  
<span id="page-260-0"></span>**Figure 8-17** Slips for entering and editing folder names  
![](images/_page_260_Picture_3.jpeg)  
Folder Creation slip has a checkbox for designating where the folder can be seen  
![](images/_page_260_Picture_5.jpeg)  
Folder Editing slip reports where the folder can be seen  
Users can create up to 12 folders visible everywhere and 12 more folders specific to each application. The system does not permit an application-specific folder to have the same name as a folder that is visible everywhere.