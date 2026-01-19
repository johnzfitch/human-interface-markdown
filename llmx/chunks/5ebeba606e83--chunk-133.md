---
chunk_index: 3749
ref: "5ebeba606e83"
id: "5ebeba606e83ff28d4b987a460455a16cf443507624084441de6ed4ecba05ef9"
slug: "chunk-133"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_133.md"
kind: "markdown"
lines: [1, 10]
token_estimate: 318
content_sha256: "250882f276d094c50340353a3a745c5b72fb353fef23642d245e34227ec2f99e"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

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