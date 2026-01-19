---
chunk_index: 3634
ref: "7ecc5835cd41"
id: "7ecc5835cd415dc5f14e5c28a05ec3195240e6f2786ffd4fc109753dc4c7cf39"
slug: "chunk-048--determining-the-action-that-is-performed"
path: "marker/1993 NeXTSTEP User Interface Guidelines - Release 3/chunks/chunk_048.md"
kind: "markdown"
lines: [19, 25]
token_estimate: 490
content_sha256: "390a0731529e16dcbef37634c866065e46db023d31f35ae00cd2fcd0fe5675bb"
compacted: false
heading_path: ["**Choosing the Character**","**Using the Alternate Key·**","**Determining the Action that Is Performed**"]
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