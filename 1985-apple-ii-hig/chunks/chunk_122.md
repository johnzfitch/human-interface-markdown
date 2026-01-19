<!-- Chunk 122 | Source: 1985 Apple II Human Interface Guidelines.pdf | Est. Tokens: 361 -->
If an application isn't primarily a text application, but does use text in fields (such as in a dialog box), it may not be able to provide the full text editing capabilities described so far.  
It's important, however, that whatever editing capabilities the application provides under these circumstances be upward-compatible with the full text editing capability. The following list shows the capabilities that can be provided, going from the minimal to the most sophisticated:  
- The user can move around using the cursor keys or mouse.
- The user can select the whole field and type in a new value.
- The user can backspace delete.
- The user can forward delete.
- The user can select a substring of the field and replace it.
- The user can select a word by double-clicking.
- The user can choose Undo, Cut, Copy, Paste, and Clear, as described above under "The Edit Menu". In the most sophisticated version, the application implements intelligent cut and paste.  
1/15/85 Tognazzini  
An application should also perform appropriate edit checks. For example, if the only legitimate value for a field is a string of digits, the application might issue an alert if the user typed any nondigits. Alternatively, the application could wait until the user is through typing before checking the validity of the contents of the field. In this case, the appropriate time to check the field is when the user clicks anywhere other than within the field.