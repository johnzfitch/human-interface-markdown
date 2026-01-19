<!-- Chunk 127 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 222 -->
The Application Kit takes care of everything discussed in this section, IIHow Menus Work." Specifically, it provides the following functionality:  
- All aspects of displaying and hiding menus and menu commands (although you must specify when a command should be disabled), including tearing off submenus
- Letting you associate menu commands with menus
- Making sure the keyboard alternative works
- Detecting when the user chooses a menu command and reacting appropriately (such as by highlighting and bringing up a panel)  
Much of this functionality can also be accessed through Interface Builder. For example, to associate an application-specific command with a menu, the programmer can simply drag a menu command from the Palettes window into the menu. You can then change the name of the command, give it a keyboard alternative if necessary, and associate an action with the command.