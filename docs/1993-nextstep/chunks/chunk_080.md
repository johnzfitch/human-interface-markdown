<!-- Chunk 80 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 1065 -->
Out of all running applications, at most one is selected to be the active application (the principal application the user is working in). An application must be activated-made to be the active application-before the user can type in its windows or use its menus.  
The active application differs from other running applications in four ways:  
- It's the only application with visible menus. When an application is deactivated, its menus are hidden from view. When it's reactivated, they're restored to the screen.
- It's the application that owns most, if not all, of the panels that are visible on-screen. In general, panels behave like menus: They hide when the application isn't active and return to the screen when the application is reactivated. In exceptional cases, however, you may choose to leave a panel on-screen even when the application isn't active. (See Chapter 5 for guidelines on when it's appropriate to allow a panel to persist.)
- It's the application that receives the user's keyboard actions. Typing and keyboard alternatives can affect only the active application. When there's no active application, the user's keystrokes have no effect.
- It's the application that contains the key window and main window (if there is a current key window or main window), and its windows are likely to be in front of the windows of other applications.  
#### **Application Activation**  
In general, the task of selecting the active application is left to the user. With one exception, an application never becomes active unless the user does something to activate it. The user's action can be direct, such as starting up the application or clicking in one of its windows, or indirect, such as having one application send a message to another application.  
The exception is that when the user hides or terminates an application, the system guesses which application should be activated next (based on which applications have on-screen windows, as described below). This method saves the user from always having to click to choose the new active application.  
An application is activated when:  
• The user starts it up, unless the user activates another application while the first one is starting up.  
- The user double-clicks a miniwindow belonging to the application, or double-clicks the application's freestanding or docked icon. Double-clicking a docked icon starts up the application if it's not already running.
- The user clicks within one of the windows belonging to the application, provided the window isn't a miniwindow or application icon.
- It receives a message from another application, if the message asks it to do something that may require interaction with the user. A message from the Workspace Manager asking the receiver to open a file is one such message. A message sent to Digital Webster asking it to define a word is another. (See "Activating an Application" later in this chapter for details.)
- It has the frontmost panel or standard window on-screen after the current application is hidden or terminated.  
#### **Application Deactivation**  
There can be only one active application per workspace (that is, one per Window Server) at a time. Whenever the user chooses a new active application, the previous one is automatically deactivated. The Application Kit and Workspace Manager take care of this task.  
The active application is also deactivated when:  
- The user hides its windows (by using the Hide command).
- The user terminates it (by choosing the Quit command).  
In either case, if another application has panels or standard windows on-screen, then the Workspace Manager activates the application with the frontmost panel or window. If no other applications have panels or standard windows on-screen, then no application becomes active.  
In addition, an application should deactivate itself just before sending a message to another application, if the intent of the message is to have the other application become active. (See "Activating an Application" later in this chapter for details.)  
**Note:** A deactivated but running application can still do work. It's "deactivated" only in the sense that it no longer is the active application, so the user can't interact with it without activating it again.