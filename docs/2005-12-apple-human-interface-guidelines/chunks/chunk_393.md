<!-- Chunk 393 | Source: 2005-12 Apple Human Interface Guidelines.pdf | Est. Tokens: 330 -->
A standard alert dialog like the one provided by Carbon or Cocoa is shown in Figure 15-9.  
**Figure 15-9** A standard alert example  
![](images/_page_290_Picture_7.jpeg)  
Although the standard alert dialogs provided by the Carbon and Cocoa take care of the general layout for you, there are a few details you are responsible for:  
- Make sure that the version of your application icon you use in the alert is 64 x 64 pixels.
- Make sure to include *both* the main message text and the informative text. An alert with only message text is not a complete alert and typically is not very useful to the user.
- Always put the action button in the bottom-right corner of the alert. This is the button that completes the action that the user initiated before the alert was displayed. Remember that the action button is not always the default button as it is in this example. In dangerous situations, the default button may be Cancel but, it should not be the action button and should not be located in the action button position.  
Figure 15-10 shows the spacing guidelines for a standard alert.  
<span id="page-291-1"></span>See ["The Elements of an Alert"](#page-203-2) (page 204) for more details on designing alert dialogs.  
**Figure 15-10** Layout dimensions for a standard alert  
![](images/_page_291_Figure_9.jpeg)