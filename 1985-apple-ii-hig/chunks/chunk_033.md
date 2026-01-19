<!-- Chunk 33 | Source: 1985 Apple II Human Interface Guidelines.pdf | Est. Tokens: 1594 -->
More specific guidelines for the windowing interface will be found in that section. While the windowing guidelines do not clash with the following information, they do go beyond it in power and performance. If you are working with the windowing software, refer to the appropriate sections for more specific information.  
The program input statement asks the user for information by displaying a verbal prompt. Prompts should terminate in a colon (:) or greater-than sign (>) if a statement, a question-mark (?) if a question. The prompt is followed by 2 spaces on an 80-column display, 1 space on a 40-column display.  
A default answer may be displayed, with the cursor following, in which no field length is denoted. If there is no default response offered, or the default is rejected by the user, the program can display a finite input field with a series of "ghost" underlines (MouseText character "I"). This character is a shortened underline with every other dot turned off. Since the user cannot type it, there can be no abiguity.  
Leading and trailing spaces should be routinely stripped from input lines, unless they are specifically needed.  
Keystroke errors are best trapped immediately: if you are accepting a number, do not accept a letter such as "A" or "B".  
An example of the input:  
What is a "drift"?  
> A whole lot of cattle  
(Consider the underline to be blinking — the printer was not able to quite capture the effect.) The user wants to change the answer to read:  
> A herd of cattle  
To edit the response, the user first moves back to the end of the word "lot," using the Left-Arrow. It looks like this:  
> A whole lot of cattle\_  
The user now moves the cursor to the left by pressing the Left-Arrow.  
- > A whole lot of cattle
> A whole lot of cattl
- Because the cursor alternates with the character to the right of the theoretical insertion point, that character is invisible half the time. In the rest of the sequence, we shall assume that we are looking during the time that the character is invisible and the cursor is visible.  
The input buffer: You should maintain an input buffer larger than the field length of the input, with a pointer showing how much of it you should allow to be visible. Let's say you have a field length of 25 and the user has typed in:  
What do you use if you want to turn left? A right-hand turn signal\_ A right-hand turn signal.  
(In order to show the two phases of the blinking cursor, each example shows the user-response, both while the bar is showing and the character "under it" is showing.)  
The user suddenly realizes the error of his answer and backtracks:  
What do you use if you want to turn left? A \_ight-hand turn signal. A right-hand turn signal.  
So far, the contents of the input buffer have not been changed. Now the user types in the correct answer:  
What do you use if you want to turn left? A left\_ight-hand turn sig
A leftright-hand turn sig  
Instead of either not allowing the user to enter any more characters, or shoving the "nal" part of "signal" off into oblivion, move all the characters ahead in your 250+ character input buffer. So, internally, you are now carrying the answer:  
A leftright-hand turn signal  
with a pointer that tells you only to display to the "g" in "signal". Now, when the user uses the right-delete key (CONTROL-F) to delete the word, "right", you can again show the characters that had been hidden:  
What do you use if you want to turn left? A \_eft-hand turn signal.. A left-hand turn signal..  
When the user presses RETURN, accept only those characters that are visible: this buffer is just there to make changes easier. You need not maintain a full 250+ character buffer if you only have short input fields. Try to have an input buffer at least twice as long as the longest field, and dump characters off the right end if the user keeps backing up and inserting: don't ever have the input simply lock up. A CONTROL-Y or CONTROL-X should clear to the end of the actual input buffer, not just the visible portion.  
Cursor Movement with no action taken  
Sometimes programs such as word processors require pure cursor movement with no action taken. The standard keys in such cases are as follows:  
Keys for up, right, down, and left motion:  
Apple IIe and newer computers: the four arrow keys  
Apple II and Apple II+:  
I=up J=left K=right M=down  
These keys are often prefixed with an ESCape.  
Keys for vertical, horizointal, and diagonal motion:  
All Apple II computers:  
U=up,left I=up O=up,right
J=left K=right
N=down,left M=down ,=down,right  
These keys are often prefixed with an ESCape.  
![](images/_page_54_Figure_6.jpeg)  
- Stop: A situation that requires remedial action by the user. The situation could be either a serious problem, or something as simple as a request by the application to the user to change diskettes.  
An application can define several stages for an alert, so that if the user persists in the same mistake, the application can issue increasingly more helpful (or sterner) messages. A typical sequence is for the first two occurrences of the mistake to result in a beep, and for subsequent occurrences to result in an alert box. This type of sequence is especially appropriate when the mistake is one that has a high probability of being accidental. An example is when the user chooses Cut when the selection is an insertion point.  
Under no circumstances should an alert message refer the user to external documentation for further clarification. It should provide an adequate description of the information needed by the user to take appropriate action. Avoid at all costs such messages as:  
Application error #1463  
Error messages should not only provide information (in the user's native tongue -- not computerese) as to what the error was, but should offer solutions as to what the user can do to correct the situation. A better message might be:  
The program here requires the name of the file you want to work from. You have not yet selected a file. Please type the name of one of the above files first.  
So, generally, it's better to be polite than abrupt, even if it means lengthening the message. The role of the alert box is to be helpful, make constructive suggestions, and to help the user solve the problem, not to give an interesting but academic description of the problem itself.