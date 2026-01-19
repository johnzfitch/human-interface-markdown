<!-- Chunk 185 | Source: 2004-05 Apple Human Interface Guidelines.pdf | Est. Tokens: 269 -->
A **text input field**, also called an editable text field, is a rectangular area in which the user enters text or modifies existing text. The text input field can be active or disabled. It supports keyboard focus and password entry.  
Your application's text input fields should perform appropriate edit checks. For example, if the only legitimate value for a field is a string of digits, the application issues an alert if the user types nondigits. In most cases, the appropriate time to check the data in the field is when the user clicks outside the field or presses the Return, Enter, or Tab key.  
Combination boxes have text input fields and also contain a menu or a list of choices. See ["Combination Boxes"](#page-176-0) (page 177).  
**Cocoa:** Text input fields are available in Interface Builder. Create them programmatically with CreateEditUnicodeTextControl.  
**Cocoa:** Text input fields are available in Interface Builder. Use the NSTextField class to create them programmatically. See *Text Views* in Cocoa User Experience documentation.  
Text Controls **187**