<!-- Chunk 271 | Source: 2002 Aqua Human Interface Guidelines.pdf | Est. Tokens: 460 -->
<span id="page-237-4"></span>Help tags are short messages that appear when the user leaves the pointer hovering over an interface element for a few seconds. When the pointer leaves the object, the tag vanishes. Use help tags to assist users in identifying the purpose of interface elements. You can define an object's help tag in Interface Builder for Carbon and Cocoa applications.  
The text of the help tags should  
- name an object only if the name is relevant to its function and does not have a text label
- briefly describe what the object does
- reflect the current state of the interface item or be state-independent. You can check the state of the item (dimmed, selected, and so on) before displaying the tag.  
For example, the help tag for a button labeled "Forward" in an email program might read "Send the selected message to someone else." This provides more detail than the button label, but does not repeat it, and it explains that a message must be selected to enable the button.  
It is not necessary for every object to have a help tag. Don't provide them for common interface elements, menu items, or items that are self-explanatory or obvious.  
If necessary, Carbon developers can implement expanded help tags—text that replaces the original help tag and that further explains the control's function. Users display an expanded help tag by pressing the Command key. Not every tag needs an expanded state.  
**Figure 14-1** A help tag and an expanded help tag  
![](images/_page_238_Picture_6.jpeg)  
<span id="page-238-1"></span>![](images/_page_238_Picture_7.jpeg)  
Help tags should always appear in the same place, regardless of the pointer location. The default position for help tags in Carbon applications is below the control, centered horizontally (if necessary, this position can be changed on a per-tag basis).