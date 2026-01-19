<!-- Chunk 101 | Source: 2008-06 Apple Human Interface Guidelines.pdf | Est. Tokens: 799 -->
**Help tags** enable your application to provide basic help information for itsinterface elements without forcing the user to leave the primary interface.  
Help tags are short messagesthat appear when the user leavesthe mouse pointer hovering over an interface element for a few seconds (see Figure 6-12 for an example of a help tag). When the pointer leaves the object, the tag vanishes. If the mouse pointer is not moved, the operating system hides the help tag after about 10 seconds.  
<span id="page-80-0"></span>**Figure 6-12** A help tag  
![](images/_page_80_Picture_3.jpeg)  
The text of a help tag should briefly describe what an interface element does. If you find that you need more than a few words to describe the function of a control, you might want to reconsider the design of your application's user interface.  
Define help tags in Interface Builder, where they are called **tooltips**. Here are some guidelines to help you create effective help tag messages.  
- Use the fewest words possible. Try to keep your tags to a maximum of 60 to 75 characters. Because help tags are always on, it is important to keep your tag text unobtrusive—that is, *short*—and useful. A tag should present only one concept and that concept should be directly related to the interface element. Localization can lengthen the text by 20 to 30 percent, which is another good reason to keep the tag short.
- Don't put the interface element's name in the tag unless the name helps the user and isn't available onscreen. If an element isreferred to by name in the documentation and in the tag, make sure the names match.
- Describe only the element the mouse pointer hovers over.
- You can use a sentence fragment beginning with a verb, for example, "Restores default settings". You can also omit articles to limit the size of the tag. If the tag text is a complete sentence, end it with a period.
- Use help tags to provide functional information for controls that are unique to your application. Don't tag window controls, scroll bars, and other parts of the standard Mac OS X interface.
- You can create contextually sensitive help tags, but you don't have to; the same text can appear when an item is selected, dimmed, and so on. By describing what the interface element accomplishes, you may help the user understand the currentstate of the control even if the tag is applicable to allsituations.
- Write the help tag text in one of these ways, depending on the interface you're documenting:
- Describe what the user will accomplish by using the control. For example, "Add or remove a language from your list" or "Reduce red tint in the selected area". Most help tags can use this format.
- Give extra information to explain the results of the user's action. This kind of tag is most effective in an interface that already includes some instructional text, because the tag and the interface text work together to describe what the control does and how the user manipulates it.  
Define terms that may be unknown to the user. This kind of tag should be used only if the interface already contains instructions to the user.  
User Assistance **81**  
#### **CHAPTER 6**  
Using Mac OS X Technologies