<!-- Chunk 112 | Source: 1992 Macintosh Human Interface Guidelines.pdf | Est. Tokens: 1551 -->
![](images/_page_151_Picture_3.jpeg)  
Apple reserves several standard keyboard equivalents for standard commands. Table 4-1 and Table 4-2 show the standard Macintosh keyboard equivalents.  
**Table 4-1** Apple-reserved keyboard equivalents for all systems  
| Menu | Keys     | Command                |
|------|----------|------------------------|
| File | x-N      | New                    |
| File | x-O      | Open…                  |
| File | x-W      | Close                  |
| File | x-S      | Save                   |
| File | x-P      | Print…                 |
| File | x-Q      | Quit                   |
| Edit | x-Z      | Undo                   |
| Edit | x-X      | Cut                    |
| Edit | x-C      | Copy                   |
| Edit | x-V      | Paste                  |
| Edit | x-A      | Select All             |
| Edit | x-period | Terminate an operation |  
Table 4-2 shows several keyboard equivalents that are reserved for use with localized versions of system software, localized keyboards, keyboard layouts, and input methods. These keyboard equivalents don't correspond directly to menu commands, so there is no menu column with command names in Table 4-2.  
**Table 4-2** Additional reserved keyboard equivalents for worldwide systems  
| Keys                     | Action                                                            |
|--------------------------|-------------------------------------------------------------------|
| x–Space bar              | Rotate through enabled script systems                             |
| x–Option–Space bar       | Rotate through keyboard layouts and input methods within a script |
| x–modifier key–Space bar | Apple reserved                                                    |
| x–Right Arrow            | Changes keyboard layout to current layout of Roman script         |
| x–Left Arrow             | Changes keyboard layout to current layout of system script        |  
See the section on keyboard equivalents in the book *Inside Macintosh: Overview* for a discussion of handling keyboard equivalents in other script systems.  
The key combinations in Table 4-1 and Table 4-2 are reserved across all applications. Even if your application doesn't support one of the menu commands in Table 4-1, it shouldn't use these keyboard equivalents for another function.  
Some applications use other common keyboard equivalents, as shown in Table 4-3. These keyboard equivalents are secondary to the standard keyboard equivalents listed in Table 4-1 and Table 4-2. If your product doesn't support one of these functions, then use these equivalents as you wish.  
**Table 4-3** Common keyboard equivalents that are not reserved  
| Menu  | Keys | Command    |
|-------|------|------------|
| File  | x-F  | Find       |
| File  | x-G  | Find Again |
| Style | x-T  | Plain Text |
| Style | x-B  | Bold       |
| Style | x-I  | Italic     |
| Style | x-U  | Underline  |  
Don't assign keyboard equivalents for infrequently used menu commands. Add keyboard equivalents only for the commands your users employ most frequently.  
#### **CHAPTER 4**  
Menus  
![](images/_page_154_Picture_2.jpeg)  
This chapter describes document windows, which contain user data, and utility windows, which "float" above other windows and can provide tools or other controls that users can work with while document windows are open. The chapter presents specifications and recommendations about the appearance and behavior of these windows, including how the window frame should look, how the user interacts with windows, how you should display them on the screen, and how they interact with each other. This chapter includes some information about dialog boxes, but you can find more extensive information about dialog and alert boxes, both of which are also windows, in Chapter 6, "Dialog Boxes," which begins on page 175.  
![](images/_page_155_Picture_3.jpeg)  
Windows provide a way for people to view and interact with their data. Windows have standard appearances that create a sense of perceived stability for people because they have a standard way to view and interact with all the different kinds of data they can create and store on Macintosh computers.  
A window is a view into the document—if the document is larger than the window, the window is a view of a portion of the document. The application puts one or more windows on the screen, each window showing a view of a document or of auxiliary information used in processing the document.  
Generally there is only one window per document. Multiple windows for the same document can confuse the relationship of windows to icons. The user may wonder, "which window do I close to close the document?" You can provide multiple views to a document by implementing the capability to split windows or by adding utility windows. (See the section "Splitting a Window" on page 170 and the section "Utility Windows" on page 137 for more information.)  
Figure 5-1 shows examples of the standard window types, including dialog boxes.  
**Figure 5-1** Examples of standard windows  
![](images/_page_156_Picture_3.jpeg)  
![](images/_page_156_Picture_4.jpeg)  
![](images/_page_156_Picture_5.jpeg)  
![](images/_page_156_Picture_7.jpeg)  
![](images/_page_156_Picture_9.jpeg)  
There are conventions for opening, closing, moving, sizing, scrolling, and zooming windows. This means that no matter which application people use, they know how to control windows on the screen and how to adjust windows in the desktop workspace for particular tasks or for their work styles.  
![](images/_page_156_Picture_12.jpeg)  
When people manipulate windows on the screen, they see immediate visual feedback. When people move windows, the graphic display keeps up with their movements using a dotted outline to represent the window as it moves on the screen, reinforcing their sense of direct manipulation. When people open and close windows, they see an illusion of such actions. All of these mechanisms emphasize that the user is in control and can directly manipulate "real" interface objects such as windows. See *Inside Macintosh: Macintosh Toolbox Essentials* for information on implementing windows.