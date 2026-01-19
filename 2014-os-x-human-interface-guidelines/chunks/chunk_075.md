<!-- Chunk 75 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 399 -->
When users Control-click a running app's Dock icon, a customizable Dock menu appears. By default, this menu displays the same items as the minimal Dock menu that's displayed when users press and hold the Dock icon. For more information about different styles of Dock menus, see The [Dock](#page-255-0) (page 256). In addition, this menu can contain app-specific items, such as the playback-focused commands in the customized iTunes Dock menu you see here. (Note that the Dock and Dock menus use the current appearance that the userspecifiesin General preferences.)  
Light menu bar and Dock appearance Dark menu bar and Dock appearance  
![](images/_page_110_Picture_3.jpeg)  
![](images/_page_110_Picture_4.jpeg)  
The custom itemsthat you add appear in the Dock menu only when your app is open and the user Control-clicks the Dock icon. You might consider adding items such as:  
- Common commands to initiate actions in your app when it is not frontmost
- Commands that are applicable when there is no open document window
- Status and informational text  
For example, Mail provides commands to compose a message and check for new messages. (To learn how to customize the Dock menu in code, see *Dock Tile Programming Guide* .)  
![](images/_page_111_Picture_2.jpeg)  
**Be sure that all Dock menu commands are also available in your app's menus.** Users might not know about the Dock menu, so it should not be the only way to do something.  
**Place your app-specific items above the standard Dock menu items.** Users should always know where to look for the system-provided Dock menu commands.