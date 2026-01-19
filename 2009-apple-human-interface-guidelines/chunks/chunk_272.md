<!-- Chunk 272 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 530 -->
A **token field** is a control that creates a token out of input text. The token field control supports behavior similar to that of the address field in the Mail application.  
<span id="page-324-1"></span>Figure 15-72 shows various states of the token field control (no contextual menu support is shown).  
**Figure 15-72** A token field control in use  
![](images/_page_324_Picture_8.jpeg)  
#### Token Field Usage  
Use a token field control in a text input field (see "Text Input [Fields"](#page-321-0) (page 322) for more information about text input fields). As the user types in the text input field, the token field control invokes text completion after a delay you specify. When the user types the comma character or presses Return, the preceding text input is transformed into a token.  
A token is draggable and, if you add code to support a menu, displays a disclosure triangle that reveals a contextual menu when the user presses or clicks it. In this menu, you might offer more information about the token and ways to manipulate it. In Mail, for example, the token menu displays information about the token (the email address associated with the name) and items that allow the user to edit the token or add its associated information to Address Book, as shown in Figure 15-73.  
<span id="page-325-1"></span>**Figure 15-73** A token field control can display a contextual menu  
![](images/_page_325_Picture_3.jpeg)  
#### Token Field Specifications  
**Control sizes**: Token field controls fit inside the standard sizes of text input fields. The heights of token field controls are fixed for each size, and their lengths are determined by the length of the token. The height of a token field control is a few pixels less than the height of the text input field that contains it:  
● Regular size: 16 pixels high.  
● Small: 14 pixels high.  
● Mini: 11 pixels high.  
#### Token Field Implementation  
<span id="page-325-2"></span><span id="page-325-0"></span>Token field controls are available in Interface Builder. To create one using Application Kit programming interfaces, use the NSTokenField class.