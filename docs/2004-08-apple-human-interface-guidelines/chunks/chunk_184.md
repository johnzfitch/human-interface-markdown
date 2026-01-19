<!-- Chunk 184 | Source: 2004-08 Apple Human Interface Guidelines.pdf | Est. Tokens: 197 -->
**Metal buttons** are for use in brushed metal windows.  
#### Metal buttons:  
- Can contain icons, graphics, or text
- Can have the behavior of other types of buttons, including radio buttons or checkboxes  
<span id="page-157-1"></span>Don't use metal buttons in dialogs. Dialogs should never use the brushed metal look. See ["Brushed](#page-110-0) [Metal Windows"](#page-110-0) (page 111) for guidelines on when to use brushed metal windows.  
If a button acts on a single setting, label the button as specifically as possible.  
**Figure 10-4** Metal buttons  
![](images/_page_157_Figure_18.jpeg)  
**Carbon:** Not available.  
**Cocoa:** Use the NSButtonCell method setBezelStyle with NSTexturedSquareBezelStyle as the argument. See *Buttons* in Cocoa User Experience Documentation.