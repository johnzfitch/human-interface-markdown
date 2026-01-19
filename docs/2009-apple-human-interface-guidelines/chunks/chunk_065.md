<!-- Chunk 65 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 525 -->
<span id="page-64-4"></span><span id="page-64-3"></span><span id="page-64-2"></span><span id="page-64-1"></span>Remember that Mac OS X is a multiple-usersystem. Not only doesthe system support multiple user accounts, it supports multiple users sharing the same computer simultaneously. This feature employs a technique known as fast user switching, in which users trade use of the computer without logging out. With multiple users accessing the computer, conflicts can arise if applications are not careful about how they use shared resources. Shared memory, cache files, semaphores, and named pipes must be carefully labeled to prevent corruption by usersrunning the same application in differentsessions. Applications cannot assume that they have exclusive access to any system resources, such as a CD or DVD drive.  
<span id="page-64-7"></span>When considering access by multiple users, there are some specific things to keep in mind for your program design:  
- <span id="page-64-6"></span>● Named resources that might potentially be accessible to an application from multiple user sessions should incorporate the session ID into the name of the resource. This applies to cache files, shared memory, semaphores, and named pipes, among others.
- Not all users have the same privileges. For example, only administrator users can write files in /Applications. Some users may be working under limited privileges and have limited access to some parts of the system. In particular, they may not be able to do the following:
- Access all panes in System Preferences
- Modify the Dock
- Change their password
- Burn DVDs and CDs
- Open certain applications
- <span id="page-64-5"></span>● Users on a computer can include both local and network users,so do not assume a user's home directory is on a local volume. You may be accessing a network volume instead.  
The document *Multiple User Environments* describes issues that arise from the existence of multiple users on a system. It also covers programmatic techniques for identifying users and protecting your application data from external corruption.