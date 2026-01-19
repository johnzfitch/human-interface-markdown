<!-- Chunk 18 | Source: 2004-05 Apple Human Interface Guidelines.pdf | Est. Tokens: 1743 -->
Don't use the keys and combinations in Table 2-3 for actions other than those listed in the table.  
**Table 2-3** Keyboard shortcuts reserved by the operating system  
| Keys              | Action                                            |
|-------------------|---------------------------------------------------|
| Esc               | Cancel the current action                         |
| Command-Tab       | Activate the most recently used open application  |
| Command-Shift-Tab | Activate the least recently used open application |
| Command-Option-D  | Show or hide the Dock                             |
| Command-H         | Hide the active application                       |
| Command-Option-H  | Hide other applications (all but the active one)  |  
<span id="page-28-0"></span>  
| Keys                           | Action                                            |
|--------------------------------|---------------------------------------------------|
| Command-Shift-Q                | Log out                                           |
| Command-Shift-Option-Q         | Log out without confirmation                      |
| Command-Shift-Option-Control-Q | Force log out without confirmation                |
| Command-Option-Esc             | Open the Force Quit dialog                        |
| Control-F1                     | Turn full keyboard navigation on or off           |
| Control-F7                     | Toggle keyboard navigation in windows and dialogs |  
<span id="page-28-8"></span>Mac OS X also provides full keyboard access mode, in which users can navigate through windows and dialogs. When this mode is active, other keyboard combinations may be reserved by default. (See*Making Carbon Applications Accessible to Users With Disabilities*.)  
Table 2-4 shows several key combinations that are reserved for use with localized versions of system software, localized keyboards, keyboard layouts, and input methods. These key combinations don't correspond directly to menu commands.  
<span id="page-28-9"></span><span id="page-28-7"></span><span id="page-28-1"></span>**Table 2-4** Key combinations reserved for international systems  
<span id="page-28-6"></span><span id="page-28-5"></span><span id="page-28-4"></span><span id="page-28-3"></span>  
| Keys                           | Action                                                               |
|--------------------------------|----------------------------------------------------------------------|
| Command–Space bar              | Rotate through enabled script systems                                |
| Command–Option–Space bar       | Rotate through keyboard layouts and input<br>methods within a script |
| Command–modifier key–Space bar | Apple reserved                                                       |
| Command–Right Arrow            | Change keyboard layout to current layout of<br>Roman script          |
| Command–Left Arrow             | Change keyboard layout to current layout of<br>system script         |  
#### <span id="page-28-2"></span>**Important**  
<span id="page-28-10"></span>Your application should not override the implementation of keyboard focus and navigation in Mac OS X. These features provide functionality for users with special needs.  
#### Creating Your Own Keyboard Shortcuts  
Apple may reserve other keyboard shortcuts in the future, so be careful about adding your own. Add them *only for frequently used commands*, not for every command.  
Use the Command key as the main modifier key for keyboard equivalents. For a command that complements another more common command, you can add Shift. The table below shows some recommended keyboard equivalents using Shift and their relation with the command they complement.  
**Table 2-5** Recommended keyboard shortcuts using Shift to complement other commands  
<span id="page-29-0"></span>  
| Keys            | Command                                       | Complemented command   |
|-----------------|-----------------------------------------------|------------------------|
| Command-Shift-A | Deselect All                                  | Command-A (Select All) |
| Command-Shift-G | Find Previous                                 | Command-G (Find Again) |
| Command-Shift-P | Page Setup                                    | Command-P (Print)      |
| Command-Shift-S | Save As                                       | Command-S (Save)       |
| Command-Shift-V | Paste as (Paste as<br>Quotation, for example) | Command-V (Paste)      |
| Command-Shift-Z | Redo                                          | Command-Z (Undo)       |  
**Note:** Command-Shift-Z would be used for Redo only if Undo and Redo are separate commands (rather than toggled using Command-Z).  
If there's a third, less common command that's related to a pair of commands that use Command and Command-Shift, you can use Command-Option for the third command's keyboard equivalent. In the example in Table 2-6, Save All could be a dynamic menu item (see ["Naming Menu](#page-77-0) [Items"](#page-77-0) (page 78)) that appears in place of Save when the user presses the Option key (rather than a separate menu item). Use combinations like these very rarely.  
<span id="page-29-1"></span>**Table 2-6** Example of using Option to modify a shortcut already using Command  
| Keys             | Command  |
|------------------|----------|
| Command-S        | Save     |
| Command-Shift-S  | Save As  |
| Command-Option-S | Save All |  
Also use Option for a keyboard shortcut that is a convenience or power-user feature. For example, the Finder uses Command-Option-W for Close All Windows and Command-Option-M for Minimize All Windows.  
Because the Control key is already used by some of the universal access features as well as in Cocoa text fields where Emacs-style key bindings are often used, it should be used as a modifier key only when necessary.  
<span id="page-30-6"></span>Remember that other languages may require modifier keys to generate certain characters. For example, on a French keyboard, Option-5 generates the "{" character. You can safely use the Command key as a modifier, but avoid using Command and an additional modifier with characters not available on all keyboards. If you must use a modifier key in addition to the Command key, try to use it only with the alphabetic characters (*a* through *z*).  
When adding custom keyboard shortcuts, try to avoid shortcuts that add a modifier key (such as Option or Shift) to an existing shortcut if the shortcuts have an unrelated function. For example, don't use Shift-Command-Z as a keyboard shortcut for a command that is unrelated to Undo. Using that shortcut for Redo is appropriate while using it for something like Calculate or Check Mail is confusing. If you can't find a unique and easy -to-use keyboard shortcut for a command, don't use one at all; keep in mind that users may have difficulty pressing multiple modifiers anyway.