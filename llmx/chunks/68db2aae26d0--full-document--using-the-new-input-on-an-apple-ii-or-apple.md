---
chunk_index: 220
ref: "68db2aae26d0"
id: "68db2aae26d0500c7cfa35e86d0233d830b190bcddfa8c4f38cea484e2b20f77"
slug: "full-document--using-the-new-input-on-an-apple-ii-or-apple"
path: "marker/1982 Apple IIe Design Guidelines/full_document.md"
kind: "markdown"
lines: [749, 808]
token_estimate: 603
content_sha256: "c6ff88785bbade87ada2a489d0e6adf49801de3b548b05bd6ee68582c4b79450"
compacted: false
heading_path: ["The (Pascal) Solid-box Cursor","Apple III Series","Notes","Using the New Input on an Apple II or Apple III Series Computer"]
symbol: null
address: null
asset_path: null
---

#### Using the New Input on an Apple II or Apple III Series Computer

The program input statement asks the user for information by displaying a verbal prompt. Prompts should terminate in a colon (:) or greater-than sign (>) if a statement, a question-mark (?) if a question. The prompt is followed by 2 spaces on an 80-column display, 1 space on a 40-column display.

A default answer may be displayed, with the cursor following, in which no field length is denoted. If there is no default response offered, or the default is rejected by the user, the program can display a finite input field with a series of periods (standard character set) or "ghost" underlines (hi-res character set). The latter character is essentially a shortened underline with every other dot turned off.

The specification of the number of spaces between the prompt and the input field is quite important: users can become confused as to where their answer begins. If all programs adhere to one space with 40 column displays, 2 spaces with 80 column displays, the users will know whether they have inadvertently typed a leading space or not. (As a separate issue, leading and trailing spaces should be routinely stripped off, unless they are specifically needed.)

Keystroke errors are best trapped immediately: if you are accepting a decimal number, do not accept a letter such as "A" or "B".

Here is the example of the input which is taught on APPLE PRESENTS...APPLE for the Apple IIe:

What is a "drift"?

A whole lot of cattle\_

(Consider the underline to be blinking — the printer was not able to quite capture the effect.) The problem presented is to change the answer to read:

> A herd of cattle

To edit the response, the user first moves back to the end of the word "lot," using the LEFT ARROW. It looks like this:

> A whole lot of cattl\_e

> A whole lot of catt\_le

> A whole lot of cat\_tle

> A whole lot of ca\_ttle

> A whole lot of c\_attle

> A whole lot of \_cattle

> A whole lot of \_ cattle

> A whole lot o\_f cattle

> A whole lot \_of cattle

> A whole lot\_ of cattle

The user is next instructed to press the DELETE key several times, until the words "whole lot" have been deleted:

A - of cattle

Next, the user types the word "herd":

> A h = of cattle

A he\_ of cattle

> A her \_ of cattle

> A herd\_ of cattle

Finally, the user can press RETURN to accept the entire response:

) A herd of cattle