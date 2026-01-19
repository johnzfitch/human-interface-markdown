<!-- Chunk 260 | Source: 2001 Aqua Human Interface Guidelines.pdf | Est. Tokens: 457 -->
<span id="page-221-2"></span>Help tags are short messages that appear when the user leaves the pointer hovering over an interface element for a few seconds. When the pointer leaves the object, the tag vanishes. Use help tags to assist users in identifying the purpose of interface elements. Help tags are designed to be a replacement for help balloons. You can define an object's help tag in Interface Builder for Carbon and Cocoa applications.  
The text of the help tags should  
- name an object only if the name is relevant to its function and does not have a text label
- briefly describe what the object does
- be state-independent—help tags always display the same wording, even when an object is dimmed  
For example, the help tag for a button labeled "Forward" in an email program might read "Send the selected message to someone else." This provides more detail than the button label, but does not repeat it, and it explains that a message must be selected to enable the button.  
It is not necessary for every object have a help tag. Don't provide them for common interface elements, menu items, or items that are self-explanatory or obvious.  
If necessary, Carbon developers can implement expanded help tags—text that replaces the original help tag and that further explains the control's function. Users display an expanded help tag by pressing the Command key. Not every tag needs an expanded state.  
**Figure 13-1** A help tag and an expanded help tag  
![](images/_page_222_Picture_9.jpeg)  
<span id="page-222-1"></span>![](images/_page_222_Picture_10.jpeg)  
Help tags should always appear in the same place, regardless of the pointer location. The default position for help tags in Carbon applications is below the control, centered horizontally (if necessary, this position can be changed on a per-tag basis).