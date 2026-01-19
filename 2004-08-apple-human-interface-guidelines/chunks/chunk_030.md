<!-- Chunk 30 | Source: 2004-08 Apple Human Interface Guidelines.pdf | Est. Tokens: 833 -->
Don't use the keys and combinations in Table 2-3 for actions other than those listed in the table.  
**Table 2-3** Keyboard shortcuts reserved by the operating system  
| Keys                   | Action                                            |  |
|------------------------|---------------------------------------------------|--|
| Esc                    | Cancel the current action                         |  |
| Command-Tab            | Activate the most recently used open application  |  |
| Command-Shift-Tab      | Activate the least recently used open application |  |
| Command-Option-D       | Show or hide the Dock                             |  |
| Command-H              | Hide the active application                       |  |
| Command-Option-H       | Hide other applications (all but the active one)  |  |
| Command-Shift-Q        | Log out                                           |  |
| Command-Shift-Option-Q | Log out without confirmation                      |  |  
<span id="page-28-0"></span>  
| Keys                           | Action                                            |
|--------------------------------|---------------------------------------------------|
| Command-Shift-Option-Control-Q | Force log out without confirmation                |
| Command-Option-Esc             | Open the Force Quit dialog                        |
| Control-F1                     | Turn full keyboard navigation on or off           |
| Control-F7                     | Toggle keyboard navigation in windows and dialogs |  
<span id="page-28-8"></span>Mac OS X also provides full keyboard access mode, in which users can navigate through windows and dialogs. When this mode is active, other keyboard combinations may be reserved by default. (See*Making Carbon Applications Accessible to Users With Disabilities*.)  
Table 2-4 shows several key combinations that are reserved for use with localized versions of system software, localized keyboards, keyboard layouts, and input methods. These key combinations don't correspond directly to menu commands.  
<span id="page-28-9"></span><span id="page-28-1"></span>**Table 2-4** Key combinations reserved for international systems  
<span id="page-28-7"></span><span id="page-28-6"></span><span id="page-28-5"></span><span id="page-28-4"></span>  
| Keys                           | Action                                                               |
|--------------------------------|----------------------------------------------------------------------|
| Command–Space bar              | Rotate through enabled script systems                                |
| Command–Option–Space bar       | Rotate through keyboard layouts and input<br>methods within a script |
| Command–modifier key–Space bar | Apple reserved                                                       |
| Command–Right Arrow            | Change keyboard layout to current layout of<br>Roman script          |
| Command–Left Arrow             | Change keyboard layout to current layout of<br>system script         |  
#### <span id="page-28-3"></span><span id="page-28-2"></span>**Important**  
<span id="page-28-10"></span>Your application should not override the implementation of keyboard focus and navigation in Mac OS X. These features provide functionality for users with special needs.