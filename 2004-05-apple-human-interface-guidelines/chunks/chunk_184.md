<!-- Chunk 184 | Source: 2004-05 Apple Human Interface Guidelines.pdf | Est. Tokens: 221 -->
Use a **static text field** for informational text in a dialog (text not intended to be modified by users). Static text fields have two states: active and dimmed.  
Controls  
When it provides an obvious user benefit, static text should be selectable. For example, a user should be able to copy an error message or a serial number to paste elsewhere.  
**Carbon:** Static text fields in various standard fonts are available in Interface Builder. Create them programmatically with CreateStaticTextControl.  
**Cocoa:** Static text fields in various standard fonts are available in Interface Builder. To create one programmatically, use the NSTextField class. See *Text Views* in Cocoa User Experience documentation.  
#### Static Text Field Specifications  
#### ■ **Size:**  
❏ Full size: System font  
❏ Small: Small system font  
<span id="page-186-0"></span>❏ Mini: Mini system font