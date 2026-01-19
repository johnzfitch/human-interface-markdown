<!-- Chunk 256 | Source: 2008-01 Apple Human Interface Guidelines.pdf | Est. Tokens: 345 -->
Round buttons are seldom used, but they can be useful when you need a simple iconic push button that initiates an immediate action. Typically, round buttons are used as navigation controls.  
Don't use a round button to create a Help button. If you provide onscreen help, use the standard Help button instead (see "The Help [Button"](#page-278-0) (page 279) for more on this control). In addtion, you should not use round buttons as radio buttons or as checkboxes.  
#### <span id="page-281-1"></span>Round Button Contents and Labeling  
Round buttons contain images only, not text. If you need to display a single letter in a round button you should treat the letter as an icon.  
**Figure 15-19** Examples of round buttons  
![](images/_page_281_Picture_14.jpeg)  
![](images/_page_281_Picture_15.jpeg)  
#### Round Button Specifications  
**Control sizes**: Round buttons are available in regular and small sizes only. The regular-size round button is 25 pixels in diameter; the small round button is 20 pixels in diameter.  
**Control spacing**: Leave 12 pixels between round buttons or between a round button and another interface element.  
#### Round Button Implementation  
Round buttons are available in Interface Builder. To create one using Application Kit programming interfaces, use the setBezelStyle: method of NSButtonCell with NSCircularBezelStyle as the argument.