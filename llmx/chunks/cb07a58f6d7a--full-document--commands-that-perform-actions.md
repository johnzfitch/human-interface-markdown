---
chunk_index: 4116
ref: "cb07a58f6d7a"
id: "cb07a58f6d7a023da8a1a6d437002fb57f0ab80028d756c382122a0c12a442f8"
slug: "full-document--commands-that-perform-actions"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [2093, 2107]
token_estimate: 301
content_sha256: "d94f3365a68204ab7c0e983c0fe6e827940f6feb0eda24574d5052459150244c"
compacted: false
heading_path: ["5 *Panels*","**Commands that Perform Actions**"]
symbol: null
address: null
asset_path: null
---

## **Commands that Perform Actions**

Wherever possible, the first word of an action command should be a verb, so the command reads like a short imperative sentence for the action it performs. Examples include Hide, Open, Save As, and Revert to Saved.

Some menu commands have different results, depending on the application's state. The name of such a command should change so that it always describes what the command will do. The clearest way to do this is to change the command's verb. Some examples of good names follow:

| First State | Second State | Notes                                        |
|-------------|--------------|----------------------------------------------|
| Show Ruler  | Hide Ruler   |                                              |
| Show Grid   | Hide Grid    |                                              |
| Use Grid    | Ignore Grid  | Don't use Grid On and Grid Off.              |
| Bold        | Unbold       | Bold is treated like a verb in this command. |

Avoid using two menu commands instead of changing the menu command's name. For example, you shouldn't have a Show Ruler command followed by a Hide Ruler command, where one of the commands is always disabled.