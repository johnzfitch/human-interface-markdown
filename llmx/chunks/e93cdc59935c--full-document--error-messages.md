---
chunk_index: 226
ref: "e93cdc59935c"
id: "e93cdc59935c199031a0d9020725ad35db00bf1440ba66d94650950062d6c55c"
slug: "full-document--error-messages"
path: "marker/1982 Apple IIe Design Guidelines/full_document.md"
kind: "markdown"
lines: [949, 972]
token_estimate: 479
content_sha256: "685db584ca6de08ad61e7488aff96b7dff01b57a9b6d6cae1edb534d5eba5b73"
compacted: false
heading_path: ["Keyword Matching During Input: the Disambiguator","\"Press RETURN to continue\"","Errors","**Error Messages**"]
symbol: null
address: null
asset_path: null
---

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