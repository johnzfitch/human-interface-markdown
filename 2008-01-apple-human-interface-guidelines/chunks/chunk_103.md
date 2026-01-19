<!-- Chunk 103 | Source: 2008-01 Apple Human Interface Guidelines.pdf | Est. Tokens: 2688 -->
<span id="page-105-4"></span><span id="page-105-3"></span>Keyboard shortcuts are used throughout Mac OS X to provide quick ways for users to initiate certain actions. Many are provided by the operating system to meet both general usability needs and accessibility needs. The operating system therefore reserves certain keys and keyboard combinations for its use. These combinations, listed in Table 8-3 and Table 8-4 affect all applications and should not be used for anyotherfunction. Otherkeyboard shortcuts are used bythe Universal Access features in Mac OS X and should be avoided.  
In addition to the keyboard shortcuts reserved by the system, there are a large number of keyboard shortcuts that have a well established meaning, such as Command-S for Save and Command-Q for Quit. Users accustomed to running applications in Mac OS X expect these keyboard shortcuts to be available and to mean the same thingin each application they use. An application that overrides these shortcuts, such as one that uses Command-Q for a Query command instead of Quit, runs the risk of unnecessarily confusing and frustrating its users.  
These common keyboard shortcuts are not reserved bythe system, but theyare highlyrecommended for applications that offer the associated commands. If your application does not offer all of these common commands, be sure you don't override these keyboard shortcuts and associate them with other commands your application does implement. A complete list of both system-reserved and commonly used keyboard shortcuts in Mac OS X is provided in ["Keyboard](#page-370-0) Shortcuts Quick [Reference"](#page-370-0) (page 371)  
<span id="page-105-2"></span>You may also define keyboard shortcuts in your application for frequently used commands. Some guidelines on how to create appropriate shortcuts are in ["Creating](#page-106-1) Your Own Keyboard [Shortcuts"](#page-106-1) (page 107) Other sections of this document list recommended keyboard shortcuts, where appropriate, to help you provide a consistent and familiar user experience in your application.  
#### <span id="page-105-1"></span>Reserved Keyboard Shortcuts  
Don't use the keys and key combinations in Table 8-3 for actions other than those listed in the table.  
**Table 8-3** Keyboard shortcuts reserved by the operating system  
| Keys                           | Action                                            |
|--------------------------------|---------------------------------------------------|
| Esc                            | Cancel the current action                         |
| Command-Tab                    | Activate the most recently used open application  |
| Command-Shift-Tab              | Activate the least recently used open application |
| Command-Option-D               | Show or hide the Dock                             |
| Command-H                      | Hide the active application                       |
| Command-Option-H               | Hide other applications (all but the active one)  |
| Command-Shift-Q                | Log out                                           |
| Command-Shift-Option-Q         | Log out without confirmation                      |
| Command-Shift-Option-Control-Q | Force log out without confirmation                |  
| Keys               | Action                                                 |
|--------------------|--------------------------------------------------------|
| Command–Space bar  | Show or hide Spotlight search field                    |
| Command-Option-Esc | Open the Force Quit dialog                             |
| Command-F5         | Turn VoiceOver on or off                               |
| Control-F1         | Turn full keyboard navigation on or off                |
| Control-F7         | Toggle keyboard navigation in windows and dialogs      |
| F9                 | Tile or untile all open windows                        |
| F10                | Tile or untile all open windows in current application |
| F11                | Hide or show all open windows                          |
| F12                | Display or hide Dashboard                              |  
<span id="page-106-7"></span>Mac OS X also provides full keyboard access mode, in which users can navigate through windows and dialogs. When this mode is active, otherkeyboard combinations maybe reserved by default. (See *Accessibility Overview*.)  
**Important:** Your application should not override the implementation ofkeyboard focus and navigation in Mac OS X. These features provide functionality for users with special needs.  
<span id="page-106-8"></span><span id="page-106-0"></span>Table 8-4 shows several key combinations that are reserved for use with localized versions of system software, localized keyboards, keyboard layouts, and input methods. These key combinations don't correspond directly to menu commands.  
<span id="page-106-6"></span>**Table 8-4** Key combinations reserved for international systems  
<span id="page-106-5"></span><span id="page-106-4"></span><span id="page-106-3"></span><span id="page-106-2"></span>  
| Keys                           | Action                                                               |
|--------------------------------|----------------------------------------------------------------------|
| Command–Space bar              | Rotate through enabled script systems                                |
| Command–Option–Space bar       | Rotate through keyboard layouts and input methods within a<br>script |
| Command–modifier key–Space bar | Apple reserved                                                       |
| Command–Right Arrow            | Change keyboard layout to current layout of Roman script             |
| Command–Left Arrow             | Change keyboard layout to current layout of system script            |  
#### <span id="page-106-9"></span><span id="page-106-1"></span>Creating Your Own Keyboard Shortcuts  
Apple may reserve other keyboard shortcuts in the future, so be careful about adding your own. Before you consider creating a keyboard shortcut, be sure to look at the keyboard shortcuts listed in ["Keyboard](#page-370-0) Shortcuts Quick Reference" (page 371) so you can avoid overriding the shortcuts users already know.  
You might also consider examining the keyboard shortcuts used in other applications that target the same user audience your application targets. If your users are likely to be familiar with these other applications, you should try to avoid overriding the shortcuts they're used to using.  
You should provide keyboard shortcuts *only for frequently used commands*, not for every command. Presenting the user with too many keyboard shortcuts can be overwhelming and can make an application's user interface seem difficult to learn.  
<span id="page-107-0"></span>Use the Command key as the main modifier key for keyboard equivalents. For a command that complements another more common command, you can add Shift. The table below shows some recommended keyboard equivalents usingShift and theirrelationwith the command theycomplement.  
**Table 8-5** Recommended keyboard shortcuts using Shift to complement other commands  
| Keys            | Command                                    | Complemented command   |
|-----------------|--------------------------------------------|------------------------|
| Command-Shift-A | Deselect All                               | Command-A (Select All) |
| Command-Shift-G | Find Previous                              | Command-G (Find Again) |
| Command-Shift-P | Page Setup                                 | Command-P (Print)      |
| Command-Shift-S | Save As                                    | Command-S (Save)       |
| Command-Shift-V | Paste as (Paste as Quotation, for example) | Command-V (Paste)      |
| Command-Shift-Z | Redo                                       | Command-Z (Undo)       |  
**Note:** Command-Shift-Z would be used for Redo only if Undo and Redo are separate commands (rather than toggled using Command-Z).  
<span id="page-107-1"></span>If there's a third, less common command that's related to a pair of commands that use Command and Command-Shift, you can use Command-Option for the third command's keyboard equivalent. In the example in Table 8-6 Save All could be a dynamic menu item (see ["Naming](#page-166-2) Menu Items" (page 167)) that appears in place of Savewhen the user presses the Option key(rather than a separate menu item). Use combinations like these very rarely.  
**Table 8-6** Example of using Option to modify a shortcut already using Command  
| Keys             | Command  |
|------------------|----------|
| Command-S        | Save     |
| Command-Shift-S  | Save As  |
| Command-Option-S | Save All |  
Also use Option for a keyboard shortcut that is a convenience or power-user feature. For example, the Finder uses Command-Option-W for Close All Windows and Command-Option-M for Minimize All Windows.  
Because the Control key is already used by some of the universal access features as well as in Cocoa text fields where Emacs-style key bindings are often used, it should be used as a modifier key only when necessary.  
<span id="page-108-6"></span>Rememberthat otherlanguages mayrequire modifierkeys togenerate certain characters.For example, on a French keyboard, Option-5 generates the "{" character. You can safely use the Command key as a modifier, but avoid using Command and an additional modifier with characters not available on all keyboards. If you must use a modifier key in addition to the Command key, try to use it only with the alphabetic characters (*a* through *z*).  
When adding custom keyboard shortcuts, try to avoid shortcuts that add a modifier key (such as Option or Shift) to an existing shortcut if the shortcuts have an unrelated function. For example, don't use Shift-Command-Z as a keyboard shortcut for a command that is unrelated to Undo. Using that shortcut for Redo is appropriate, but usingit for somethinglike Calculate or Check Mail is confusing. If you can't find a unique and easy-to-use keyboard shortcut for a command, don't use one at all; keep in mind that users may have difficulty pressing multiple modifier keys anyway.  
#### User-Defined Keyboard Shortcuts  
<span id="page-108-2"></span><span id="page-108-0"></span>Users may modify your application's keyboard shortcuts and some of the system in Keyboard & Mouse preferences. Even though users can remap keyboard shortcuts, you should adhere to the shortcuts recommended throughout this document. Doing so provides a more consistent user experience. See ["Keyboard](#page-370-0) Shortcuts Quick Reference" (page 371) for a list of all the reserved and recommended combinations.