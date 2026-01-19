<!-- Chunk 127 | Source: 2008-06 Apple Human Interface Guidelines.pdf | Est. Tokens: 1078 -->
Apple may reserve other keyboard shortcuts in the future, so be careful about adding your own. Before you consider creating a keyboard shortcut, be sure to look at the keyboard shortcutslisted in ["Keyboard](#page-354-0) Shortcuts Quick [Reference"](#page-354-0) (page 355) so you can avoid overriding the shortcuts users already know.  
You might also consider examining the keyboard shortcuts used in other applications that target the same user audience your application targets. If your users are likely to be familiar with these other applications, you should try to avoid overriding the shortcuts they're used to using.  
You should provide keyboard shortcuts *only forfrequently used commands*, not for every command. Presenting the user with too many keyboard shortcuts can be overwhelming and can make an application's user interface seem difficult to learn.  
<span id="page-104-1"></span>Use the Command key asthe main modifier key for keyboard equivalents. For a command that complements another more common command, you can add Shift. The table below shows some recommended keyboard equivalents using Shift and their relation with the command they complement.  
**Table 8-5** Recommended keyboard shortcuts using Shift to complement other commands  
| Keys            | Command                                    | Complemented command   |
|-----------------|--------------------------------------------|------------------------|
| Command-Shift-A | Deselect All                               | Command-A (Select All) |
| Command-Shift-G | Find Previous                              | Command-G (Find Again) |
| Command-Shift-P | Page Setup                                 | Command-P (Print)      |
| Command-Shift-S | Save As                                    | Command-S (Save)       |
| Command-Shift-V | Paste as (Paste as Quotation, for example) | Command-V (Paste)      |
| Command-Shift-Z | Redo                                       | Command-Z (Undo)       |  
**Note:** Command-Shift-Z would be used for Redo only if Undo and Redo are separate commands(rather than toggled using Command-Z).  
If there's a third, less common command that's related to a pair of commands that use Command and Command-Shift, you can use Command-Option for the third command's keyboard equivalent. In the example in Table 8-6 Save All could be a dynamic menu item (see ["Naming](#page-162-2) Menu Items" (page 163)) that appears in place of Save when the user presses the Option key (rather than a separate menu item). Use combinations like these very rarely.  
<span id="page-105-0"></span>**Table 8-6** Example of using Option to modify a shortcut already using Command  
| Keys             | Command  |
|------------------|----------|
| Command-S        | Save     |
| Command-Shift-S  | Save As  |
| Command-Option-S | Save All |  
Also use Option for a keyboard shortcut that is a convenience or power-user feature. For example, the Finder uses Command-Option-W for Close All Windows and Command-Option-M for Minimize All Windows.  
Because the Control key is already used by some of the universal access features as well as in Cocoa text fields where Emacs-style key bindings are often used, itshould be used as a modifier key only when necessary.  
<span id="page-105-2"></span>Remember that other languages may require modifier keys to generate certain characters. For example, on a French keyboard, Option-5 generates the "{" character. You can safely use the Command key as a modifier, but avoid using Command and an additional modifier with characters not available on all keyboards. If you must use a modifier key in addition to the Command key, try to use it only with the alphabetic characters (*a* through *z*).  
When adding custom keyboard shortcuts, try to avoid shortcuts that add a modifier key (such as Option or Shift) to an existing shortcut if the shortcuts have an unrelated function. For example, don't use Shift-Command-Z as a keyboard shortcut for a command that is unrelated to Undo. Using that shortcut for Redo is appropriate, but using it for something like Calculate or Check Mail is confusing. If you can't find a unique and easy-to-use keyboard shortcut for a command, don't use one at all; keep in mind that users may have difficulty pressing multiple modifier keys anyway.