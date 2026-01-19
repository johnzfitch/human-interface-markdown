---
chunk_index: 371
ref: "e4e7b4defc78"
id: "e4e7b4defc786ab5b504faf5ef580634f26b6f76b575ceaf79dea5e330bcc40a"
slug: "chunk-040"
path: "marker/1985 Apple II Human Interface Guidelines/chunks/chunk_040.md"
kind: "markdown"
lines: [1, 11]
token_estimate: 553
content_sha256: "45e1cd34f93177a0ee5526d899dc53bbf4574f0ba0ade0f894d6f14a48e92343"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 40 | Source: 1985 Apple II Human Interface Guidelines.pdf | Est. Tokens: 529 -->
One of the problems with confirmation questions is that the user's response eventually becomes entirely automatic. The danger in this is that when you really need confirmation of a dangerous situation, the user idly selects Y Return, just as always. The following guidelines will help overcome that problem:  
- 1. Do not ask for confirmation when it is not needed--most important.
- 2. If destruction is involved, default to the least-destrutive option.
- 3. Do not ring the bell for confirmation questions asked every time: save the bell for unusual cirmstances. 4. Place the default answer first in the list, unless an error in the user's choice can result in catastrophic damage.  
The user's pattern of use will thus be that accepting the default means a simple Return, and rejecting the default means Right-Arrow Return. This automatic pattern will always make the computer work, except in one case:  
This disk has active files. Reformatting will destroy them.  
Do you want to re-format and destroy all files? Destroy <CANCEL>  
In this case, the user must break normal pattern and can only destroy what may be one month's work by pressing <u>Left-Arrow</u> Return, or typing a letter other than Y or N. (This is the reason for not allowing wrap-around, which would let the user press the Right-Arrow key-the "habit key".  
There is one cardinal rule that must be followed to make this sheme work: Do not harrass the user. If there is an activity which must be habitually handled, you must allow the user to fail. Excessive prompting leads people to totally ignore the meaning of every prompt in their efforts to escape from your clutches. Then, when something really important arises, they will bang their way through it without even looking at the words, destroying exactly what you were trying to keep them from destroying.  
These kinds of difficulties arise out of the most altruistic of motives; they will show up when you begin to do long-term testing with people from your target audience. Get your program into test sites as early as possible, and listen to user-feedback on just these sorts of issues.