<!-- Chunk 30 | Source: 1986-12 Human Interface Guidelines (Final Draft).pdf | Est. Tokens: 2075 -->
There are very standard conventions for opening, closing, moving, sizing, scrolling and zooming windows. No matter what application is being used, users know how to control the appearance of windows on the screen, and how to manage the workspace for particular tasks and to their tastes.  
When the user manipulates windows on the screen, visual feedback is immediate. When users move windows, they have the sense of directly moving them; changes in the graphic display keep up with the user's movements. When users open or close windows they see an illusion of such opening or closing, enhancing the sense of "real world" activity. When a document is scrolled, the scroll box provides direct visual feedback about the position of the current view within the document as a whole.  
All of these mechanisms emphasize user control and the direct manipulation of concrete objects.  
#### Dialogs, alerts, and controls  
Among the other standard elements are window-like dialog boxes and alert boxes—and the specific controls that are used in these boxes. These boxes provide a standard framework in which the computer can present alternatives from which the user can choose.  
The purpose of **dialog boxes** is to elicit responses from the user, typically several at one time. For example, the print dialog box enables the user to specify the number of copies to be printed, the pages to be printed, whether there should be a title page, and so on. A dialog box appears whenever the user chooses a menu item that is followed, in the menu itself, by an ellipsis (...). Standard dialog boxes suspend the system until the user either provides the needed information or cancels the operation.  
All requests made in dialog boxes are phrased in plain language and in a friendly and non-threatening manner.  
When the dialog box is complete, the user dismisses it by "pushing a button" in the dialog box (by clicking the mouse button while the screen pointer is within a button-shaped object within the dialog box). This is not the same way standard windows are closed. Also unlike standard windows, the user can't move or resize modal dialog boxes.  
Alerts notify the user, in plain and polite language, whenever an unusual situation occurs. They can warn of dangerous situations, recommend corrective actions, or provide information that might change the user's plans—but the user is always in charge. There are different levels of alerts, according to the severity of the situation.  
As with dialog boxes, users dismiss alert boxes by pushing a button, but can't move or resize them.  
![](images/_page_33_Picture_7.jpeg)  
Figure 3 Dialog box  
![](images/_page_34_Figure_0.jpeg)  
Figure 4 Alert box  
Standard controls are used within dialog and alert boxes. Their appearance and functions are standardized. They provide users with familiar tools and formats for responding to the computer's need for information. Described in detail in Chapter 3, these controls include buttons, check boxes, radio buttons, and text entry fields.  
#### Menus  
Menus are central to the "noun-verb" principle of the Apple Desktop Interface: the user first selects an object (noun), either on the desktop or in a window, then chooses, from a menu, the operation (verb) to be applied to this object.  
Because menus display the full range of potential activities available, users don't have to remember and type command names. Instead, they simply choose from the alternatives presented. The user's task is recognition, not recall.  
Because they list all available activities, menus let users quickly get an overview (or, for new users, a preview) of what is possible at any given moment.  
Finally, pull-down menus make it possible to keep unnecessary detail out of sight, and out of the way of the main task, while still making those details quickly and easily available. The user "pulls down" a menu only when it's needed—the rest of the time, the menu is "rolled up" into the menu bar at the top of the screen.  
The overall concept of pull-down menus comprises three fundamental screen elements: the menu bar, where the name of each available menu appears; pull-down menus, which appear only when the user wants them to; and the menu items themselves.  
#### The menu bar  
The menu bar serves as a stabilizing element. Even when the screen changes drastically, as when the user changes from one application to another, the **menu bar** is always visible at the top of the screen, adding to the illusion of stability amid a flexible environment.  
The elements of the menu bar—the words and phrases that are the titles of the different menus—are also quite stable. Three of the menus—the Apple menu, the File menu, and the Edit menu—are **standard menus** that appear as the first three menus in almost every any application. Do not make up your own menus and then give them the same names as standard menus.  
In addition to the three standard menus, each application has its own unique menus. Because they appear to the right of the more standard menus, application-specific menus don't interfere with the user's sense of stability.  
![](images/_page_35_Picture_4.jpeg)  
Figure 5 Menu bar  
![](images/_page_36_Figure_0.jpeg)  
Figure 6 Menu  
#### Menu items  
Within an application, menu items don't usually vary (the exceptions are "integrated" applications where, for example, the spreadsheet and the word processor may have different sets of menus). This, too, contributes to the user's sense of stability. Even though sometimes certain items are unavailable, they remain in the menu—dimmed to show that they're unavailable at the moment.  
The user can either browse through menu items—without having to choose any of them—or choose one item to be executed. To browse, the user simply holds the mouse button down and moves the pointer through the menu bar, which pulls down one menu at a time.  
Selecting a menu item is a deliberate process. To choose an item from the menu that's pulled down, the user drags the pointer down to that item and releases the mouse button.  
Menus can include a wide range of items, typically grouped by type to make the most sense to the user.  
The Apple menu, often called the desk accessory menu, is always the leftmost menu. It lists the desk accessories that are currently installed on the system. This menu changes when the users installs a new desk accessory or deletes an old ne. Desk accessories are usually "mini-applications," implemented as device drivers, that can be run at the same time as a full-scale application.  
![](images/_page_37_Picture_0.jpeg)  
Figure 7 The Apple menu  
The second menu is the **File menu** (Figure 8), which lets the user perform tasks relative to whole documents—opening, closing, saving, and printing—from within an application. A key item in the File menu is the **Quit** operation, which lets the user quit an application at any time. This is in contrast to traditional applications that require the user to step backwards to a "Main Menu" before quitting.  
| File                                    |              |
|-----------------------------------------|--------------|
| New                                     | %N           |
| Open                                    | <b>%0</b>    |
| Close<br>Save<br>Save As<br>Revert to S | %\$<br>Saved |
| Page Setur<br>Print                     | )            |
| Quit                                    | жQ           |  
| Edit       |       |
|------------|-------|
| Undo       | ЖZ    |
| Cut        | жх    |
| Сору       | ЖС    |
| Paste      | ₩IJ   |
| Clear      |       |
| Select All |       |
|            |       |
| Show Clip  | board |  
Figure 8
File and Edit menus  
There are two important principles behind the items in the **Edit menu** (Figure 8). First, they make it explicit that anything the user can do, the user can also *undo*. Second, they allow the user to easily move information from one part of a document to another, or between documents—even between documents that are created by different applications.  
Every application should include an Edit menu with Undo, Cut, Copy, Paste, and Clear (in that order). Even if the application itself doesn't use them, those five commands must be available for desk accessories that may need them.