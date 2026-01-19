<!-- Chunk 189 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 1472 -->
#### *active application*  
The application currently associated with keyboard events. Menus are visible on-screen only for the active application, and only the active application can have the current key window and main window.  
#### *anchor point*  
When the user drags to define a range, the position of the cursor when the mouse button is pressed. See also *end point.*  
#### *application*  
A program with a graphical user interface that the user can run from the workspace, such as Edit, FaxReader, or Preferences.  
#### *application dock*  
The column holding application icons at the right of the screen.  
#### *Application Kir'*  
The Objective C classes and C functions available for implementing the NeXT window-based user interface in an application. The Application Kit provides a basic program structure for applications that draw on the screen and respond to events.  
#### *arrow key*  
One of the four keys with arrows on them, to the left of the numeric keypad on the NeXT keyboard. They move the insertion point in the indicated direction.  
#### *auach*  
To choose a menu command that controls a submenu, causing the submenu to appear on-screen next to the supermenu (the menu with the controlling command). Moving or closing a supermenu also moves or closes its attached submenu; choosing the controlling command a second time detaches and hides the submenu.  
#### *attention panel*  
A panel that demands the user's attention. Until the user acts to dismiss the panel from the screen, no other action within the application is possible. Attention panels permit the user to rescind a command (such as Close), ask the user to complete a command (such as Save As), and give warnings that the user must acknowledge. See also *panel* and *ordinary panel.*  
#### *background color*  
In the Application Kit, the color that fills the content area of a window and provides a background for all the drawing done within the window, or the color that fills a View as a background for any drawing the View or its subviews do.  
#### *bar*  
The part of a slider or a scroller that holds ~he moveable knob. See also *knob.*  
#### *busy cursor*  
The cursor image (a spinning disk) that indicates that an application is busy.  
#### *character code*  
The code that identifies a character in a given character set; an index into the character set's encoding vector.  
#### *character keys*  
The keys that transmit characters to the NeXT computer. This includes not only the usual letters, numbers, and symbols, but also Return, Enter, Delete, Tab, Esc, and the arrow keys.  
#### *character set*  
The set of characters for a particular font or fonts; either the NeXTSTEP character set (an extension of ASCII) or Symbol.  
#### *class*  
In the Objective C language, a prototype for a particular kind of object. A class definition declares instance variables and defines methods for all members of the class. Objects that have the same types of instance variables and have access to the same methods belong to the same class. See also *class object.*  
#### *click*  
To press and release a mouse button while the cursor is positioned over an object on-screen. Clicking an object may select it or cause it to act in some way. Users can also click to select a particular location (for the insertion point, for example).  
#### *close button*  
The button that can appear at the far right in a window's title bar. Clicking the button closes the window (removes it from the workspace).  
#### *content area*  
The area within a window that's available for the application to use. It excludes only the window's border, title bar, and resize bar.  
#### *controls*  
Graphical objects-such as buttons, sliders, text fields, and scrollers-that the user can operate to give instructions to an application.  
#### *cursor*  
The small image (usually an arrow) that moves on the screen correspondingly as you move the mouse.  
#### *delegate*  
In the Application Kit, an object that acts on behalf of another object. Window, Application, Text, Listener, NXBrowser, NXImage, and other objects can be assigned delegates.  
#### *directory*  
See *folder.*  
#### *dock*  
See *application dock.*  
#### *docked icon*  
An icon in the application dock.  
#### *document window*  
A window that displays the contents of a user-created file.  
#### *double-click*  
To press and release a mouse button twice in succession while the cursor is positioned over an object on-screen. To count as a double-click rather than as two separate clicks, the mouse cannot move and the mouse button must be pressed the second time within a short interval of the first.  
#### *drag*  
To move the mouse (and the cursor on screen) while a mouse button is held down.  
#### *endpoint*  
When the user drags to define a range, the position of the cursor when the mouse button is released. See also *anchor point.*  
#### *event*  
The direct or indirect report of a user's action on the keyboard or mouse.  
#### *event mask*  
A long integer associated with a window. It controls which types of events will be associated with the window and passed to the application that owns the window. A 1 in the bit corresponding to a particular event type means the window will accept that type of event.  
#### *file*  
A collection of related information stored on a disk, such as a document, report, letter, or application.  
#### *file package*  
A folder that the Workspace Manager presents as a file, allowing the user to manipulate a group of files as if they were one file. A file package for an application executable should have the same name as the executable file, plus a ".app" extension. File packages for documents should bear the same extension as the one assigned to the application's document files.  
#### *file system*  
The collection of all the files the user can access through the computer.