<!-- Chunk 36 | Source: 1982 Apple IIe Design Guidelines.pdf | Est. Tokens: 1117 -->
#### Apple II Series  
| Keystroke            | Editing Operation                                                                                                                                                    |
|----------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Necessary:           |                                                                                                                                                                      |
| LEFT-ARROW           | moves cursor left within input line.                                                                                                                                 |
| RIGHT-ARROW          | moves cursor right within input line.                                                                                                                                |
| CTRL-D               | deletes character to the left of the cursor - Apple II & II+.                                                                                                        |
| DELETE               | deletes character to the left of the cursor - Apple IIe.                                                                                                             |
| RETURN               | accepts entire response, regardless of current cursor position.                                                                                                      |
| CTRL-B               | has no effect on a display with a single input. On a multiple- input display (see next section), CTRL-B accepts entire response, moving user back to previous input. |
| Useful if implementa | tion language allows sufficient speed:                                                                                                                               |
| CTRL-X               | deletes all characters on the input line.                                                                                                                            |
| CTRL-Y               | deletes all chars from present cursor position to end of line.                                                                                                       |
| CTRL-R               | recalls display of default response. If no default, then it acts the same as $\mathtt{CTRL-X}$ .                                                                     |
| Optional:            |                                                                                                                                                                      |
| CTRL-P               | Prints the contents of the display on the default printer.                                                                                                           |  
#### **Notes**  
Because this input is new to Apple II and Apple II+ users, it is particularly inportant that you expressly state on the display that CTRL-D is used to delete characters. (Apple IIe users have been trained how to use this input on the APPLE PRESENTS...APPLE diskette, but a reminder to use the DELETE key would be helpful.)  
Typing any printing character will automatically insert that character into the input line at the current cursor position.  
Pressing RETURN with the cursor anywhere within the input line will accept the entire input.  
Default responses are displayed with the cursor at the end of the response.  
| RETURN      | will accept that response.                                                                                                |
|-------------|---------------------------------------------------------------------------------------------------------------------------|
| LEFT-ARROW  | will move cursor back into the default response, enabling the user to edit it.                                            |
| RIGHT-ARROW | will signal that you wish to append material to the response.                                                             |
| CTRL-D      | (Apple II & II+) will delete a single character from the end of a response and signal that you wish to edit the response. |  
DELETE (Apple IIe) will delete a single character from the end of the response and signal that you wish to edit the response.  
Pressing any other key will clear the default response and begin a new response in its place.