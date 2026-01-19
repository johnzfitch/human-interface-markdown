<!-- Chunk 13 | Source: 2013 OS X Human Interface Guidelines.pdf | Est. Tokens: 1017 -->
Users expect to be able to interact with their Mac using the input device of their choice. Some users might use a one-button or multibutton mouse, others might be more comfortable with a trackpad, and still others might use their voice or an assistive device to control their computer. As with the built-in apps, the best apps make no assumptions about the type of input device the user is using.  
The trackpad offers an alternative way to interact with Mac apps and the system. People use their fingers on the trackpad to perform actionsthey might otherwise perform using a mouse,such as move the pointer,select or activate a UI element, and scroll.  
In addition to such actions, a Multi-Touch trackpad can support gesturesthat perform more complex behaviors, such as:  
- Zoom in or out on the active image or view under the pointer
- Rotates the active view under the pointer in the direction of the user's movement
- Navigate forward or backward through a set of views or pages in the active window
- Show Mission Control, Launchpad, and App Exposé
- Switch between desktops and full-screen windows  
To perform some of these actions, users can change the gesture they want to use in Trackpad preferences. For example, a user might prefer to swipe with two or three fingers (instead scroll left or right with two fingers) to swipe between pages.  
![](images/_page_17_Picture_2.jpeg)  
Users expect to be able to activate systemwide features, such as Mission Control and switching between desktops and full-screen windows, regardless of the app they're currently using. Great Mac apps pay attention to the behavior associated with a gesture, in addition to the physical gesture itself, so that users can enjoy a consistent gesture experience throughout the system. To learn about supporting gestures in your app, see "Handle Gestures [Appropriately"](#page-42-0) (page 43).  
All users need to use the keyboard sometimes, and some users prefer using the keyboard to using a mouse or trackpad. Other users, such as VoiceOver users, might use only the keyboard. All keyboard users expect the system-defined and common keyboard shortcuts they're familiar with to work seamlessly in all apps. To learn more about the system-reserved and commonly used keyboard shortcuts, see ["Keyboard](#page-307-0) Shortcuts" (page 308).  
OS X also provides full keyboard access mode, in which users can navigate through windows and dialogs. When this mode is active, other keyboard combinations may be reserved by default. (Usersturn on full keyboard access in Keyboard preferences.)  
Finally, OS X reserves several key combinations for use with localized versions of system software, localized keyboards, keyboard layouts, and input methods. These key combinations(listed in Table 1-1) don't correspond directly to menu commands.  
<span id="page-18-0"></span>**Table 1-1** Key combinations reserved for international systems  
| Keys                                     | Action                                                                                       |
|------------------------------------------|----------------------------------------------------------------------------------------------|
| Command–Space<br>bar                     | Rotate<br>through<br>enabled<br>script<br>systems                                            |
| Option–Command–Space<br>bar              | Rotate<br>through<br>keyboard<br>layouts<br>and<br>input<br>methods<br>within<br>a<br>script |
| modifier<br>key<br>–Command–Space<br>bar | Apple<br>reserved                                                                            |
| Command–Right<br>Arrow                   | Change<br>keyboard<br>layout<br>to<br>current<br>layout<br>of<br>Roman<br>script             |
| Command–Left<br>Arrow                    | Change<br>keyboard<br>layout<br>to<br>current<br>layout<br>of<br>system<br>script            |  
To learn about creating keyboard shortcuts for commands in your app, see "Provide [Keyboard](#page-63-0) Shortcuts for Frequently Used [Commands"](#page-63-0) (page 64).