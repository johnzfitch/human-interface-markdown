<!-- Chunk 224 | Source: 2004-08 Apple Human Interface Guidelines.pdf | Est. Tokens: 175 -->
Use a **static text field** for informational text in a dialog (text not intended to be modified by users). Static text fields have two states: active and dimmed.  
When it provides an obvious user benefit, static text should be selectable. For example, a user should be able to copy an error message or a serial number to paste elsewhere.  
**Carbon:** Static text fields in various standard fonts are available in Interface Builder. Create them programmatically with CreateStaticTextControl.  
**Cocoa:** Static text fields in various standard fonts are available in Interface Builder. To create one programmatically, use the NSTextField class. See *Text Views* in Cocoa User Experience documentation.