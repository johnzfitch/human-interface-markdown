<!-- Chunk 68 | Source: 2008-01 Apple Human Interface Guidelines.pdf | Est. Tokens: 1276 -->
A hallmark of Mac OS X is the use of animation to enhance the user experience, such as in the minimizing of windows to the Dock, the unfurling of sheets, and the sliding of drawers. In Mac OS X v10.5 and later, animation powers the movement of icons in the Finder Cover Flow view, the springing of items from a stack in the Dock, and the arrival of buddies in an iChat window, among other things. Figure 6-2 shows a "time-lapsed" view of items springing from a stack.  
<span id="page-69-1"></span>**Figure 6-2** Animation allows items in a stack to emerge smoothly  
![](images/_page_69_Picture_6.jpeg)  
Animation allows users track the movements of objects, helps them understand the effects of their actions, and lends a sense of physicality and realism to the virtual world they see on the display screen. In general, animation is ideal for:  
■ Communicating progress  
Using Mac OS X Technologies  
- Providing meaningful feedback
- Clarifying a process or concept  
If you are developing an application to run in Mac OS X v10.5 and later, you, too, can take advantage of animation by using Core Animation programminginterfaces. Aswith most powerful tools, however, it's important to use animation wisely, that is, as a subtle enhancement to the user experience, not as the focus of the user experience. For example, you might consider using animation in the following cases:  
■ When users navigate a collection.  
When navigation is similar to familiar, real-world activities, such as flipping through pages in a book or DVDs on a shelf, users are better able to grasp the organization and extent of a collection. In addition,when items in a collection appearto have realistic dimensionalityandweight, they're easier to recognize at a glance.  
■ When it's helpful for users to understand the consequences of an action before they commit to it.  
Showing users the results of an action before theycomplete it allows them to be sure of themselves and avoid mistakes. For example, items in the Dock move aside when users drag an object into the Dock area, showing them where the new object will reside when they release the mouse button.  
■ When users enter or initiate a different interaction mode.  
When users enter a different mode of interaction, such as full-screen mode, animation can guide them and provide clues that help them keep trackof the current mode.For example, the animated star field in Time Machine provides a completely different user experience that helps the user distinguish between the Time Machine view of the system and the user's standard view of the system.  
■ When an object changes its properties.  
Showing an object's transition from one state to another, instead of showing only the beginning and ending states, helps users understand what's happening and gives them a greater sense of control over the process. For example, in an application that allows users to change several properties of a document at one time, an icon that smoothly shows the effects of the combination of changes would provide valuable feedback.  
■ When an action occurs so quickly, users can't track it.  
Although speed and efficiency are essential in software, sometimes an action can take place so quicklythat its context orresult is unclear. When it's important that users understand a connection or a process, animation can help them watch actions occur in a more human time frame. For example, when the user minimizes a window it doesn't just disappear from the desktop and reappear in the Dock; instead, it moves fluidly from the desktop to the Dock so the user knows where it went.  
Ifyou decide to use animation, therefore, be sure the animation subtlyenhances the tasks and concepts your application focuses on and doesn't distract from them. Although animation can clarify obscure or hidden processes and provide valuable feedback, gratuitous or illogical animation can degrade the user experience, in addition to decreasing the performance of your application. In particular, you should:  
Animation **71**  
- Avoid replicating a Front Row or Time Machine style of user interface for an application that requires a lot of user input (especially textual input) or that users use for content creation. A fully animated, full-screen userinterface that displays large, simplified controls does not make detailed content-creation tasks easier or more efficient.
- Avoid animating everything.
- Although it's tempting to think that more animation results in greater clarification and better feedback, it's not generally true. Most tasks and actions in an application are best performed quickly and with a minimum of fanfare.
- Avoid animating routine user-interface actions supported by system-provided controls, such as:
- ❏ Switching tabs
- ❏ Opening or closing views
- ❏ Clicking toolbar items  
Users understand how common user interface elements work, and they don't appreciate being forced to spend extra time watching unnecessary animation every time they click a button.  
To learn more about using animation in your application, see *Core Animation Programming Guide*.