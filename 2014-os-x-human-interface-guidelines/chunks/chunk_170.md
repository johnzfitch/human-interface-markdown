<!-- Chunk 170 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 610 -->
OS X is a multiple-user system. Not only does the system support multiple user accounts, it allows multiple usersto be logged in simultaneously so that they can share the same computer in quick succession. Thisfeature employs a technique known as fast user switching, in which users trade use of the computer without logging out.  
The fast user switching menu is displayed by clicking the current user's name in the menu bar. The menu lists the names of the other users who have accounts on the computer (and whether they're currently logged in).  
![](images/_page_278_Picture_3.jpeg)  
When a different user's name is chosen in the fast user switching menu, the current desktop (or full-screen window) is veiled and a login window appears. The new user logs in, sees the system exactly as they left it, and immediately gets access to their content.  
With multiple users accessing the computer, conflicts can arise if apps are not careful about how they use shared resources. Great apps take care to avoid making assumptions about the current user's privileges and access to system resources and external devices.  
**Be prepared for multiple users with different privileges.** The OS X fast user switching feature allows multiple usersto be logged in simultaneously and to switch quickly between accounts. To ensure that your app behaves appropriately when there are multiple users logged in or when the current user has limited privileges, keep the following things in mind:  
Some users may be working under limited privileges and have limited access to some parts of the system. For example, only administrator users can write filesin /Applications. In particular, users with limited privileges may not be able to:  
- Access all panes in System Preferences
- Modify the Dock
- Change their password
- Burn DVDs and CDs
- Open certain apps
- Visit certain websites  
Users on a computer can include both local and network users, so don't assume that a user's home directory is on a local volume. Be prepared for the possibility that you are accessing a network volume instead.  
Named resourcesthat might potentially be accessible to an app from multiple usersessionsshould incorporate the session ID into the name of the resource. This applies to cache files, shared memory, semaphores, and named pipes, among others.  
To learn more about the ramifications of a multiuser system, see *Multiple User Environment Programming Topics*.