<!-- Chunk 124 | Source: 2012 OS X Human Interface Guidelines.pdf | Est. Tokens: 1187 -->
A **source list** (also called a **sidebar**) is an area of a window, usually set off by a movable splitter, that provides users with a way to navigate orselect objectsin an app (for more information on splitters,see "Split [View"](#page-294-0) (page 295)). Typically, users select an object in the source list that they act on in the main part of the window.  
You can provide a source list as the primary means of navigating or viewing within your app, as the Finder and Mail do, or as a way to select a view in a part of the app, as the Network preferences pane does. Each of these usage patterns is associated with a different source list appearance. Specifically:  
- A source list that provides the primary navigation or selection mechanism for the app as a whole displays a blue background.
- A source list that provides selection functionality for the window, but not the app as a whole, displays a white background.  
For example, the Finder sidebar, which helps users navigate the file system, uses the blue background.  
![](images/_page_189_Picture_5.jpeg)  
To learn how to design icons to display in a sidebar similar to the Finder sidebar, see ["Designing](#page-124-0) Sidebar [Icons"](#page-124-0) (page 125).  
In the figure below, you can see the white background of the source list in Network preferences, which allows users to select a network service to configure.  
![](images/_page_190_Picture_2.jpeg)  
The following guidelines help you use a source list appropriately in your app.  
**Consider using a source list to give users a file-system abstraction.** A source list can shield users from the details of file and document management, and allow them to work with user-customizable, app-specific containers that hold related items. Source lists can be especially useful in single-window apps that aren't necessarily document-based, but that allow users to create and manage content. For example, iTunes allows users to ignore the file-system locations of their songs, podcasts, and movies, and instead work with libraries and playlists. Similarly, iWeb focuses on website creation, not on file management.  
In particular, you might consider using a source list in your app when:  
- Navigation and selection of content are primary tasks.
- Collections of objects are key to the user's mental model (to learn more about the mental model, see ["Mental](#page-26-2) Model" (page 27)).
- The hierarchical arrangement of objects presents a natural way to navigate.
- Arranging objects hierarchically removes complexity.  
**If necessary, display titles inside the source list.** Source lists don't generally have headers like lists can, but they can display titles to distinguish subsets of objects or data. For example, the Finder displays several useful subsets of locations in its sidebar, such as Devices, Shared, and Places.  
![](images/_page_191_Picture_6.jpeg)  
**Avoid displaying more than two levels of hierarchy in a source list.** If the data you need to display is organized in more than two levels of hierarchy, you can use a second source list, but you should not use additional disclosure triangles to expose additional levels of hierarchy in a single source list. If, however, your app is centered on the navigation of deeply nested objects, you should consider using a browser view instead of multiple source lists.  
**Use the appropriate background appearance in your source list.** If your app contains a single source list that provides primary navigation and selection functionality, you can use the blue background. In all other cases, however, you should use the white background. Specifically, use the white background when:  
- Your window contains more than one source list.
- You use a source list in a panel or preferences window.  
**As much as possible, allow users to customize the contents of a source list.** It's best when users can decide which object containers are most important to them. You should also consider using Spotlight to support smart data containers. For more information on using Spotlight in your app, read *Spotlight Overview*.  
If you need to allow users to add, remove, manipulate, or get information about items in a source list, you can use gradient buttons at the bottom edge of the source list. Gradient buttons look good on the window-body area. (For details about using gradient buttons, see ["Gradient](#page-249-0) Button" (page 250).)  
**Consider using a popover instead of a source list.** If your source list does not represent primary functionality in your app you might consider replacing it with a popover, because a popover can appear only when users need it. To learn more about using a popover in your app, see ["Popovers"](#page-204-0) (page 205).