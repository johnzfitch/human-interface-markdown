---
chunk_index: 153
ref: "7ff33a1de999"
id: "7ff33a1de9996402eb9fe2d7128d900013b8b1e536824719c47c8ed9d43214ed"
slug: "chunk-038--error-messages"
path: "marker/1982 Apple IIe Design Guidelines/chunks/chunk_038.md"
kind: "markdown"
lines: [71, 82]
token_estimate: 482
content_sha256: "dd37918eb6b1150c51a389f04bf4c3e1df91e7f1f51b73f0198b25f0056e2b77"
compacted: false
heading_path: ["\"Press RETURN to continue\"","Errors","**Error Trapping**","**Error Messages**"]
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