<!-- Chunk 194 | Source: 2002 Aqua Human Interface Guidelines.pdf | Est. Tokens: 1820 -->
#### User Input  
Table 9-4 shows several key combinations that are reserved for use with localized versions of system software, localized keyboards, keyboard layouts, and input methods. These key combinations don't correspond directly to menu commands.  
<span id="page-176-5"></span>**Table 9-4** Key combinations reserved for international systems  
<span id="page-176-4"></span><span id="page-176-3"></span><span id="page-176-2"></span><span id="page-176-1"></span>  
| Keys                           | Action                                                               |
|--------------------------------|----------------------------------------------------------------------|
| Command–Space bar              | Rotate through enabled script systems                                |
| Command–Option–Space bar       | Rotate through keyboard layouts and input<br>methods within a script |
| Command–modifier key–Space bar | Apple reserved                                                       |
| Command–Right Arrow            | Changes keyboard layout to current layout<br>of Roman script         |
| Command–Left Arrow             | Changes keyboard layout to current layout<br>of system script        |  
<span id="page-176-6"></span><span id="page-176-0"></span>Mac OS X (version 10.2 and later) provides a way for users to enlarge onscreen objects. Users can turn on the screen-zooming feature in the Seeing pane of Universal Access preferences. If your application uses any of the keyboard combinations in Table 9-5, they are overridden when zooming is turned on.  
**Table 9-5** Key combinations used with screen zooming  
| Key combination          | Action                        |
|--------------------------|-------------------------------|
| Option–Command–*         | Turn screen zooming on or off |
| Option–Command–+         | Zoom in                       |
| Option–Command (hyphen)  | Zoom out                      |
| Control-Option-Command-* | Invert the screen colors      |
| Option-Command-/         | Turn smoothing on or off      |
|                          |                               |  
The Keyboard **177**  
#### User Input  
<span id="page-177-6"></span>Mac OS X 10.1 and later provides the option of **full keyboard access mode,** in which users can navigate through windows and dialogs. (See ["Full Keyboard Access](#page-183-1)  [Mode" \(page 184\).](#page-183-1))  
#### **Important**  
Your application should not override the implementation of keyboard focus and navigation in Mac OS X. These features provide functionality for users with special needs.  
<span id="page-177-0"></span>**Table 9-6** Key combinations for moving focus in full keyboard access mode (mnemonic alternatives are in parentheses)  
<span id="page-177-5"></span><span id="page-177-4"></span><span id="page-177-3"></span><span id="page-177-2"></span><span id="page-177-1"></span>  
| Key combinations                      | Action                                                                                                                |
|---------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| Control-F1                            | Turn full keyboard access on or off                                                                                   |
| Control-F7                            | Temporarily override the current keyboard access mode in<br>windows and dialogs                                       |
| Control-F2 (Control-m)*               | Move focus to the menu bar                                                                                            |
| Control-F3 (Control-d)*               | Move focus to the Dock                                                                                                |
| Control-F4 (Control-w)                | Move focus to the active (or next) window                                                                             |
| Control-F5 (Control-t)*               | Move focus to the toolbar                                                                                             |
| Control-F6 (Control-u)*               | Move focus to the first (or next) utility window (palette)                                                            |
| Shift-Control-F6<br>(Shift-Control-w) | Move focus to the previous utility window                                                                             |
| Control-Tab                           | Move focus to the next grouping of controls in a dialog or the<br>next table (when Tab moves to next cell)            |
| Shift-Control-Tab                     | Move focus to the previous grouping of controls                                                                       |
| Command-Tab                           | Movs focus to the first (or next) open application's Dock icon                                                        |
| Shift-Command-Tab                     | Move focus to the previous open application's Dock icon                                                               |
| Arrow key                             | Move focus to the next or previous value in a text field or certain<br>controls, such as menus; also opens Dock menus |  
<sup>\*</sup> Users can change these default combinations in the Full Keyboard Access pane of Keyboard preferences. When full keyboard access is on, user-defined combinations override any combinations used in applications.  
**Table 9-6** Key combinations for moving focus in full keyboard access mode (mnemonic alternatives are in parentheses) (continued)  
| Key combinations  | Action                                                                                                                                            |
|-------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|
| Control–arrow key | Move focus to another value or cell within a control such as a<br>table                                                                           |
| Command-~         | Activate the next open window in the frontmost application                                                                                        |
| Shift-Command-~   | Activate the previous open window in the frontmost application                                                                                    |
| Space bar         | Select the highlighted control (equivalent to clicking the mouse<br>button)                                                                       |
| Return (Enter)    | Select the default button                                                                                                                         |
| Escape            | Cancel a dialog or a selection in a pop-up menu or list; in a Dock<br>menu, Escape closes the menu and moves the focus to the<br>frontmost window |  
<sup>\*</sup> Users can change these default combinations in the Full Keyboard Access pane of Keyboard preferences. When full keyboard access is on, user-defined combinations override any combinations used in applications.