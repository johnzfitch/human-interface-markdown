<!-- Chunk 31 | Source: 2004-08 Apple Human Interface Guidelines.pdf | Est. Tokens: 912 -->
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
<span id="page-29-2"></span>Because the Control key is already used by some of the universal access features as well as in Cocoa text fields where Emacs-style key bindings are often used, it should be used as a modifier key only when necessary.  
Remember that other languages may require modifier keys to generate certain characters. For example, on a French keyboard, Option-5 generates the "{" character. You can safely use the Command key as a modifier, but avoid using Command and an additional modifier with characters not available on all keyboards. If you must use a modifier key in addition to the Command key, try to use it only with the alphabetic characters (*a* through *z*).  
When adding custom keyboard shortcuts, try to avoid shortcuts that add a modifier key (such as Option or Shift) to an existing shortcut if the shortcuts have an unrelated function. For example, don't use Shift-Command-Z as a keyboard shortcut for a command that is unrelated to Undo. Using that shortcut for Redo is appropriate while using it for something like Calculate or Check Mail is confusing. If you can't find a unique and easy -to-use keyboard shortcut for a command, don't use one at all; keep in mind that users may have difficulty pressing multiple modifiers anyway.