<!-- Chunk 40 | Source: 1980 Lisa UI Standards.pdf | Est. Tokens: 238 -->
The Undo command undoes the last command you issued  
Undo is a command, thus a second Undo undoes the first
Undo. Undo applies to all edit menu commands, and in later releases
it will apply to more and more commands until eventually it will
apply to all.  
Simply changing what is selected does not count as a command. Therefore, after a command is invoked, the user can Undo until another command is invoked  
A series of keystrokes on the keyboard including printing characters, RETURN, TAB, all CODE-shifted characters, and all variations of BACKSPACE, with no intervening changes of selection and no command invocations , is considered a single command for Undo purposes. For example, if a word is selected, and the user types over it (even if he types more backspaces than characters) and then he invokes Undo in that folder, then the text is restored to its condition before the first character /as typed, and the original word is again selected.