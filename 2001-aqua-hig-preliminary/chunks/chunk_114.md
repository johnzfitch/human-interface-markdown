<!-- Chunk 114 | Source: 2001 Aqua Human Interface Guidelines (Preliminary).pdf | Est. Tokens: 1435 -->
Mac OS X reserves certain keyboard combinations as equivalents to menu commands; these shortcuts affect all applications. Even if your application doesn't support all the combinations shown in [Table 8-3](#page-137-3), don't use any of them for another function.  
<span id="page-137-5"></span><span id="page-137-3"></span><span id="page-137-1"></span>**Table 8-3** Reserved and recommended keyboard equivalents  
| Menu        | Keys       | Command          |
|-------------|------------|------------------|
| Application | Command-H* | Hide             |
| Application | Command-Q* | Quit             |
| Window      | Command-M* | Minimize         |
| File        | Command-N* | New              |
| File        | Command-O  | Open             |
| File        | Command-W  | Close            |
| File        | Command-S  | Save             |
| File        | Command-P  | Print            |
| Edit        | Command-Z  | Undo             |
| Edit        | Command-X  | Cut              |
| Edit        | Command-C  | Copy             |
| Edit        | Command-V  | Paste            |
| Edit        | Command-A  | Select All       |
| Format      | Command-T  | Open Font dialog |  
**<sup>\*</sup>These combinations are reserved by the system; the others are recommended.**  
#### User Input  
Some applications use other common keyboard equivalents, as shown in [Table 8-4](#page-138-3). If you choose not to implement these functions in your product, you may use these equivalents for other actions, although that could make your application less intuitive for users accustomed to the combinations shown here.  
<span id="page-138-15"></span><span id="page-138-3"></span><span id="page-138-0"></span>**Table 8-4** Common keyboard equivalents that are not reserved  
<span id="page-138-6"></span><span id="page-138-5"></span><span id="page-138-4"></span>  
| Menu               | Keys      | Command    |
|--------------------|-----------|------------|
| Edit (recommended) | Command-F | Find       |
| Edit (recommended) | Command-G | Find Again |
| Format             | Command-B | Bold       |
| Format             | Command-I | Italic     |
| Format             | Command-U | Underline  |  
<span id="page-138-13"></span><span id="page-138-7"></span>[Table 8-5](#page-138-2) shows several key combinations that are reserved for use with localized versions of system software, localized keyboards, keyboard layouts, and input methods. These equivalents don't correspond directly to menu commands.  
<span id="page-138-14"></span><span id="page-138-2"></span><span id="page-138-1"></span>**Table 8-5** Key combinations reserved for international systems  
<span id="page-138-12"></span><span id="page-138-11"></span><span id="page-138-10"></span><span id="page-138-9"></span>  
| Keys                           | Action                                                               |
|--------------------------------|----------------------------------------------------------------------|
| Command–Space bar              | Rotate through enabled script systems                                |
| Command–Option–Space bar       | Rotate through keyboard layouts and input<br>methods within a script |
| Command–modifier key–Space bar | Apple reserved                                                       |
| Command–Right Arrow            | Changes keyboard layout to current layout of<br>Roman script         |
| Command–Left Arrow             | Changes keyboard layout to current layout of<br>system script        |  
<span id="page-138-8"></span>The Keyboard **139**  
#### <span id="page-139-3"></span><span id="page-139-0"></span>Creating Your Own Keyboard Equivalents  
Apple reserves the right to reserve other keyboard equivalents in the future, so be careful about adding your own, and add them *only for frequently used commands.* For example, if users typically open the Preferences dialog when they first start using your application, but not after their preferences are set, don't assign it a keyboard shortcut.  
Use the Command key as the main modifier key for shortcuts. For a command that complements another more common command, you can add Shift. The table below shows some recommended keyboard equivalents using Shift.  
<span id="page-139-1"></span>**Table 8-6** Recommended keyboard equivalents using Shift to complement other commands  
| Keys            | Command                           | Complemented command   |
|-----------------|-----------------------------------|------------------------|
| Shift-Command-G | Find Previous                     | Command-G (Find Again) |
| Shift-Command-P | Page Setup                        | Command-P (Print)      |
| Shift-Command-S | Save As                           | Command-S (Save)       |
| Shift-Command-V | Paste as (Quotation, for example) | Command-V (Paste)      |
| Shift-Command-Z | Redo                              | Command-Z (Undo)       |  
Use Option for a command that is a power user feature and that further augments the behavior of a combination that already uses Shift. The set of commands should be related. For example, the Finder uses Command-Delete for Move to Trash and Shift-Command-Delete for Empty Trash.  
<span id="page-139-4"></span><span id="page-139-2"></span>Remember that other languages may require modifier keys to generate certain characters. For example, the "[" character on a U.S. keyboard translates to Option-5 on a French or German keyboard. You can safely modify any character with the Command key, but avoid using Command and an additional modifier with characters not available on all keyboards. If you must use a modifier key in addition to the Command key, use only the alphabetic characters (*a* through *z*).