---
chunk_index: 511
ref: "7682c96b20f7"
id: "7682c96b20f7b9e8f74122c7f513225f9881d4101e549f496fe5ead020d34267"
slug: "full-document--how-to-ask-confirmation-questions-safely"
path: "marker/1985 Apple II Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [881, 900]
token_estimate: 539
content_sha256: "a5bce1c8ec913733f8302e334d196bba38aff9b287d02ad7cf1a3ba34230300b"
compacted: false
heading_path: ["How to Ask Confirmation Questions Safely"]
symbol: null
address: null
asset_path: null
---

# How to Ask Confirmation Questions Safely

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