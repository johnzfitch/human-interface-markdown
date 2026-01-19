<!-- Chunk 87 | Source: 1985 Apple II Human Interface Guidelines.pdf | Est. Tokens: 562 -->
| Character | Command |
|-----------|---------|
| P         | Print   |
| S         | Save    |  
1/15/85 Tognazzini  
| Character | Command                          |
|-----------|----------------------------------|
| В         | Bold                             |
| С         | Copy                             |
| D         | Delete                           |
| E         | Edit                             |
| F         | Forward Delete                   |
| * H       | Left Arrow                       |
| * I       | Tab                              |
| * J       | Down Arrow                       |
| * K       | Up Arrow                         |
| L         | Begin or End Underline           |
| * M       | Carriage Return                  |
| P         | Print the contents of the screen |
| S         | Save                             |
| * U       | Right Arrow                      |
| V         | Paste                            |
| X         | Cut                              |
| Z         | Undo                             |
| * [       | Escape                           |  
COMMANDS 93  
The most basic reason to group commands is to break up a menu so it's easier to read. Commands grouped for this reason are logically related, but independent. Commands that are actions are usually grouped this way, such as Cut, Copy, Paste, and Clear in the Edit menu.  
Attribute commands that are interdependent are grouped to show this interdependence. Two kinds of attribute command groups are mutually exclusive groups and accumulating groups.  
In a mutually exclusive attribute group, only one command in the group is in effect at the same time. The command that's in effect is preceded by a check mark. If the user chooses a different command in the group, the check mark is moved to the new command. An example is the Font menu in MacWrite; no more than one font can be in effect at a time.  
In an accumulating attribute group, any number of attributes can be in effect at the same time. One special command in the group cancels all the other commands. An example is the Style menu in MacWrite: the user can choose any combination of Bold, Italic, Underline, Outline, or Shadow, but Plain Text cancels all the other commands.