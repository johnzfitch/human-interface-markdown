<!-- Chunk 53 | Source: 1986-07 Human Interface Guidelines (Second Beta Draft).pdf | Est. Tokens: 372 -->
If an application isn't primarily a text application, but does use text in fields (such as in a dialog box), it may not be able to provide the full text-editing capabilities described so far. It's important, however, that whatever editing capabilities the application provides under these circumstances be upward-compatible with the full text-editing capabilities. The following list ranks the capabilities that can be provided, in a continuum from the minimum set to the most sophisticated features: .  
- The user can select the whole field and type in a new value.
- The user can backspace.
- The user can select a substring of the field and replace it.  
- The user can select a word by double clicking.
- The user can choose Undo, Cut, Copy, Paste, and Clear, as described in "The Edit Menu."
- Intelligent cut and paste is fully implemented.  
An application should also perform appropriate edit checks. For example, if the only legitimate value for a field is a string of digits, the application issues an alert message if the user types any nondigits. For example, the alert message might interrupt the erring user to remind that the letters I and I can't be used in place of the numerals I and I and I and I the application could wait until the user is through typing before checking the validity of a field's contents. In this case, the appropriate time to check the field is when the user clicks anywhere other than within the field or presses the Return, Enter, or Tab key.  
(