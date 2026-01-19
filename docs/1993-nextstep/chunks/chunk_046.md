<!-- Chunk 46 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 865 -->
Initially, until the user specifies a different preference, applications should follow the guidelines for keyboard alternatives described in this section. Users can use the Preferences application to alter the keyboard alternatives for every application at once. You're also encouraged to let the user choose and change keyboard alternatives using your application's Preferences panel.  
The guidelines place keyboard alternatives into three groups-reserved, required, and recommended. These groups are listed in the tables that follow along with the commands they perform and the menus where the commands are located. (See "Standard Menus and Commands" in Chapter 6 for more information on the listed commands and menus.)  
#### **Reserved Keyboard Alternatives**  
Reserved keyboard alternatives must be used for the commands that follow, and cannot be used for any others. If your application implements the functionality that a command represents, it must provide both the command and the keyboard alternative.  
For example, if your application opens files, it must have an Open command with Command-o as the keyboard alternative. If your application doesn't allow the user to open files, it won't have an Open command and must not use Command-o as a keyboard alternative.  
| Keyboard Alternative | Command      | Menu          |
|----------------------|--------------|---------------|
| Command-?            | Help         | Info menu     |
| Command-a            | Select All   | Edit menu     |
| Command-c            | Copy         | Edit menu     |
| Command-h            | Hide         | main menu     |
| Command-n            | New          | Document menu |
| Command-o            | Open         | Document menu |
| Command-p            | Print        | main menu     |
| Command-q            | Quit         | main menu     |
| Command-s            | Save         | Document menu |
| Command-v            | Paste        | Edit menu     |
| Command-w            | Close Window | Windows menu  |
| Command-x            | Cut          | Edit menu     |
| Command-z            | Undo         | Edit menu     |  
#### **Required Keyboard Alternatives**  
These keyboard alternatives must be used if the application implements the command. For example, if your application has a Find panel, you must provide Command-f as a way of bringing the panel up.  
However, if an application doesn't implement the particular functionality of an item (if it doesn't have a Find panel, for example), it can use the keyboard alternative (Command-f) for something else. Nevertheless, to preserve interapplication consistency, it's strongly recommended that you first try to use characters that don't overlap with those on this list.  
| Keyboard Alternative | Command           | Menu          |
|----------------------|-------------------|---------------|
| Command-=            | Define in Webster | Services menu |
| Command-;            | Check Spelling    | Edit menu     |
| Command-b            | Bold (Unbold)     | Font menu     |
| Command-d            | Find Previous     | Find menu     |
| Command-e            | Enter Selection   | Find menu     |
| Command-f            | Find Panel        | Find menu     |
| Command-g            | Find Next         | Find menu     |
| Command-i            | Italic (Unitalic) | Font menu     |
| Command-t            | Font Panel        | Font menu     |
| Command-C            | Colors            | varies        |