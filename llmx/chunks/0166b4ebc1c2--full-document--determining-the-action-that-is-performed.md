---
chunk_index: 4001
ref: "0166b4ebc1c2"
id: "0166b4ebc1c2d47ec7d242e733684af85faaa65eefb6c84ad2943ff161ff478e"
slug: "full-document--determining-the-action-that-is-performed"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/full_document.md"
kind: "markdown"
lines: [929, 941]
token_estimate: 489
content_sha256: "51971d5c00b380c47b4cf1046ac59e7fff73ff4197ba54e682bd98aed4910298"
compacted: false
heading_path: ["*Introduction*","**Creating Application-Specific Keyboard Alternatives**","**Choosing the Character**","**Determining the Action that Is Performed**"]
symbol: null
address: null
asset_path: null
---

#### **Determining the Action that Is Performed**

A keyboard alternative should almost always accomplish exactly the same thing as the mouse action. Even slight variations between a mouse action and its keyboard alternative run counter to the principle that every keyboard operation must match a corresponding mouse operation. However, in some cases it's acceptable to have a keyboard alternative do just a bit more than the mouse operation. These cases are rare and often go unnoticed by users because the difference is both subtle and intuitive. The keyboard alternative simply does what the user wants, while also doing one or both of the following:

- Reducing the number of clicks or keystrokes the user needs to perform
- Eliminating the need to switch from the keyboard to the mouse and back again

For example, the Edit application has a Find panel that's brought up by the Find Panel menu command or its Command-fkeyboard alternative. Usually, the panel stays up until the user explicitly closes it, since it can be used many times in a row. However, a user who is concentrating on entering text often wants to find a word in a document but then doesn't want to use the Find panel for a while.

Edit accounts for both kinds of use by automatically closing the panel if the user is not likely to use the Find panel immediately. It assumes that this is the case if the user doesn't use the .mouse to conduct the search (instead, using Command-f to bring up the panel, and starting the search by pressing Return). Edit's behavior lets users find a word using a minimum number of actions, and relieves them of having to switch to the mouse to bring the document window back in front of the Find panel.

In general, you should start with all keyboard alternatives the same as their associated mouse action. In the rare case when a keyboard alternative should be different from its associated mouse action, the need becomes clear through everyday use.