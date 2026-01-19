---
chunk_index: 831
ref: "9a8b857ef1e0"
id: "9a8b857ef1e0a03fc561e4c4a78e5c581b4cfa985c30a56aee4f7fec8ed796e3"
slug: "full-document--forgiveness"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/full_document.md"
kind: "markdown"
lines: [410, 421]
token_estimate: 455
content_sha256: "6e5599d5d88f85015cb0a4e68e72138d2289cf9d68a089b398bfc82ce66d97bb"
compacted: false
heading_path: ["Consistency","See-and-Point versus Remember-and-Type","Forgiveness"]
symbol: null
address: null
asset_path: null
---

### Forgiveness

Control, dialog, ease of learning, direct manipulation, and feedback all encourage exploration. Even though users demand full documentation with their software, they don't really want to read manuals. (Do you?) They'd rather figure out how a system works the same way they learned to do things when they were children: by exploration, with lots of action and lots of feedback. Applications like the Finder and MacPaint have changed people's expectations of how computers are learned and used, and the most successful applications are the ones that follow up on their promise.

"Permission to explore" means that applications allow the user to do anything reasonable. Let the users know that they can't "break" anything and that they can always cancel risky operations. The user, not the system, decides what to do next. Event—driven programming means that an application cannot predict the sequence of tasks it will be expected to perform. Programs must determine, from moment to moment, what to do by looking for input from the user.

Now and then, computer users, like other mortals, make mistakes or explore a bit farther than they really want to. A computer system should be forgiving, always warning users when they're entering risky territory, then allowing them either to back gracefully away from the situation—or to plunge ahead, knowing exactly what the consequences are. Even actions that are not particularly risky should be reversible. Tell the users about any exceptions to this pattern.

Error messages should appear infrequently. If the user is constantly subjected to a barrage of error messages, something is wrong with the design of the program. If your application

includes on-line help, you might want to design it so that error conditions automatically trigger the help system.