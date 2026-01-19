---
chunk_index: 1708
ref: "1638f3227592"
id: "1638f3227592167bdcc906d9a4c91e1a8d7fd06f7fb441a8f5645fea0b6585fc"
slug: "chunk-062--desk-accessories"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/chunks/chunk_062.md"
kind: "markdown"
lines: [48, 58]
token_estimate: 737
content_sha256: "6e5e4a2976b678e6a6f685c60f727bec0fb06f37d03fea69a25ccf80b9819a20"
compacted: false
heading_path: ["Alerts","Beeps","Alert boxes","Desk accessories"]
symbol: null
address: null
asset_path: null
---

#### Desk accessories  
A desk accessory is a program with a relatively limited scope that can be opened while another application is running. Desk accessories can be created to perform a wide range of functions. Some imitate useful objects found on real desktops—the standard Macintosh Note Pad, Alarm Clock, and Calculator, for example. Some (the Chooser, for example) are file- or network-related utilities that users may need to access from within a number of different applications. Some are specific to an application or type of application, such as rulers and other graphics tools that are available only in graphics applications, and spelling checkers that are needed only when a word processing application is being used. There are also "idle" programs that blank out the screen or display special graphics after the computer has been idle for a specified period of time. Figure 3-17 shows some desk accessories on a desktop.  
![](images/_page_76_Picture_2.jpeg)  
Figure 3-17 Some desk accessories  
The user can quickly open one or more desk accessories by choosing them from the Apple menu. Generally, all installed desk accessories can be accessed from the Finder or from any other application, except for desk accessories specific to a particular application or type of application.  
Don't design a full-scale application and implement it as a desk accessory. If it's really an application, treat it as an application. Remember that there is <sup>a</sup> limit on the number of desk accessories that can be installed at one time. On the other hand, if your application is a relatively small one that is useful in a variety of situations, consider making it a desk accessory.  
Desk accessories don't have to be windows, but desk accessories that are windows should behave like windows. The user should be able to move them around the screen and dismiss them by clicking a close box.  
A desk accessory can add one (and only one) menu to the application's menu bar. This menu goes away when the desk accessory is closed. Desk accessories should never interfere with the application's menus.  
If possible, let users install and remove all desk accessories in one standard way. Users should be able to install all Macintosh desk accessories with the standard Font/DA Mover rather than with a special installation program.  
All applications should treat desk accessories in a standard way. If a desk accessory opens a window, that window should remain open on the desktop until the user explicitly closes it or quits the current application. The principle "the user is in control" suggests that an application should not close desk accessories just because the user opens or closes document windows. When help systems are implemented as desk accessories, for example, the user can open and close document windows without losing the help window.  
There's more on desk accessories under the heading "The Apple Menu" in this chapter.