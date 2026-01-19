<!-- Chunk 90 | Source: 2008-01 Apple Human Interface Guidelines.pdf | Est. Tokens: 325 -->
Bundles make it possible to provide drag-and-drop installation for applications (for more information on application bundles, see *Bundle Programming Guide*). Using bundles is the preferred way to install an application for the following reasons:  
- It is easy for users to install and uninstall the application.
- It takes less time to install (only the time needed to copy the bundle).
- You don't have to spend time developing an installer.  
Providing drag-and-drop installation does not preclude you from placing files in specific places on the system. When your application is first run, it can copy any needed support files to appropriate places on the system. However,you should avoid usingthis technique to install additional executable code and should instead use it to install preference files, document templates, or other resources that can be regenerated as needed and are not required for the application to run.  
Software Installation and Software Updates  
**Note:** Ifyou install additional fileswhen your application is firstrun, be sure to install them in obvious places, such as in the Application Support directory. Place your resources in a directory named for your application to make it easy for the user to find these files if they ever need to uninstall your application.