---
chunk_index: 867
ref: "2fe8ce16bdca"
id: "2fe8ce16bdca255b66a07fb443ac507adaa4e40cb051351b318e553be7e19866"
slug: "full-document--character-keys"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/full_document.md"
kind: "markdown"
lines: [707, 724]
token_estimate: 568
content_sha256: "92d793fa57b5994e661e791a57797eec1fb1573c10b4154e388a9dd096d8e664"
compacted: false
heading_path: ["Character Keys"]
symbol: null
address: null
asset_path: null
---

# Character Keys

Character keys include keys for letters, numbers, and symbols, as well as the Space bar. If the user presses one of these keys while entering text, the corresponding character is added to the text. Other keys, such as the Enter, Tab, Return, Backspace, and Clear keys, are also sent to the application as character keys; the result of pressing one of these keys depends on the application and the context.

"

The Enter key tells the application that the user is through entering information in a particular area of the document, such as a field in an array. Most applications add information to a document as soon as the user types or draws it. However, the application may need to wait until a whole collection of information is available before processing it. In this case, the user presses the Enter key to signal that the information is complete. Both Enter and Return can be used to dismiss dialog and alert boxes. (See "Dialogs and Alerts.")

The Tab key is a signal to proceed: It signals movement to the next item in a sequence. Tab often implies an Enter operation before the Tab motion is perfonned.

The Return key is another signal to proceed, but it defines a different type of motion than Tab. A press of the Return key signals movement to the leftmost field one step down (just like a carriage return on a typewriter). Return can also imply an Enter operation before the Return operation. Both Return and Enter can also be used to dismiss dialog and alert boxes. (See "Dialogs and Alerts.")

During entry of text into a document, Tab moves the insertion point to the next tab stop, Retum moves it to the beginning of the next line, and Enter is ignored.

The Backspace key deletes text or graphics. Generally, Backspace deletes a selection without putting it in the clipboard, and to delete the character t.o the left of the insertion point. Using the clipboard and Backspace in text is described in "Text Editing."

The Clear key has the same effect as the Clear command in the Edit menu; that is, it removes the selection from the document without putting it in the Clipboard. Using this key is also explained in "Text Editing." Because not all Apple computers have Clear keys, no application should ever *require* use of the Clear key.