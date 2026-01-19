<!-- Chunk 205 | Source: 2004-05 Apple Human Interface Guidelines.pdf | Est. Tokens: 335 -->
A standard alert dialog like the one provided by Carbon or Cocoa is shown in Figure 11-9.  
<span id="page-211-0"></span>**Figure 11-9** A standard alert example  
![](images/_page_211_Figure_3.jpeg)  
Although the standard alert dialogs provided by the Carbon and Cocoa take care of the general layout for you, there are a few details you are responsible for:  
- Verify that a 64 x 64 pixel version of your application icon is used in the alert.
- Make sure to include *both* the main message text and the informative text. An alert with only message text is not a complete alert and typically is not very useful to the user.
- Always put the action button in the bottom-right corner of the alert. This is the button that completes the action that the user initiated before the alert was displayed. Remember that the action button is not always the default button as it is in this example. In dangerous situations, the default button may be Cancel but, it should not be the action button and should not be located in the action button position.  
<span id="page-211-1"></span>Figure 11-10 shows the spacing guidelines for a standard alert.  
See ["The Elements of an Alert"](#page-135-3) (page 136) for more details on designing alert dialogs.  
**Figure 11-10** Layout dimensions for a standard alert  
![](images/_page_211_Figure_11.jpeg)