---
chunk_index: 4156
ref: "413de8fafb25"
id: "413de8fafb25443ddaf91b47e6d348517abad9c1ef1d010e2cbc254df252dad8"
slug: "full-document--choosing-the-button-s-result"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [2639, 2652]
token_estimate: 524
content_sha256: "cc971dddb42e2900791d1cd10a9fa904211716e0bcfdbf7438ed3879cd483635"
compacted: false
heading_path: ["7! *Controls*","Implementing Buttons","Choosing the Button's Result"]
symbol: null
address: null
asset_path: null
---

#### Choosing the Button's Result

A one-state (action) button shouldn't change the action it performs. Although it's sometimes tempting to alter the action with the application's state—to switch between Erase and Restore, for example—it's best to provide a different button for each action and disable those that aren't operable. This lets the user safely click in the accustomed place without having to consider which state the application is in. However, it's acceptable for buttons that perform time-consuming actions to have a stop state, as described in "Implementing Stop Buttons," later in this chapter.

One-state buttons are generally labeled with a verb or verb phrase (such as Find), but occasionally they have only a graphic image (such as the arrowhead in a scroll bar button). Labeling conventions are discussed in "Choosing the Button's Image or Label," below.

Two-state buttons should never perfonn actions, although the characteristic they affect might result in some visible change. For example, an inspector for a graph might have a set of radio buttons that control the graph's type (line, bar, and so on). Clicking one of the buttons resets the graph's type, which in tum results in the graph being redrawn. However, it wouldn't be acceptable for the radio button to, for example, create a second graph of the new type.

Ideally, as soon as the user clicks a two-state button, the visible consequences (if any) should be shown immediately. However, that's not always practical, as when changing the characteristic takes a long time or isn't easy to reverse. For example, if changing the type of a graph takes a long time, then the application might wait for the user to click a Redraw Graph button before redrawing the graph.

However, whether or not a two-state button's associated characteristic changes immediately, the button's appearance always changes immediately, as described in "Changing the Button's Appearance during a Click," later in this chapter.

Buttons with more than two states aren't recommended: It's very difficult to convey their result to the user.