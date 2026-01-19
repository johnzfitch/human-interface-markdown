<!-- Chunk 161 | Source: 2001 Aqua Human Interface Guidelines (Preliminary).pdf | Est. Tokens: 303 -->
Help Tags are short messages that appear when the user leaves the pointer hovering over an interface element for a few seconds. When the mouse leaves the object, the tag vanishes. Use Help Tags to assist users in identifying the purpose of interface elements. Help Tags are designed to be a Carbon-compliant replacement for Balloon Help. Help Tag support is provided to Cocoa developers via the Application Kit, and they can define an object's Help Tag in Interface Builder.  
The text of the Help Tags should  
- name an object only if the name is relevant to its function and does not have a text label
- briefly describe, in as few words as possible, what the object does
- be state-independent—Help Tags always display the same wording, even when an object is dimmed  
For example, the Help Tag for a button labeled "Forward" in an email program might read "Send the selected message to someone else." This provides more detail than the button label, but does not repeat it, and it explains that a message must be selected to enable the button.  
It is not necessary for every object have a Help Tag. Don't provide them for common interface elements, menu items, or items that are self-explanatory or obvious.