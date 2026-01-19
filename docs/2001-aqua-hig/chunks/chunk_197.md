<!-- Chunk 197 | Source: 2001 Aqua Human Interface Guidelines.pdf | Est. Tokens: 692 -->
Apple reserves the right to reserve other keyboard equivalents in the future, so be careful about adding your own, and add them *only for frequently used commands.* For example, if users typically open the Preferences dialog when they first start using your application, but not after their preferences are set, don't assign it a keyboard equivalent.  
Use the Command key as the main modifier key for keyboard equivalents. For a command that complements another more common command, you can add Shift. The table below shows some recommended keyboard equivalents using Shift.  
<span id="page-174-0"></span>**Table 9-6** Recommended keyboard equivalents using Shift to complement other commands  
| Keys             | Command                              | Complemented command   |
|------------------|--------------------------------------|------------------------|
| Shift-Command-G  | Find Previous                        | Command-G (Find Again) |
| Shift-Command-P  | Page Setup                           | Command-P (Print)      |
| Shift-Command-S  | Save As                              | Command-S (Save)       |
| Shift-Command-V  | Paste as (Quotation, for<br>example) | Command-V (Paste)      |
| Shift-Command-Z* | Redo                                 | Command-Z (Undo)       |  
**<sup>\*</sup> This combination would be used only if Undo and Redo are separate commands (rather than toggled using Command-Z).**  
If there's a third, less common command that's related to a pair of commands that use Command and Shift-Command, you can use Option-Command for the third command's keyboard equivalent. In the example in Table 9-7, Save All could be a dynamic menu item (see ["Menu Behavior" \(page 48\)](#page-47-0)) that appears in place of Save when the user presses the Option key (rather than a separate menu item). Use combinations like these very rarely.  
<span id="page-174-1"></span>**Table 9-7** Example of using Option to modify a shortcut already using Command  
| Command  |
|----------|
| Save     |
| Save As  |
| Save All |
|          |  
The Keyboard **175**  
Also use Option for a keyboard equivalent that is a convenience or power user feature. For example, the Finder uses Option-Command-W for Close All Windows and Option-Command-M for Minimize All Windows.  
Remember that other languages may require modifier keys to generate certain characters. For example, the "[" character on a U.S. keyboard translates to Option-5 on a French or German keyboard. You can safely modify any character with the Command key, but avoid using Command and an additional modifier with characters not available on all keyboards. If you must use a modifier key in addition to the Command key, use them only with the alphabetic characters (*a* through *z*).