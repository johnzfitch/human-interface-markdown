<!-- Chunk 81 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 566 -->
Mac OS X services are features that applications can make available to each other. Through services, you can share your application's resources and capabilities with other applications. In turn, users of your application can take advantage of the resources and capabilities provided by other applications. The Services feature is one of the many ways Mac OS X helps your application interoperate with others. (Interoperability is a characteristic of great software; to learn more about it, see ["Interoperability"](#page-36-0) (page 37).)  
By default, the application menu contains a Services submenu that lists services that are appropriate for the currently selected or targeted content in your application. This submenu automatically includes a command that opens Services preferences in Keyboard Shortcuts preferences. The services can be provided by applications installed anywhere on the system.  
To vend services to other applications, your application provides information about each service, such as:  
- The data types on which it operates
- The command that can appear in the Services menu
- The keyboard shortcut for invoking the command, if appropriate. Note that if the keyboard shortcut you choose conflicts with a keyboard shortcut in the currently running application, the application'sshortcut is always used.  
To learn the programmatic steps you need to take to provide services and take advantage of them, read *Services Implementation Guide*.  
To ensure a good user experience, you should follow these guidelines when defining the services your application can provide:  
- Give each service a short, focused title that describes exactly what it does.
- Strive to create a unique service title. If there are two or more services with identical names, the application name is automatically displayed after each service to distinguish them.
- As with all menu-item names, use title-style capitalization for the service title and, in general, avoid including definite or indefinite articles.  
Good examples are "Look Up in Dictionary" and "Make New Sticky Note."  
● Avoid providing an "Open in *Application Name*" service.  
Instead, users should view the applications that can open a selected file in the Open With menu item of the Finder.