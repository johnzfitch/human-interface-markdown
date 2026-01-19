<!-- Chunk 249 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 504 -->
Like a push button, a **round button** initiates an immediate action. Unlike a push button, however, a round button does not contain text.  
Round buttons, like bevel buttons, are seldom used in applications running in Mac OS X v10.4 and later. You might be able to use a gradient button that contains a system-provided (or custom) image as an alternative. See ["Gradient](#page-272-0) Buttons" (page 273) for more information about gradient buttons; see ["System-Provided](#page-154-0) [Images"](#page-154-0) (page 155) for more information about system-provided images available in Mac OS X v10.5 and later.  
#### Round Button Usage  
Round buttons are seldom used, but they can be useful when you need a simple iconic push button that initiates an immediate action. Typically, round buttons are used as navigation controls.  
Don't use a round button to create a Help button. If you provide onscreen help, use the standard Help button instead (see "The Help [Button"](#page-275-0) (page 276) for more on this control). In addition, you should not use round buttons as radio buttons or as checkboxes.  
#### <span id="page-278-1"></span>Round Button Contents and Labeling  
Round buttons contain images only, not text. If you need to display a single letter in a round button you should treat the letter as an icon.  
**Figure 15-19** Examples of round buttons  
![](images/_page_278_Picture_14.jpeg)  
![](images/_page_278_Picture_15.jpeg)  
#### Round Button Specifications  
**Control sizes**: Round buttons are available in regular and small sizes only. The regular-size round button is 25 pixels in diameter; the small round button is 20 pixels in diameter.  
**Control spacing**: Leave 12 pixels between round buttons or between a round button and another interface element.  
#### Round Button Implementation  
Round buttons are available in Interface Builder. To create one using Application Kit programming interfaces, use the setBezelStyle: method of NSButtonCell with NSCircularBezelStyle as the argument.