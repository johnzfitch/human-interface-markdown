---
chunk_index: 697
ref: "aaaf1be0a12a"
id: "aaaf1be0a12a59834f7b8ba7b8dcee7412e375520e0095f06b2b19e2259237b2"
slug: "chunk-038"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/chunks/chunk_038.md"
kind: "markdown"
lines: [1, 9]
token_estimate: 592
content_sha256: "3154f5221a221f1a7eeef673707cd750bfcc7bd347683e4bc01ea8891648e61c"
compacted: false
heading_path: []
symbol: null
address: null
asset_path: null
---

<!-- Chunk 38 | Source: 1986-07 Human Interface Guidelines (Second Beta Draft).pdf | Est. Tokens: 565 -->
Character keys include keys for letters, numbers, and symbols, as well as the Space bar. If the user presses one of these keys while entering text, the corresponding character is added to the text. Other keys, such as the Enter, Tab, Return, Backspace, and Clear keys, are also sent to the application as character keys; the result of pressing one of these keys depends on the application and the context.  
"  
The Enter key tells the application that the user is through entering information in a particular area of the document, such as a field in an array. Most applications add information to a document as soon as the user types or draws it. However, the application may need to wait until a whole collection of information is available before processing it. In this case, the user presses the Enter key to signal that the information is complete. Both Enter and Return can be used to dismiss dialog and alert boxes. (See "Dialogs and Alerts.")  
The Tab key is a signal to proceed: It signals movement to the next item in a sequence. Tab often implies an Enter operation before the Tab motion is perfonned.  
The Return key is another signal to proceed, but it defines a different type of motion than Tab. A press of the Return key signals movement to the leftmost field one step down (just like a carriage return on a typewriter). Return can also imply an Enter operation before the Return operation. Both Return and Enter can also be used to dismiss dialog and alert boxes. (See "Dialogs and Alerts.")  
During entry of text into a document, Tab moves the insertion point to the next tab stop, Retum moves it to the beginning of the next line, and Enter is ignored.  
The Backspace key deletes text or graphics. Generally, Backspace deletes a selection without putting it in the clipboard, and to delete the character t.o the left of the insertion point. Using the clipboard and Backspace in text is described in "Text Editing."  
The Clear key has the same effect as the Clear command in the Edit menu; that is, it removes the selection from the document without putting it in the Clipboard. Using this key is also explained in "Text Editing." Because not all Apple computers have Clear keys, no application should ever *require* use of the Clear key.