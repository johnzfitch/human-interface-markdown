---
chunk_index: 864
ref: "cb39aef25364"
id: "cb39aef2536400d49a37ce7f8566e27a45bed0657958f2c2782c9a90a3e6da13"
slug: "full-document--double-clicking"
path: "marker/1986-07 Human Interface Guidelines (Second Beta Draft)/full_document.md"
kind: "markdown"
lines: [668, 679]
token_estimate: 563
content_sha256: "e16dcd4a62da2365edbddf79098d7629031cec890db878396d2a32ded462a9a7"
compacted: false
heading_path: ["The Pointing Device","What About the Cursor? (a Digression)","Double Clicking"]
symbol: null
address: null
asset_path: null
---

### Double Clicking

As stated already, double clicking involves a second click that follows immediately after the end of a first click. If the two clicks are close enough to one another in terms of time (as set by the user in the Control Panel) and of screen location, then they constitute a double click. Its most common use is as a shortcut way (but *never* the only way) to perform an action. For example, clicking twice on an icon is a faster way to open it than selecting it and choosing Open; clicking twice on a word to select it is faster than dragging through it.

Some applications support selection by double clicking and triple clicking. As always with multiple clicks, the second click extends the effect of the first click, and the third click extends the effect of the second click. For example, in a text-oriented application, the first click selects an insertion point, the second click might select the whole word containing the insertion point, and the third click might select the whole sentence. In a graphics application, the first click might select a single object, and double and triple clicks might select successively larger sets of objects.

Three clicks is probably the practical limit, and even that is difficult for many people. If an application defines the effect only of single and double clicking, a third click should have no effect. If triple clicking is defined, then the fourth click should have no effect.

Double clicking is a shortcut for those users physically able to use it. For example, users with a little experience like to be able to launch an application by double clicking on its icon rather than clicking on it to select it and then selecting Open from the File menu. Again, double clicking should never be the *only* way to accomplish a task. Many novice users, children, and disabled people have a hard time double clicking.

To allow the software to distinguish efficiently between single clicks and double clicks on objects that respond to both, an operation invoked by double clicking an object must be an enhancement, superset, or extension of the feature invoked by single clicking that object. Triple clicking is also possible; it should similarly represent an extension of a double click.