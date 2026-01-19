<!-- Chunk 270 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 243 -->
Use a **static textfield** for informational text (text not intended to be modified by users) in a dialog or window. Static text fields have two states: active and dimmed.  
When it provides an obvious user benefit, static text should be selectable. For example, a user should be able to copy an error message, a serial number, or an IP address to paste elsewhere. Figure 15-69 shows several examples of static text used to give information to users.  
<span id="page-321-1"></span>**Figure 15-69** Static text fields provide information to users  
![](images/_page_321_Picture_3.jpeg)  
![](images/_page_321_Picture_4.jpeg)  
<span id="page-321-2"></span><span id="page-321-0"></span>Static text fields in various standard fonts are available in Interface Builder. You can use system font, small system font, or mini system font, depending on the layout of your window. To create a static text field using Application Kit programming interfaces, use the NSTextField class.