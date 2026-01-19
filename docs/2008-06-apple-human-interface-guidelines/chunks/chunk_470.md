<!-- Chunk 470 | Source: 2008-06 Apple Human Interface Guidelines.pdf | Est. Tokens: 413 -->
A standard alert is shown in Figure 16-9.  
Figure 16-9 A standard alert example  
![](images/_page_342_Picture_8.jpeg)  
Although the standard alerts take care of the general layout for you, there are a few details you are responsible for:  
■ Make sure that the application icon you use in the alert is 64 x 64 pixels.  
- Make sure to include *both* the main message text and the informative text. An alert with only message text is not a complete alert and typically is not very useful to the user.
- Always put the action button in the bottom-right corner of the alert. This is the button that completes the action that the user initiated before the alert was displayed. Remember that the action button is not always the default button as it is in this example (the default button has color and pulses and receives a click when the user presses Return or Enter). In situations where clicking the action button can have dangerous consequences (such as data loss) the default button can be Cancel, but when this is the case it should not be located in the action button position.  
Alerts look best when the margin at the bottom edge is the same height as in other windows (for example, in Figure 16-10, this margin is 20 pixels). In addition, you should ensure that there is an equal amount of space in the margins at the sides. The standard alert shown in Figure 16-10 uses a 24-pixel wide margin at the sides of the window.  
<span id="page-343-2"></span>See "The [Elements](#page-232-1) of an Alert" (page 233) for more details on designing alerts.  
**Figure 16-10** Layout dimensions for a standard alert  
![](images/_page_343_Picture_7.jpeg)