<!-- Chunk 10 | Source: 1982 Apple IIe Design Guidelines.pdf | Est. Tokens: 434 -->
The Apple IIe Monitor has been carefully rewritten to maintain all the same entry points as those published in the original Apple II Reference Manual. (The same entry points are, of course, also listed in the Apple IIe Reference Manual.) At the same time, the Monitor screen-  
handling routines have been changed to accommodate the requirements of 80-column display.  
The keyboard ROM map now features lowercase characters as well as several characters not directly available on the Apple II and II Plus keyboard.  
To adapt software to these new features, follow these guidelines:  
- Either avoid performing checksums on the resident firmware or be prepared to accept the checksum outcome of each model of Apple II that the software will run on.
- 2. Make sure that the program is designed to recognize lowercase characters or to convert them to uppercase as necessary.
- 3. Make sure the program reacts appropriately to the alternate single-quote character (decimal code 96) now on the keyboard, as well as the more commonly used single quote character (decimal code 39) that has always been present on Apple II keyboards.
- 4. Programs that compensated for the absence of certain characters (for example,  $\setminus$  or |) do not need to do so for the Apple IIe.
- 5. If a program uses Monitor input/output routines, it should not use the 80-column software switch at location 49165 (\$C00D).
- 6. BASIC programs that use 80-column firmware should POKE location 36 with tab locations rather than attempting to do "comma tabbing."
- Any program that uses 80-column firmware cannot also display flashing characters. Flashing characters are not available in the alternate character set, which is the set the 80-column firmware uses.