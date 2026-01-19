<!-- Chunk 190 | Source: 2011 iOS Human Interface Guidelines.pdf | Est. Tokens: 562 -->
iOS provides the buttons described in Table 7-5 for use in table rows and other elements.  
**Table 7-5** Standard buttons for use in table rows and other UI elements  
| Button | Name             | Meaning                                                                                                                                                                    |
|--------|------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|        | ContactAdd       | Display a people picker to add a contact to an item.                                                                                                                       |
|        | DetailDisclosure | Display a new view that contains details about the current item.                                                                                                           |
|        | Info             | Flip to the back of the view to display configuration options or more information.<br>Note that the Info button is also available as a light-colored "i" in a dark circle. |  
These buttons should be used according to their defined meaning, as with all standard buttons and icons. In other words, avoid choosing a button based on its appearance, without regard for its documented meaning. For a discussion of the reasons why it's important to use these buttons correctly, see "Use UI [Elements](#page-54-1) [Consistently"](#page-54-1) (page 55).  
Although the detail disclosure button is usually used in table rows, it can be used elsewhere. For more information about this button, see "Detail [Disclosure](#page-125-0) Button" (page 126). iOS also provides a set of controls for use in table rows only; for more information about these, see ["Table](#page-106-0) View" (page 107).  
For more information on using the ContactAdd and Info buttons in your app, see the documentation for UIButtonType in *UIButton Class Reference*. For information on using the DetailDisclosure button in your app, see UITableViewCellAccessoryDetailDisclosureButton in *UITableViewCell Class Reference*.)  
#### **CHAPTER 7**  
iOS UI Element Usage Guidelines