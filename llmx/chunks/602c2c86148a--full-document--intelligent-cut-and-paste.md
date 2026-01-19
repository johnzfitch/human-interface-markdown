---
chunk_index: 591
ref: "602c2c86148a"
id: "602c2c86148a896de7062187ab61bb88184da069c3f7e3684cae8d67fa5643a0"
slug: "full-document--intelligent-cut-and-paste"
path: "marker/1985 Apple II Human Interface Guidelines/full_document.md"
kind: "markdown"
lines: [1952, 1980]
token_estimate: 541
content_sha256: "a69870792b377c7f16ee434e842b1c8aa7580a6009fce796b06df5145309c18d"
compacted: false
heading_path: ["Intelligent Cut and Paste"]
symbol: null
address: null
asset_path: null
---

# Intelligent Cut and Paste

An application that lets the user select a word by double-clicking should also see to it that the user doesn't regret using this feature. The only way to do this is by providing "intelligent" cut and paste.

To understand why this feature is necessary, consider the following sequence of events in an application that doesn't provide it:

- 1. A sentence in the user's document reads: "Returns are only accepted if the merchandise is damaged." The user wants to change this to: "Returns are accepted only if the merchandise is damaged."
- 2. The user selects the word "only" by double-clicking. The letters are highlighted, but not either of the adjacent spaces.
- The user chooses Cut, clicks just before the word "if", and chooses Paste.
- 4. The sentence now reads: "Returns are accepted onlyif the merchandise is damaged." To correct the sentence, the user has to remove a space between "are" and "accepted", and add one between "only" and "if". At this point he or she may be wondering why Apple computers are supposed to be easier to use than other computers.

If an application supports intelligent cut and paste, the rules to follow are:

- If the user selects a word or a range of words, highlight the selection, but not any adjacent spaces.
- When the user chooses Cut, if the character to the left of the selection is a space, discard it.
- When the user chooses Paste, if the character to the left of the current selection isn't a space, add a space. If the character to the right of the current selection isn't a punctuation mark or a space, add a space. Punctuation marks include the period, comma, exclamation point, question mark, apostrophe, colon, semicolon, and quotation mark.

This feature makes more sense if the application supports the full definition of a word (as detailed above under "Selecting a Word"), rather than the definition of a word as anything between two spaces.

These rules apply to any selection that's one or more whole words, whether it was chosen with a double-click or as a range selection.

Figure 23 shows some examples of intelligent cut and paste.

1/15/85 Tognazzini

TEXT EDITING

105