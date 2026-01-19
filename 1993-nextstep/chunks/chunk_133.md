<!-- Chunk 133 | Source: 1993 NeXTSTEP User Interface Guidelines - Release 3.pdf | Est. Tokens: 292 -->
Wherever possible, the first word of an action command should be a verb, so the command reads like a short imperative sentence for the action it performs. Examples include Hide, Open, Save As, and Revert to Saved.  
Some menu commands have different results, depending on the application's state. The name of such a command should change so that it always describes what the command will do. The clearest way to do this is to change the command's verb. Some examples of good names follow:  
| First State | Second State | Notes                                        |
|-------------|--------------|----------------------------------------------|
| Show Ruler  | Hide Ruler   |                                              |
| Show Grid   | Hide Grid    |                                              |
| Use Grid    | Ignore Grid  | Don't use Grid On and Grid Off.              |
| Bold        | Unbold       | Bold is treated like a verb in this command. |  
Avoid using two menu commands instead of changing the menu command's name. For example, you shouldn't have a Show Ruler command followed by a Hide Ruler command, where one of the commands is always disabled.