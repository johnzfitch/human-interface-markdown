<!-- Chunk 38 | Source: 1982 Apple IIe Design Guidelines.pdf | Est. Tokens: 3719 -->
In the olden days of computers, one typed a command to a computer onto a punched card. One then walked down the hall to the computer room, left said card, and returned some hours later to find that the command was syntactically incorrect. Later, time-sharing changed all that. Now one could type in the command, then press a single key called  
RETURN which would send the command down the hall. Soon (15 seconds or so later) the computer would announce the command was syntactically incorrect.  
Many microcomputer programs still wait around until the user has made a thorough fool of himself and pressed RETURN before sending the results "down the hall" to the program unit which does keyword matching. This unnecessary waste of processing time and power is inherent in the built-in input routines of the languages which have been ported over to micros from time-share systems. Since we are generally supplanting those old routines with the new blinking-underline routine, which is accessible and can be taken apart, this waste need not go on.  
Keyword matching is used in programs which are command-driven and programs with lists, such as file names, from which a user must select by typing in the name of the selection. Often, the human interface is rather sparse:  
| Command Word?                              |
|--------------------------------------------|
| File Name?                                 |
| Enter command and command-object:          |
| or, even more simply, (for the programmer) |
|                                            |  
Command-driven programs offer a speed and flexibility not generally attainable in a menu-driven program. They also typically offer a much steeper learning curve—so debilitating a learning curve that salespeople will often avoid selling a command-driven program because of the time and practice required for them to give even a rudimentary demonstration. Result? Lost sales.  
In order to type a command or list selection without prompting, the user must learn what words he can type at any one point in the program. This learning problem can be overcome in a straightforward manner by displaying a list of all options then available. Typically, this can be done by creating a display similar to the standard menu format, with the center region devoted to the list of words.  
| Commodity Analyzer | Belly Processes | Pork Bellies |  |
|--------------------|-----------------|--------------|--|
| Commands           | Inventory Type  | es:          |  |
| display            | complete        | e bellies    |  |
| graph              | partial bellies |              |  |
| compute            | dancing bellies |              |  |
| buy                |                 |              |  |
| sell               |                 |              |  |
| eat                |                 |              |  |
| delete             |                 |              |  |  
Options: ESCAPE to leave OPEN-APPLE-? for help  
As the available options change, so do the options displayed. Thus, the user knows at every point exactly what she can select. (The display of command words could be made optional through the novice/expert flag; variable lists of words, such as file names, should always be visible.)  
A second, more subtle learning problem must be handled a different way: Typically, a command word system will allow abreviations: why make the user type in "display dancing bellies" when "di d" is all that is required to make the user's intentions clear? (Display and Delete both start with d. Once the i is added, display is the only possible answer. The only command-object that currently starts with a d is "dancing bellies." Thus, the user's meaning is not ambiguous.  
Usually the user has either had to look up abbreviations of command words in the manual, or discover them by trial and error. Words from lists such as current file names have simply had to be typed out completely, with no abbreviations accepted. The Disambiguator changes all that.  
The algorithm for figuring out at what point the user has typed enough so that an answer is unique (not ambiguous) is really quite simple: on each keystroke, the list of possible words is scanned for a match-up of as many letters have been typed so far. As soon as only one match can be found, the word has been found and can be completed by the program. In the above example, the sequence would look like this:  
Type your instruction and press RETURN.
D\_  
No unique match is found (both delete and display match) so the input only echos the user's character.  
Type your instruction and press RETURN. DI = splay  
User's response is no longer ambiguous: the program supplies the remaining characters in the opposite case from that the user is typing. (An alternate character set can be used when the environment permits, so that the user can type both uppercase and lowercase characters.)  
Type your instruction and press RETURN. DIS\_play  
The user has not noticed that the computer has made a match, which happens often with a touch-typist. There is no penalty: the new character is echoed and the program now supplies just that portion of the command word still remaining.  
Type your instruction and press RETURN.
DISPLAY \_  
The user has noticed that the answer has been found and has pressed the terminating character, in this case a space. The program completes the word, using the case that the user has been typing and adds the space to the end.  
Type your instruction and press RETURN.
DISPLAY D\_ancing bellies  
As soon as the "D" in "dancing bellies" has been typed, the remainder of the phrase becomes clear.  
Type your instruction and press RETURN.
DISPLAY DANCING BELLIES  
The user terminates the input with RETURN and the full answer is echoed and acted upon.  
The Disambiguator input has been used in a number of programs over the last two years: it has proven to be quite successful. It lets people get used to abbreviations at their own speed, without their having to look up anything or get yelled at by the computer for using the wrong abbreviation, yet it accomplishes this with no penalty to the touchtypist who is just as happy pounding out the entire word. As a fringe benefit, it speeds up the program's response time: when the user presses RETURN, the program already knows what the instruction is and that it is legal.  
Pascal programs handling lists of up to thirty words in any one context have been implemented with this routine in Pascal. Pascal programs with very long lists or any BASIC programs need the routine to be implemented in native code.  
The Disambiguator algorithm is just an example of the kind of processing that can go on actively during the user's input to make the user's life a little easier. There is no longer any technical reason for programs to stand by while users flounder, waiting to pounce on them when they press RETURN.  
#### "Press RETURN to continue"  
The user can control the movement from one display to the next by pressing the RETURN key (or, optionally but consistently, SPACE bar). He is informed by a message such as, "Press the RETURN key to go on to the menu." on the bottom line of the screen. (Delay loops are difficult to judge as to the proper duration, and become somewhat insulting to the intelligence of the user.) The actual prompt message should give some indication as to what will happen next, rather than simply saying "Press RETURN to continue."  
The educational software community has pretty much selected SPACE bar instead of RETURN to control movement: children were found to occasionally press RESET by accident on the older Apple II's and Apple II Plusses. Please be consistent in your choice of RETURN or SPACE bar, not only within a given program, but across your complete product line.  
Do not tell the user to "press any key." On the Apple II series computers, you cannot read every key by itself: RESET, SHIFT, CONTROL. We have also found in testing that new users, in particular, panic when asked to press any key. Over 80% of them will turn around and say, "but what key should I press?" In questioning them about this response, we discovered that they are quite convinced that even though the prompt implied all keys were OK to press, some could be dangerous. Of course, they were quite right.  
While you should not tell them to press any key, you may, in this specific case only, accept more than the key specified. Both RETURN and SPACE bar should be accepted, even though only one is prompted for: users grow used to using one or the other. You may optionally (and only in this specific case of using the key as a switch) want to accept most keys, so that a user striking out for SPACE bar and pressing V by accident will not be penalized. Do not accept ESCAPE instead of RETURN or SPACE bar.  
Displays with several input statements:  
- Movement from input to input is sequential: the user may move back and forth but not randomly skip around.
- Pressing the RETURN key automatically positions the user at the next input statement.
- Pressing CTRL-B automatically positions the user at the previous input statement. The prior response to the previous input will be displayed as that input's default.
- The last input on the display will normally ask if the user has completed all responses to her satisfaction.
- No input will be accepted without the user explicitly terminating it, usually with RETURN or CTRL-B. The fact that the user has used up all the spaces available in the field should not automatically move the user to the next question.  
#### Errors  
#### **Error Trapping**  
In most situations, user inputs must be checked for validity. Account numbers, employee numbers, and dates are just a few examples of items that should be checked to see if the data requested is on file or plausible. Numeric inputs should be screened for values too small or too large, if extreme values are invalid or potentially damaging to the program. An error message line should be provided in a consistent location toward the bottom of the display.  
Many types of errors can be circumvented through software design: If, in testing, you find users repeatedly making the same kind of errors, change the software.  
Make your program insensitive to upper/lower case when no distinction is necessary. Be particularly aware on Apple II programs: the new Apple IIe can generate lower-case characters. (Make sure you only  
transform characters: many of those obscure punctuation marks are often-used special characters on foreign keyboards.)  
Spaces should never be significant. Users look upon a space as a lack of a character, not as a character. Strip leading and trailing spaces, and intervening spaces too, when practical. For example, when prompting the user for the name of an existing file, should the user respond "door bell", first look for a literal match, then strip spaces, so that you can match with the user's original, but now forgotten, "doorbell".  
Likewise, do not refer to "the RETURN character", unless you are prepared to deliver an essay. Users steadfastly cling to their belief that RETURN is an action, not a character.  
Do not make commands position-dependent. For example, do not set up a stream of "parameters" such that if the user wishes to change the fourth parameter, she must type three commas to signify acceptance of the first three "default" parameters. If the meaning of the above sentence is not immediately clear, you have gotten the point.  
When a menu offers a set of choices, or the user is otherwise prompted to respond to a restricted set of options, then the program should recognize only the responses that are valid. Do not offer the user a menu of options, most of which cannot be used. If the user needs to select a file before deciding to Edit, Save, or Delete, let him know. Don't make him go down through a list, getting the same unenlightening message, "Option not currently valid."  
Enable only those keys you have informed the user you are enabling. Do not prompt: "Press ESCAPE to end, RETURN to continue..." and fail to announce that SPACE bar will eliminate this afternoon's files. The classic negative example of this is an early Apple text editor with a verified replace option. According to the manual (no instructions were displayed), R meant replace this occurrence, SPACE bar signified do not replace this occurrence. The actual code was such that any character with an ASCII value of 82 (R) or above caused a replacement, and any character with an ASCII value less than 82 caused a skip. Therefore, "[" would replace, "8" would not, "^" would replace, "," would not. Confusion yet reigns over that one.  
Having presented the rule, here is the exception: when using SPACE bar or RETURN as a switch ("Press RETURN to continue") you may want to accept all reasonable keys surrounding the intended target, so as to not penalize the user for poor aim.  
#### **Error Messages**  
Error messages should alert the user, identify the problem, and direct the user toward solutions. They should do so with a minimum of disruption: ring the bell once—the whole room doesn't need to know the user has yet again made a fool of himself.  
Remove the error message as soon as the user takes proper action to correct the condition. Users will believe you: as long as the message is there, they will continue to correct the problem. It has been shown that attempting to correct a problem that has already been corrected will usually result in a brand new problem.  
There are two classes of error messages that either intimidate or infuriate users.  
First, the computer-gibberish special:  
Application error #1463  
Error messages should not only provide information (in the user's native tongue, not computerese) as to what the error was, but should offer solutions as to what the user can do to correct the situation. A better message might be:  
You have not yet selected the name of the file you want to work from. Please type the name of one of the above files.  
Second, the it's-easier-to-flag-an-error-than-correct-it error:  
Data entry error: no comma after Aardvark  
Users soon catch on that if the computer/language/program (everything gets blamed) knows for a fact that there should be a comma after Aardvark, that the computer/language/program should supply said comma. Therefore, the computer/language/program is either really stupid or is lying.  
Your application should have a designated area of the screen where error messages are displayed. The usual location has come to be lines 23 and 24 of the display, but whether you choose these lines or not, make the location consistent. Long help instructions may require a different "page". Preserve the contents of display as much as possible while providing help, and once help is terminated, restore the context completely.