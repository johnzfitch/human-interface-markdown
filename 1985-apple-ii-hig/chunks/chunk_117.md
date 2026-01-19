<!-- Chunk 117 | Source: 1985 Apple II Human Interface Guidelines.pdf | Est. Tokens: 137 -->
When the user presses Control-F, one of two things happens:  
- If the current selection is one or more characters, it's deleted (exactly as with Delete).
- If the current selection is an insertion point, the character to the right of the insertion point is deleted. (The cursor in a MouseText-based program is a blinking underscore. Since the underscore itself is to the right of the insertion-point, the effect is that the character immediately above the underscore is deleted.)  
In both cases, the deleted characters don't go into the Clipboard.