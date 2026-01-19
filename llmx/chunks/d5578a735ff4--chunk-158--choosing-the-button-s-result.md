---
chunk_index: 3789
ref: "d5578a735ff4"
id: "d5578a735ff45021ffc18475f8fe659041e599ba2283b3e34ed3b6acc14e1b62"
slug: "chunk-158--choosing-the-button-s-result"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_158.md"
kind: "markdown"
lines: [7, 13]
token_estimate: 525
content_sha256: "dea341811f308ff1dafaadd5b6d833dc9b856e1a597267233c36957b21023256"
compacted: false
heading_path: ["Choosing the Button's Result"]
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