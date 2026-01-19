---
chunk_index: 222
ref: "3c9a9929a0c0"
id: "3c9a9929a0c081a34353571115a66cde60781027a1535f7e4b4cd722d715bedc"
slug: "full-document--keyword-matching-during-input-the-disambigua"
path: "marker/1982 Apple IIe Design Guidelines/full_document.md"
kind: "markdown"
lines: [831, 906]
token_estimate: 1734
content_sha256: "abafcae8b0e51317dd086a5308876aed6d8d22dcfe6b016b001042b294597eae"
compacted: false
heading_path: ["Keyword Matching During Input: the Disambiguator"]
symbol: null
address: null
asset_path: null
---

# Keyword Matching During Input: the Disambiguator

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