<!-- Chunk 273 | Source: 2002 Aqua Human Interface Guidelines.pdf | Est. Tokens: 651 -->
- Describe what the user will accomplish by using the control. Examples: "Add or remove a language from your list." "Reduce red tint in the selected area." Most help tags can use this format.
- Give extra information to explain the results of the user's action. This kind of tag is most effective in an interface that already includes some instructional text, because the tag and the interface text work together to describe what the control does and how the user manipulates it.
- Define terms that may be unknown to the user. This kind of tag should be used only if the interface already contains instructions to the user.
- You can create contextually sensitive help tags but you don't have to; the same text can appear when an item is selected, dimmed, and so on. By describing what the item accomplishes, you may help the user understand the current state of the control even if the tag is applicable to all situations.
- Use help tags to provide functional information for controls that are unique to your application. Don't tag window controls, scroll bars, and other parts of the standard Mac OS X interface.
- Don't put the item's name in the tag unless the name helps the user and isn't available onscreen. If an item is referred to by name in the documentation and in the tag, make sure the names match.
- You can use a sentence fragment beginning with a verb, for example, "Restores default settings." You can also omit articles to limit the size of the tag. If the tag text is a complete sentence, end it with a period.
- Describe only the item the user points to.
- Use help tags primarily to provide necessary information, rather than incidental tips.
- If you implement an expanded tag to add another layer of information, don't repeat the text in the original tag. An expanded tag should do one of the following:
- More fully explain or describe the results of the action described in the small help tag.  
*Help tag:* Shuffles the play order.  
*Expanded tag:* Plays the current list of songs in random order.  
■ Explain when or why the user would do the action described in the original tag.  
<span id="page-240-2"></span>*Help tag:* Creates folder on player. *Expanded tag:* Creates folders to help you organize music on the player.  
If the main tag is an explanation or a definition that helps supplement instructions in the interface, you're less likely to need an expanded tag.  
<span id="page-240-3"></span>Carbon developers should see *Inside Mac OS X: Providing Help Tags in Carbon,* available on the Mac OS X developer documentation website, for implementation information.