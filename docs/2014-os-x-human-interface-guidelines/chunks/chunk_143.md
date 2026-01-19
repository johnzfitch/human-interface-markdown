<!-- Chunk 143 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 207 -->
A **round button** initiates an immediate action.  
Round buttons are available in Interface Builder. To create one using AppKit programming interfaces, use the setBezelStyle: method of NSButtonCell with NSCircularBezelStyle as the argument.  
Round buttons contain images only, not text.  
**Don't use a round button to create a Help button.** If you provide onscreen help, use the standard Help button instead (to learn more about this control, see The Help [Button](#page-187-0) (page 188)).  
**Don't use round buttons as radio buttons or as checkboxes.** If you need to provide functionality of these types, use radio buttons (see Radio [Buttons](#page-179-0) (page 180)) or checkboxes (see [Checkbox](#page-181-0) (page 182)).  
If you need to display a single letter in a round button you should treat the letter as an icon.