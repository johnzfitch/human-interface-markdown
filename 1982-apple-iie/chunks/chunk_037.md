<!-- Chunk 37 | Source: 1982 Apple IIe Design Guidelines.pdf | Est. Tokens: 2318 -->
| Keystroke                                     | Editing Operation                                                                                                                                                                                                                                                                   |
|-----------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Necessary:                                    |                                                                                                                                                                                                                                                                                     |
| LEFT-ARROW                                    | moves cursor left within input line.                                                                                                                                                                                                                                                |
| R I G H T – A R R O W                         | moves cursor right within input line.                                                                                                                                                                                                                                               |
| Either:                                       |                                                                                                                                                                                                                                                                                     |
| CTRL-SPACE,<br>CTRL-LEFT-<br>ARROW, or DELETE | will delete the character to the left of the cursor.                                                                                                                                                                                                                                |
| Either:                                       |                                                                                                                                                                                                                                                                                     |
| CTRL-RIGHT-<br>ARROW Or<br>CTRL-DELETE        | will delete the character to the right of the cursor.                                                                                                                                                                                                                               |
| RETURN                                        | accepts entire response, regardless of current cursor position.                                                                                                                                                                                                                     |
| CTRL-B                                        | has no effect on a display with a single input. On a multiple-input display (see next section), CTRL-RETURN accepts entire response, moving user back to previous input. Programs often use                                                                                         |
| CTRL-RETURN                                   | in addition to CTRL-B for accept and move back: CTRL-RETURN is indistinguishable from CTRL-M, or CTRL-whatever-character-your-user-has-defined-to-be-in-M's-standard-keyboard-position. Please take this potential risk into account before enabling CTRL-RETURN as well as CTRL-B. |
| CTRL-E                                        | deletes (erases) all characters on the input line.                                                                                                                                                                                                                                  |
| CTRL-K                                        | deletes all chars from present cursor position to end of line.                                                                                                                                                                                                                      |
| CTRL-U                                        | (Un-do) recalls display of default response. If no default, then it acts the same as $\mathtt{CTRL-E}.$                                                                                                                                                                             |
| Optional:                                     |                                                                                                                                                                                                                                                                                     |
| CTRL-P                                        | Prints the contents of the display on the default printer.                                                                                                                                                                                                                          |  
#### Notes  
Typing any printing character will automatically insert that character into the input line at the current cursor position.  
Pressing RETURN with the cursor anywhere within the input line will accept the entire input.  
Default responses are displayed with the cursor at the end of the response.  
RETURN will accept that response.  
LEFT-ARROW will move cursor back into the default response, enabling the  
user to edit it.  
RIGHT-ARROW will signal that you wish to append material to the response.  
CTRL-SPACE  
or DELETE will delete a single character from the end of a response and  
signal that you wish to edit the response.  
#### Using the New Input on an Apple II or Apple III Series Computer  
The program input statement asks the user for information by displaying a verbal prompt. Prompts should terminate in a colon (:) or greater-than sign (>) if a statement, a question-mark (?) if a question. The prompt is followed by 2 spaces on an 80-column display, 1 space on a 40-column display.  
A default answer may be displayed, with the cursor following, in which no field length is denoted. If there is no default response offered, or the default is rejected by the user, the program can display a finite input field with a series of periods (standard character set) or "ghost" underlines (hi-res character set). The latter character is essentially a shortened underline with every other dot turned off.  
The specification of the number of spaces between the prompt and the input field is quite important: users can become confused as to where their answer begins. If all programs adhere to one space with 40 column displays, 2 spaces with 80 column displays, the users will know whether they have inadvertently typed a leading space or not. (As a separate issue, leading and trailing spaces should be routinely stripped off, unless they are specifically needed.)  
Keystroke errors are best trapped immediately: if you are accepting a decimal number, do not accept a letter such as "A" or "B".  
Here is the example of the input which is taught on APPLE PRESENTS...APPLE for the Apple IIe:  
What is a "drift"?  
A whole lot of cattle\_  
(Consider the underline to be blinking — the printer was not able to quite capture the effect.) The problem presented is to change the answer to read:  
> A herd of cattle  
To edit the response, the user first moves back to the end of the word "lot," using the LEFT ARROW. It looks like this:  
> A whole lot of cattl\_e  
> A whole lot of catt\_le  
> A whole lot of cat\_tle  
> A whole lot of ca\_ttle  
> A whole lot of c\_attle  
> A whole lot of \_cattle  
> A whole lot of \_ cattle  
> A whole lot o\_f cattle  
> A whole lot \_of cattle  
> A whole lot\_ of cattle  
The user is next instructed to press the DELETE key several times, until the words "whole lot" have been deleted:  
A - of cattle  
Next, the user types the word "herd":  
> A h = of cattle  
A he\_ of cattle  
> A her \_ of cattle  
> A herd\_ of cattle  
Finally, the user can press RETURN to accept the entire response:  
) A herd of cattle  
#### Cursor Movement with no Action Taken  
Sometimes programs such as word processors require pure cursor movement with no action taken. The standard keys in such cases are as follows:  
Keys for up, down, left, and right motion:  
Apple II and Apple II Plus:  
These keys are often prefixed with an ESCAPE.  
Apple IIe: the four arrow keys Apple III: the four arrow keys  
Keys for vertical, horizontal, and diagonal motion:  
Apple II, Apple II Plus, and Apple IIe:  
These keys are often prefixed with an ESCAPE.  
Apple III:  
Full cursor movement on the Apple *III* is done using the numeric keypad: