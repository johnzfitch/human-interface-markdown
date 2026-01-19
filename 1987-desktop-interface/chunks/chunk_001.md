<!-- Chunk 1 | Source: 1987 Apple Human Interface Guidelines - The Apple Desktop Interface.pdf | Est. Tokens: 1897 -->
![](images/_page_0_Picture_4.jpeg)  
![](images/_page_1_Picture_0.jpeg)  
![](images/_page_2_Picture_0.jpeg)  
![](images/_page_2_Picture_1.jpeg)  
Addison-Wesley Publishing Company, Inc.  
Reading, Massachusetts Menlo Park, California New York Don Mills, Ontario Wokingham, England Amsterdam Bonn Sydney Singapore Tokyo Madrid San Juan  
#### **APPLE COMPUTER, INC.**  
Copyright © 1987 by Apple Computer, Inc.  
All rights reserved. No part of this publication may be reproduced, stored in a retrieval system, or transmitted, in any form or by any means, mechanical, electronic, photocopying, recording, or otherwise, without prior written permission of Apple Computer, Inc. Printed in the United States of America.  
© Apple Computer, Inc., 1986 20525 Mariani Avenue Cupertino, California 95014 (408) 996-1010  
The Apple Desktop Interface is proprietary to Apple Computer and is protected by both literary and audio-visual copyrights and patents. Unauthorized use or copying of the interface is not permitted and is a violation of Apple's intellectual property rights.  
Apple, the Apple logo, and LaserWriter are registered trademarks of Apple Computer,  
Macintosh is a trademark of Apple Computer, Inc.  
ITC Avant Garde Gothic, ITC Garamond, and ITC Zapf Dingbats are registered trademarks of International Typeface Corporation.  
Microsoft is a registered trademark of Microsoft Corporation.  
POSTSCRIPT is a trademark of Adobe Systems Incorporated.  
Simultaneously published in the United States and Canada.  
ISBN 0-201-17753-6 DEFGHII-DO-89  
Fourth Printing, December 1988  
#### WARRANTY INFORMATION  
ALL IMPLIED WARRANTIES ON THIS MANUAL, INCLUDING IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE, ARE LIMITED IN **DURATION TO NINETY (90)** DAYS FROM THE DATE OF THE ORIGINAL RETAIL PURCHASE OF THIS PRODUCT.  
Even though Apple has reviewed this manual, APPLE MAKES NO WARRANTY OR REPRESENTA-TION, EITHER EXPRESS OR IMPLIED, WITH RESPECT TO THIS MANUAL, ITS QUALITY, ACCURACY, MERCHANTABILITY, OR FITNESS FOR A PARTICULAR PURPOSE. AS A RESULT, THIS MANUAL IS SOLD "AS IS," AND YOU, THE PURCHASER, ARE ASSUMING THE ENTIRE RISK AS TO ITS QUALITY AND ACCURACY.  
IN NO EVENT WILL APPLE BE LIABLE FOR DIRECT, INDIRECT, SPECIAL, INCIDENTAL, OR CONSEQUENTIAL DAMAGES RESULTING FROM ANY DEFECT OR INACCURACY IN THIS MANUAL even if advised of the possibility of such damages.  
THE WARRANTY AND REMEDIES SET FORTH ABOVE ARE EXCLU-SIVE AND IN LIEU OF ALL OTHERS, ORAL OR WRITTEN, **EXPRESS OR IMPLIED.** No Apple dealer, agent, or employee is authorized to make any modification, extension, or addition to this warranty.  
Some states do not allow the exclusion or limitation of implied warranties or liability for incidental or consequential damages, so the above limitation or exclusion may not apply to you. This warranty gives you specific legal rights, and you may also have other rights which vary from state to state.  
![](images/_page_4_Picture_0.jpeg)  
#### Figures and tables ix Foreword xi  
#### Chapter <sup>1</sup> Philosophy <sup>1</sup>  
```
A view of the user 2
General design principles 3 Metaphors from the real world 3
Direct manipulation 4 See-and-point (instead of remember-and-type)
Consistency 6
WYSIWYG (what you see is what you get) 6
User control 7 Feedback and dialog 7 Forgiveness 8
Perceived stability 8
Aesthetic integrity 9
Principles of graphic communication 9
Visual consistency 10
Simplicity 10
Clarity 11 A strategy for programming 1
Modelessness 12 The event loop 13
Reversible actions 13 The screen 14
Plain language 14 User testing 15
The design process 15 Test subjects 1
Procedures 15
```  
Designing for disabled people 16 Vision disabilities 16 Hearing disabilities 17 Other disabilities 17  
#### Chapter 2 Elements of the Desktop Interface 19  
Screen elements 20  
The desktop 20  
Windows 22  
Window manipulation 23  
Dialog boxes, alert boxes, and controls 23  
Menus 24  
The menu bar 25  
Menu items 25  
Human-computer interaction 27  
Pointing 28  
Mouse actions 28  
Pointers 28  
Selecting 29  
Keyboard actions 30  
Color 30  
What is color? 31  
Standard uses of color 31  
Color coding 31  
General principles of color design 32  
Design in black and white 32  
Limit color use 33  
Contrast and discrimination 33  
Colors on grays 33  
Colored text 34  
Beware of blue 34  
Small objects 34  
Specific recommendations 34  
Backgrounds 34  
Outlines 34  
Highlighting and selection 35  
Menus 35  
Windows 35  
Dialog and alert boxes 35  
Pointers 35  
Sound 36  
When to use sound 36  
Getting attention 36  
Alerts 36  
Modes 36  
General guidelines 37 Restraint 37 Redundancy 37 Unobtrusiveness 37 Significant differences 37 User control 37 Summary 38  
#### Chapter 3 Specifications 39  
Introduction 40 The desktop 40 Windows 42 Document windows 43 Opening and closing windows 43 Multiple windows 44 The active window 45 Moving a window 45 Changing the si2e of <sup>a</sup> window 46 Window zooming 46 Scroll bars 49 Scrolling with the scroll arrows 50 Scrolling by windowful 50 Scrolling by dragging the scroll box 51 Proportional scroll boxes 51 Automatic scrolling 52 Splitting a window 53 Panels 55 Controls, dialog boxes, and alerts 55 Controls 56 Buttons 56 Check boxes and radio buttons 56 Dials 57 Dialog boxes 58 Alerts 60 Beeps 60 Alert boxes 6l Desk accessories 63 Menus 65 The menu bar 65 Menu items 66  
Choosing <sup>a</sup> menu item 66  
```
Appearance of menu items 67
Grouping operations in menus 67
Toggled menu items 68
Special visual features 69
Scrolling menus 71
Keyboard equivalents for menu items 72
Interrupting an operation 73
The standard menus 74
The Apple menu 74
The File menu 75
New 76
Open 76
Close 77
Save 78
Save As 78
Revert to Saved 79
Page Setup 79
Print 80
Quit 80
The Edit menu 80
The Clipboard 81
Undo 82
Cut 83
Copy 83
Paste 83
Clear 83
Select All 84
Show Clipboard 84
Font-related menus 84
Font menu 84
FontSize menu 85
Style menu 86
Special menu types 87
Hierarchical menus 87
Pop-up menus 88
Palettes 90
Tear-off menus 91
The pointing device 93
Cursors, pointers, and insertion points 93
Mouse actions 95
Clicking 95
Double-clicking 96
Pressing 96
Dragging 97
Mouse-ahead 97
```  
```
The keyboard 98
Character keys 98
Enter 98
Tab 98
Return 99
Backspace (or Delete) 99
Clear 99
Escape 99
Modifier keys 100
Shift 100
Caps Lock 100
Option 100
The Apple (or Command) key 101
The Control key 101
Type-ahead and auto-repeat 101
International keyboards 102
Arrow keys 102
Appropriate uses for the arrow keys 102
Moving the insertion point 103
Moving the insertion point in empty documents 103
Using modifier keys with arrow keys 104
Function keys 105
Selecting 106
Types of objects 106
Selection in general 108
Selection by clicking 108
Range selection 109
Extending a selection 109
Making a discontinuous selection 110
Selection by data type 111
Selections in text 111
Making a selection with arrow keys 113
Undoing a text selection 114
Selections in graphics 115
Selections in arrays and tables 116
Editing text 1 18
Inserting text 118
Backspacing 118
Replacing text 118
Intelligent cut and paste 119
Editing fields 120
```  
#### Appendix A The Roots of the Apple Desktop Interface <sup>123</sup>  
#### Appendix B Software for International Markets 125  
General guidelines 125 Macintosh localization 126 Text 127 Line spacing 127 Font selection 127 Uppercase and lowercase 127 Menus 128 The International Utilities Package 128 The Script Manager 128 Dialog and alert boxes 129  
#### Appendix C Recommended Reading <sup>131</sup>  
Index 137