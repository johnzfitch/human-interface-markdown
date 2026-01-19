---
chunk_index: 4157
ref: "4aee2a7d8e6f"
id: "4aee2a7d8e6f44c782704b39cdce1f1d5f02d347c4468b0d7c8556ad58f9bedc"
slug: "full-document--choosing-the-button-s-image-or-label"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [2653, 2670]
token_estimate: 587
content_sha256: "b17bdbd65a08e9c93267cb804b6c25da43e02ee254d66346dd38d554873bcf90"
compacted: false
heading_path: ["7! *Controls*","Implementing Buttons","Choosing the Button's Result","**Choosing the Button's Image or Label**"]
symbol: null
address: null
asset_path: null
---

#### **Choosing the Button's Image or Label**

A button's label should say, in a succinct shorthand, what action it causes the application to take. Even when a button purports to label a state (such as AM or PM), users are apt to think of it not as the current state, but as the state that will be set if the button is clicked. In other words, they're liable to interpret it as an action. An On button, for example, is more likely to be interpreted to mean "Press this to tum something on" than "This is now on."

It's best, therefore, to use images and highlighting to show the current state, and reserve the button's label as a brief statement of what the button does. Buttons that do label a state, such as a button that switches between AM and PM, should be used only where what they label is clearly visible. For example, AMIPM buttons can be used alongside a digital representation of the time, but they can't stand alone. These and other two-state buttons are shown in the figure in the following section.

**Note:** Make sure that the button clearly looks like either an action button or a two-state button. It's confusing to the user to see a two-state button that doesn't clearly have two states, or an action button that doesn't look like it perfonns an action.

You should always dim the label of a button (using gray text) whenever pushing the button will have no effect. A dimmed button is completely disabled-pushing it shouldn't cause it to highlight, push in, or change in any other way.

Button labels should be capitalized like menu commands: The first and last words begin with uppercase letters and the words between are capitalized as they would be in a title. Like menu commands, buttons that always bring up a panel (unless it's a warning panel) should have three dots ( ... ) at the end of the label.

When an action button can be chosen using the Return key, the button should contain the Return symbol to the right of its label, as shown below at the left. However, when pressing Return won't choose the button-for example, when the button's window isn't the key window-the Return symbol should disappear from the button (as shown at the right, below). Removing the Return symbol helps avoid user confusion over whether pressing Return will work.

![](images/_page_151_Figure_2.jpeg)

![](images/_page_151_Figure_3.jpeg)