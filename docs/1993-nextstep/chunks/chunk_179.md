<!-- Chunk 179 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 464 -->
The Workspace Manager searches for executable files by using a *search path,* an ordered set of folders. The default path used by the Workspace Manager lists these six folders:  
-IApps /LocalApps INextApps INextDeveloperl Apps INextAdmin INextDeve1operlDemos  
The Workspace Manager uses this path for three tasks:  
- To find the icons it should display for files associated with a particular application.
- To find the application it should start up when the user double-clicks a file.
- To find services offered by applications.  
Before using the search path to find which application to start up, the Workspace Manager first looks in the dock. Each application icon in the dock represents a particular application residing in a particular folder on disk. By putting an icon in the dock, the user has indicated a preference for that version of the application over any others.  
If an application isn't in the dock, the Workspace Manager looks next in the current working folder, the folder containing the file the user wants to open. Only after failing to find the application there does it tum to the path listed above.  
In the path, the Workspace Manager looks first in the Apps folder of the current user's home folder. That's where the user's own applications would be. It next looks in the ILocalApps folder for sitewide software, then in the lNextApps, /NextDeveloper/Apps, lNextAdmin, and lNextDeveloperlDemos folders for NeXT-supplied software. This ordering of folders lets users customize their software to override sitewide software, and lets sitewide software override software supplied by NeXT.  
Users can alter the path shown above for the Workspace Manager by setting a value for the ApplicationPaths parameter in their defaults database. You might do this, for example, to add a ILocalAdmin or ILocalDeveloperl Apps folder to the path.