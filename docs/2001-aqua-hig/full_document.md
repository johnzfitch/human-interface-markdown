# Inside Mac OS X

# Aqua Human Interface Guidelines

![](images/_page_0_Picture_2.jpeg)

 Apple Computer, Inc. © 2001 Apple Computer, Inc. All rights reserved.

No part of this publication may be reproduced, stored in a retrieval system, or transmitted, in any form or by any means, mechanical, electronic, photocopying, recording, or otherwise, without prior written permission of Apple Computer, Inc., with the following exceptions: Any person is hereby authorized to store documentation on a single computer for personal use only and to print copies of documentation for personal use provided that the documentation contains Apple's copyright notice.

The Apple logo is a trademark of Apple Computer, Inc. Use of the "keyboard" Apple logo (Option-Shift-K) for commercial purposes without the prior written consent of Apple may constitute trademark infringement and unfair competition in violation of federal and state laws.

No licenses, express or implied, are granted with respect to any of the technology described in this book. Apple retains all intellectual property rights associated with the technology described in this book. This book is intended to assist application developers to develop applications only for Apple-labeled or Apple-licensed computers

Every effort has been made to ensure that the information in this document is accurate. Apple is not responsible for typographical errors.

Apple Computer, Inc. 1 Infinite Loop Cupertino, CA 95014 408-996-1010

Apple, the Apple logo, AirPort, AppleScript, AppleTalk, AppleWorks, Aqua, Cocoa, Final Cut Pro, FireWire, Keychain, Mac, Macintosh, QuickDraw, QuickTime, Sherlock, and WorldScript are

trademarks of Apple Computer, Inc., registered in the United States and other countries.

Balloon Help, Carbon, Finder, iMac, iMovie, and ResEdit are trademarks of Apple Computer, Inc.

Objective-C is a trademark of NeXT Software, Inc., registered in the United States and other countries.

Java is a trademark of Sun Microsystems, Inc., registered in the U.S. and other countries.

Simultaneously published in the United States and Canada

**Even though Apple has reviewed this manual, APPLE MAKES NO WARRANTY OR REPRESENTATION, EITHER EXPRESS OR IMPLIED, WITH RESPECT TO THIS MANUAL, ITS QUALITY, ACCURACY, MERCHANTABILITY, OR FITNESS FOR A PARTICULAR PURPOSE. AS A RESULT, THIS MANUAL IS SOLD "AS IS," AND YOU, THE PURCHASER, ARE ASSUMING THE ENTIRE RISK AS TO ITS QUALITY AND ACCURACY.**

**IN NO EVENT WILL APPLE BE LIABLE FOR DIRECT, INDIRECT, SPECIAL, INCIDENTAL, OR CONSEQUENTIAL DAMAGES RESULTING FROM ANY DEFECT OR INACCURACY IN THIS MANUAL, even if advised of the possibility of such damages.**

**THE WARRANTY AND REMEDIES SET FORTH ABOVE ARE EXCLUSIVE AND IN LIEU OF ALL OTHERS, ORAL OR WRITTEN, EXPRESS OR IMPLIED. No Apple dealer, agent, or employee is authorized to make any modification, extension, or addition to this warranty.**

**Some states do not allow the exclusion or limitation of implied warranties or liability for incidental or consequential damages, so the above limitation or exclusion may not apply to you. This warranty gives you specific legal rights, and you may also have other rights which vary from state to state.**

# Contents

[Figures and Tables](#page-12-0) 13

| Chapter 1 | Introduction to the Aqua Human Interface Guidelines                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 19 |
|-----------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----|
|           | The Benefits of Applying the Interface Guidelines<br>20<br>Tools for Applying the Guidelines<br>20<br>If You Have a Need Not Covered by the Guidelines<br>22<br>What's New in Aqua<br>23<br>Filename Extension Hiding<br>25                                                                                                                                                                                                                                                                                                                                                        |    |
| Chapter 2 | Human Interface Design<br>27                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |    |
|           | Human Interface Design Principles<br>27<br>Metaphors<br>27<br>Direct Manipulation<br>28<br>See-and-Point<br>28<br>Consistency<br>29<br>WYSIWYG (What You See Is What You Get)<br>29<br>User Control<br>30<br>Feedback and Dialog<br>30<br>Forgiveness<br>31<br>Perceived Stability<br>31<br>Aesthetic Integrity<br>31<br>Modelessness<br>32<br>Knowledge of Your Audience<br>33<br>Worldwide Compatibility<br>33<br>Cultural Values<br>34<br>Language Differences<br>34<br>Text Display and Text Editing<br>35<br>Default Alignment of Interface Elements<br>35<br>Resources<br>36 |    |

[Universal Accessibility](#page-35-1) 36 [Visual Disabilities](#page-36-0) 37 [Hearing Disabilities](#page-36-1) 37 [Physical Disabilities](#page-37-0) 38

### **Chapter 3** [The Dock](#page-38-0) 39

[Dock Notification Behavior](#page-38-1) 39 [Dock Menus](#page-39-0) 40 [Clicking in the Dock](#page-40-0) 41

### **[Chapter 4](#page-42-0)** Menus 43

[What's New in Aqua](#page-42-1) 43 [Menu Elements](#page-44-0) 45 [Menu Titles](#page-44-1) 45 [Menu Items](#page-45-0) 46 [Grouping Items in Menus](#page-45-1) 46 [Menu Behavior](#page-47-0) 48 [Scrolling Menus](#page-47-1) 48 [Toggled Menu Items](#page-48-0) 49 [Hierarchical Menus \(Submenus\)](#page-49-0) 50 [Sticky Menus](#page-50-0) 51 [Standard Pull-Down Menus \(The Menu Bar\)](#page-50-1) 51 [The Apple Menu](#page-51-0) 52 [The Application Menu](#page-52-0) 53 [The Application Menu Title](#page-53-0) 54 [The Application Menu Contents](#page-54-0) 55 [The File Menu](#page-54-1) 55 [The Edit Menu](#page-57-0) 58 [The View Menu](#page-59-0) 60 [The Window Menu](#page-59-1) 60 [The Help Menu](#page-60-0) 61 [Menu Bar Status Items](#page-60-1) 61

[Contextual Menus](#page-61-0) 62

[Using Special Characters and Text Styles in Menus](#page-62-0) 63 [Using Symbols in Menus](#page-62-1) 63 [Using Ellipses in Menus](#page-63-0) 64 [Using Text Styles and Fonts in Menus](#page-64-0) 65

### **Chapter 5** [Windows](#page-66-0) 67

[What's New in Aqua](#page-67-0) 68 [Window Appearance and Behavior](#page-68-0) 69 [Opening and Naming Windows](#page-69-0) 70 [Positioning Windows](#page-72-0) 73 [Closing Windows](#page-75-0) 76 [Moving Windows](#page-76-0) 77 [Resizing and Zooming Windows](#page-76-1) 77 [Active and Inactive Windows](#page-77-0) 78 [Click-Through](#page-77-1) 78 [Scrolling Windows](#page-80-0) 81 [Automatic Scrolling](#page-82-0) 83 [Minimizing and Expanding Windows](#page-83-0) 84 [Windows With Changeable Panes](#page-83-1) 84 [Special Windows](#page-84-0) 85 [Drawers](#page-84-1) 85 [When to Use Drawers](#page-85-0) 86 [Drawer Behavior](#page-85-1) 86 [Utility Windows](#page-86-0) 87 [The About Window](#page-87-0) 88

### **Chapter 6** [Dialogs](#page-90-0) 91

[What's New in Aqua](#page-90-1) 91 [Types of Dialogs and When to Use Them](#page-91-0) 92 [Document-Modal Dialogs \(Sheets\)](#page-92-0) 93 [Sheet Behavior](#page-93-0) 94 [When to Use Sheets](#page-93-1) 94 [When Not to Use Sheets](#page-94-0) 95 [Alerts](#page-94-1) 95

[Dialog Behavior](#page-97-0) 98 [Accepting Changes](#page-97-1) 98 [The Open Dialog](#page-98-0) 99 [Saving, Closing, and Quitting Behavior](#page-100-0) 101 [Save Dialogs](#page-101-0) 102 [Closing a Document With Unsaved Changes](#page-104-0) 105 [Saving Documents During a Quit Operation](#page-105-0) 106 [Saving a Document With the Same Name as an Existing Document](#page-108-0) 109 [The Choose Dialog](#page-109-0) 110 [The Printing Dialogs](#page-111-0) 112

### **Chapter 7** [Controls](#page-114-0) 115

[What's New in Aqua](#page-114-1) 115 [Control Behavior and Appearance](#page-115-0) 116 [Push Buttons](#page-115-1) 116 [Push Button Specifications](#page-116-0) 117 [Radio Buttons and Checkboxes](#page-117-0) 118 [Radio Button and Checkbox Specifications](#page-118-0) 119 [Selections Containing More Than One Checkbox State](#page-118-1) 119 [Pop-Up Menus](#page-119-0) 120 [Pop-Up Menu Specifications](#page-121-0) 122 [Command Pop-Down Menus](#page-122-0) 123 [Combination Boxes](#page-122-1) 123 [Combo Box Specifications](#page-123-0) 124 [The Text Entry Field](#page-124-0) 125 [The Pop-Up Menu or Scrolling List](#page-124-1) 125 [Placards](#page-125-0) 126 [Bevel Buttons](#page-125-1) 126 [Bevel Button Specifications](#page-126-0) 127 [Pop-Up Icon Buttons and Pop-Up Bevel Buttons](#page-127-0) 128 [Slider Controls](#page-130-0) 131 [Slider Control Specifications](#page-130-1) 131 [Tab Controls](#page-131-0) 132 [Tab Control Specifications](#page-132-0) 133 [Progress Indicators and Relevance Controls](#page-134-0) 135

[Text Fields and Scrolling Lists](#page-136-0) 137 [Tools for Creating Lists](#page-137-0) 138 [Text Input Field Specifications](#page-138-0) 139 [Scrolling List Specifications](#page-139-0) 140 [Image Wells](#page-139-1) 140 [Disclosure Triangles](#page-140-0) 141

### **Chapter 8** [Layout Guidelines](#page-142-0) 143

[Positioning Controls in Dialogs and Windows](#page-142-1) 143 [Group Boxes](#page-143-0) 144 [Sample Dialog Layouts](#page-146-0) 147 [Using Small Versions of Controls](#page-152-0) 153

### **Chapter 9** [User Input](#page-154-0) 155

[What's New in Aqua](#page-154-1) 155 [The Mouse and Other Pointing Devices](#page-155-0) 156 [Using the Mouse](#page-155-1) 156 [Clicking](#page-156-0) 157 [Double-Clicking](#page-156-1) 157 [Pressing](#page-156-2) 157 [Dragging](#page-157-0) 158 [The Keyboard](#page-157-1) 158 [The Functions of Specific Keys](#page-158-0) 159 [Character Keys](#page-158-1) 159 [Modifier Keys](#page-160-0) 161 [Arrow Keys](#page-161-0) 162 [Function Keys](#page-166-0) 167 [Keyboard Focus and Navigation](#page-167-0) 168 [Keyboard Equivalents](#page-171-0) 172 [Creating Your Own Keyboard Equivalents](#page-173-0) 174 [Type-Ahead and Auto-Repeat](#page-175-0) 176 [Selecting](#page-175-1) 176 [Selection Methods](#page-176-0) 177 [Selection by Clicking](#page-177-0) 178

[Selection by Dragging](#page-177-1) 178 [Changing a Selection With Shift-Click](#page-178-0) 179 [Changing a Selection With Command-Click](#page-179-0) 180 [Selections in Text](#page-180-0) 181 [Selecting With the Mouse](#page-180-1) 181 [What Constitutes a Word](#page-181-0) 182 [Selecting Text With the Arrow Keys](#page-182-0) 183 [Selections in Graphics](#page-182-1) 183 [Selections in Arrays and Tables](#page-182-2) 183 [Editing Text](#page-183-0) 184 [Inserting Text](#page-183-1) 184 [Deleting Text](#page-183-2) 184 [Replacing a Selection](#page-184-0) 185 [Intelligent Cut and Paste](#page-184-1) 185 [Editing Text Fields](#page-185-0) 186 [Entering Passwords](#page-186-0) 187

### **[Chapter 10](#page-188-0)** Fonts 189

### **[Chapter 11](#page-190-0)** Icons 191

[What's New in Aqua](#page-190-1) 191 [More Realistic Icons](#page-190-2) 191 [Icon Genres and Families](#page-191-0) 192 [Types of Icons](#page-193-0) 194 [Application Icons](#page-193-1) 194 [User Application Icons](#page-193-2) 194 [Viewer, Player, and Accessory Icons](#page-195-0) 196 [Utility Icons](#page-196-0) 197 [Non-Application Icons](#page-196-1) 197 [Document Icons](#page-196-2) 197 [Icons for Preferences and Plug-ins](#page-198-0) 199 [Icons for Hardware and Removable Media](#page-198-1) 199 [Toolbar Icons](#page-200-0) 201 [Icon Perspectives](#page-201-0) 202

[Icon Materials](#page-203-0) 204 [Conveying an Emotional Quality in Icons](#page-204-0) 205 [Suggested Process for Creating Aqua Icons](#page-205-0) 206 [Tips for Designing Aqua Icons](#page-206-0) 207

### **Chapter 12** [Drag and Drop](#page-208-0) 209

[Drag and Drop Design Overview](#page-208-1) 209 [Drag and Drop Semantics](#page-209-0) 210 [Move Versus Copy](#page-209-1) 210 [When to Check the Option Key State](#page-210-0) 211 [Selection Feedback](#page-211-0) 212 [Single-Gesture Selection and Dragging](#page-211-1) 212 [Background Selections](#page-211-2) 212 [Drag Feedback](#page-212-0) 213 [Destination Feedback](#page-212-1) 213 [Windows](#page-212-2) 213 [Text](#page-213-0) 214 [Multiple Dragged Items](#page-213-1) 214 [Automatic Scrolling](#page-214-0) 215 [Using the Trash as a Destination](#page-214-1) 215 [Drop Feedback](#page-214-2) 215 [Finder Icons](#page-215-0) 216 [Graphics](#page-215-1) 216 [Text](#page-215-2) 216 [Transferring a Selection](#page-215-3) 216 [Feedback for an Invalid Drop](#page-216-0) 217 [Clippings](#page-216-1) 217

### **[Chapter 13](#page-218-0)** Help 219

[What's New in Aqua](#page-218-1) 219 [Apple's Philosophy of Help](#page-219-0) 220 [Help Viewer](#page-220-0) 221 [Providing Access to Help](#page-221-0) 222

[Help Tags](#page-221-1) 222 [Help Tag Guidelines](#page-222-0) 223 [Setup Assistants](#page-224-0) 225

### **Chapter 14** [Language](#page-228-0) 229

[Style](#page-228-1) 229 [Terminology](#page-229-0) 230 [Developer Terms and User Terms](#page-229-1) 230 [Labels for Interface Elements](#page-229-2) 230 [Capitalization of Interface Elements](#page-230-0) 231 [Using Contractions in the Interface](#page-231-0) 232 [Writing Good Alert Messages](#page-231-1) 232

### **Chapter 15** [File Location](#page-234-0) 235

[Predefined User Domain Directories](#page-234-1) 235

### **Appendix A** [Checklist for Creating Aqua Applications](#page-236-0) 237

[General Considerations](#page-236-1) 237 [Graphic Design](#page-238-0) 239 [Menus](#page-239-0) 240 [Pop-Up Menus](#page-240-0) 241 [Windows](#page-240-1) 241 [Scrolling](#page-241-0) 242 [Utility Windows](#page-242-0) 243 [Dialogs](#page-242-1) 243 [Alerts](#page-244-0) 245 [The Mouse](#page-244-1) 245 [Keyboard Equivalents](#page-245-0) 246 [Text](#page-245-1) 246 [Icons](#page-246-0) 247 [User Documentation](#page-246-1) 247 [Help Tags](#page-247-0) 248

| Mac OS X Terminology Guidelines<br>Appendix B  | 249 |
|------------------------------------------------|-----|
|                                                |     |
| Document Revision History<br>Appendix C<br>261 |     |
|                                                |     |
| Glossary<br>265                                |     |
|                                                |     |
| Index<br>273                                   |     |

# <span id="page-12-0"></span>Figures and Tables

| Chapter 3 | The Dock    | 39                                                                                                       |
|-----------|-------------|----------------------------------------------------------------------------------------------------------|
|           | Figure 3-1  | An example of a badged Dock icon: The Mail application icon<br>indicates there are unread messages<br>40 |
|           | Figure 3-2  | The iTunes Dock icon menu<br>41                                                                          |
| Chapter 4 | Menus       | 43                                                                                                       |
|           | Figure 4-1  | The menu bar<br>44                                                                                       |
|           | Figure 4-2  | A pull-down menu and its parts<br>45                                                                     |
|           | Figure 4-3  | Grouping items in menus<br>47                                                                            |
|           | Figure 4-4  | Avoid ambiguous toggled menu items<br>49                                                                 |
|           | Figure 4-5  | A hierarchical menu<br>50                                                                                |
|           | Figure 4-6  | The menu bar displayed when the Finder is active<br>51                                                   |
|           | Figure 4-7  | The Apple menu<br>53                                                                                     |
|           | Figure 4-8  | The Mail application menu<br>54                                                                          |
|           | Figure 4-9  | The File menu<br>56                                                                                      |
|           | Figure 4-10 | The Edit menu<br>58                                                                                      |
|           | Figure 4-11 | A Window menu<br>60                                                                                      |
|           | Figure 4-12 | A contextual menu in a document (left) and in the Finder<br>62                                           |
|           | Figure 4-13 | Don't use arbitrary symbols in menus<br>63                                                               |
|           | Figure 4-14 | Symbols in menus<br>64                                                                                   |
|           | Figure 4-15 | A Font menu displayed with different fonts<br>65                                                         |
|           |             |                                                                                                          |
| Chapter 5 | Windows     | 67                                                                                                       |
|           | Figure 5-1  | Standard window parts<br>69                                                                              |
|           | Figure 5-2  | The close button in its unsaved changes state<br>70                                                      |
|           | Figure 5-3  | Document path pop-up menu, opened by Command-clicking the<br>proxy icon<br>70                            |
|           | Figure 5-4  | Appropriate titles for a series of unnamed windows<br>71                                                 |
|           | Figure 5-5  | Examples of correct and incorrect window titles<br>72                                                    |
|           |             |                                                                                                          |

Figure 5-6 ["Visually centered" new window placement\] 74](#page-73-0)

|           | Figure 5-7                | Appropriate placement of a new window on a system with multiple<br>monitors (the user moved the first window to span the<br>screens))<br>76         |
|-----------|---------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
|           | Figure 5-8                | Window controls in active and inactive states<br>78                                                                                                 |
|           | Figure 5-9<br>Figure 5-10 | An inactive window with controls that support click-through<br>79<br>The Save button on the inactive window does not support click<br>through<br>81 |
|           | Figure 5-11               | The elements of a scroll bar<br>82                                                                                                                  |
|           | Figure 5-12               | An open drawer next to its parent window<br>85                                                                                                      |
|           | Figure 5-13               | Examples of tool palettes (utility windows)<br>87                                                                                                   |
|           | Figure 5-14               | Examples of About windows (all specifications apply to both<br>versions)<br>89                                                                      |
| Chapter 6 | Dialogs                   | 91                                                                                                                                                  |
|           |                           |                                                                                                                                                     |
|           | Figure 6-1                | The Save Changes alert: An example of using a sheet to display a<br>document-modal dialog<br>94                                                     |
|           | Figure 6-2                | A standard alert<br>96                                                                                                                              |
|           | Figure 6-3                | A customized alert showing the caution icon badged with an<br>application icon<br>97                                                                |
|           | Figure 6-4                | An Open dialog<br>100                                                                                                                               |
|           | Figure 6-5                | The minimal (collapsed) Save dialog<br>102                                                                                                          |
|           | Figure 6-6                | The expanded Save dialog<br>104                                                                                                                     |
|           | Figure 6-7                | A Save Changes alert for a document-based application<br>106                                                                                        |
|           | Figure 6-8                | A Save Changes alert for an application that is not document<br>based<br>107                                                                        |
|           | Figure 6-9                | The Save Before Quitting alert (sheet) that appears when the user<br>quits with only one unsaved document<br>108                                    |
|           | Figure 6-10               | The Review Changes alert (application modal) that appears when<br>the user quits with more than one unsaved document open<br>108                    |
|           | Figure 6-11               | Alert for confirming replacing a file<br>110                                                                                                        |
|           | Figure 6-12               | A Choose dialog<br>111                                                                                                                              |
|           | Figure 6-13               | A Print dialog<br>113                                                                                                                               |
|           |                           |                                                                                                                                                     |

| Chapter 7 | Controls    | 115                                                              |
|-----------|-------------|------------------------------------------------------------------|
|           | Figure 7-1  | Example of standard push buttons<br>116                          |
|           | Figure 7-2  | Stacked push buttons<br>117                                      |
|           | Figure 7-3  | Push button dimensions<br>117                                    |
|           | Figure 7-4  | Radio button spacing<br>119                                      |
|           | Figure 7-5  | Checkbox spacing<br>119                                          |
|           | Figure 7-6  | Dashes in checkboxes representing a selection with more than one |
|           |             | state<br>120                                                     |
|           | Figure 7-7  | An open pop-up menu<br>120                                       |
|           | Figure 7-8  | Pop-up menu spacing<br>122                                       |
|           | Figure 7-9  | A command pop-down menu<br>123                                   |
|           | Figure 7-10 | Combo box with scrolling list and with pop-up menu (closed and   |
|           |             | open)<br>124                                                     |
|           | Figure 7-11 | Combo box dimensions<br>124                                      |
|           | Figure 7-12 | A placard pop-up menu<br>126                                     |
|           | Figure 7-13 | Bevel button specifications<br>127                               |
|           | Figure 7-14 | Bevel buttons as radio buttons and push buttons<br>128           |
|           | Figure 7-15 | Pop-up icon button<br>129                                        |
|           | Figure 7-16 | Pop-up bevel button with square corners<br>130                   |
|           | Figure 7-17 | Pop-up bevel button with rounded corners<br>130                  |
|           | Figure 7-18 | Slider control dimensions<br>131                                 |
|           | Figure 7-19 | Small slider dimensions<br>131                                   |
|           | Figure 7-20 | Orientation of tab text on each side<br>132                      |
|           | Figure 7-21 | Tab control dimensions<br>133                                    |
|           | Figure 7-22 | Small tab control dimensions<br>133                              |
|           | Figure 7-23 | Tab panes edge to edge<br>134                                    |
|           | Figure 7-24 | Tab panes inset from edge of window<br>135                       |
|           | Figure 7-25 | Progress bars<br>136                                             |
|           | Figure 7-26 | Relevance control<br>136                                         |
|           | Figure 7-27 | Text input field specifications<br>139                           |
|           | Figure 7-28 | Small text input field specifications<br>139                     |
|           | Figure 7-29 | Scrolling list dimensions<br>140                                 |
|           | Figure 7-30 | Image wells<br>141                                               |
|           | Figure 7-31 | Disclosure triangles in the Finder list view<br>141              |

| Chapter 8  | Layout Guidelines                                                                                                                                                           | 143                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
|------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|            | Figure 8-1<br>Figure 8-2<br>Figure 8-3<br>Figure 8-4<br>Figure 8-5<br>Figure 8-6<br>Figure 8-7<br>Figure 8-8<br>Figure 8-9                                                  | Dialog redesigned without group boxes (first example)<br>145<br>Dialog redesigned without group boxes (second example)<br>146<br>Dialog redesigned without a group box (third example)]<br>147<br>A standard alert with dimensions<br>148<br>Sample application preferences dialog<br>149<br>Sample dialogs with panes<br>150<br>Sample dialog with scrolling list<br>152<br>Sample window using small scroll bars and resize control<br>153<br>Sample utility window using small controls<br>154                                                                                                                                                                                                                                                                                         |
| Chapter 9  | User Input                                                                                                                                                                  | 155                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
|            | Figure 9-1<br>Figure 9-2<br>Figure 9-3<br>Figure 9-4<br>Figure 9-5<br>Figure 9-6<br>Table 9-1<br>Table 9-2<br>Table 9-3<br>Table 9-4<br>Table 9-5<br>Table 9-6<br>Table 9-7 | Keyboard focus for a text field<br>168<br>Keyboard focus for a scrolling list<br>169<br>Keyboard focus for columns<br>169<br>Selection techniques<br>178<br>Shift-clicking in the addition model and the fixed-point<br>model<br>179<br>Discontinuous selection within an array<br>180<br>Moving the insertion point with the arrow keys<br>164<br>Extending text selection with the Shift and arrow keys<br>165<br>Key combinations for moving focus in full keyboard access<br>mode<br>171<br>Reserved and recommended keyboard equivalents<br>173<br>Key combinations reserved for international systems<br>174<br>Recommended keyboard equivalents using Shift to complement<br>other commands<br>175<br>Example of using Option to modify a shortcut already using<br>Command<br>175 |
| Chapter 10 | Fonts                                                                                                                                                                       | 189                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |

**16**

Figure 10-1 [Mac OS X standard fonts 189](#page-188-1)

| Chapter 11 | Icons        | 191                                                                                                        |
|------------|--------------|------------------------------------------------------------------------------------------------------------|
|            | Figure 11-1  | Traditional application icon and Mac OS X icon<br>191                                                      |
|            | Figure 11-2  | Application icons of different genres—user applications and                                                |
|            |              | utilities—shown as they might appear in the Dock<br>192                                                    |
|            | Figure 11-3  | Two icon genres: User application icons in top row, utility icons in                                       |
|            |              | bottom row<br>193                                                                                          |
|            | Figure 11-4  | An icon family: The iTunes application icon and its associated                                             |
|            |              | icons<br>194                                                                                               |
|            | Figure 11-5  | The TextEdit application icon makes it obvious what this application                                       |
|            |              | is for<br>195                                                                                              |
|            | Figure 11-6  | The Preview application icon: An example of a tool element<br>195                                          |
|            | Figure 11-7  | The Stickies application icon: Effective without the addition of a                                         |
|            |              | tool<br>196                                                                                                |
|            | Figure 11-8  | The icons for QuickTime Player, Calculator, and Chess<br>196                                               |
|            | Figure 11-9  | Discriminating use of color in the Process Viewer and Print Center                                         |
|            |              | icons<br>197                                                                                               |
|            | Figure 11-10 | Icons for the Preview application and a Preview document<br>198                                            |
|            | Figure 11-11 | Incorrect and correct badging of a document icon<br>198                                                    |
|            | Figure 11-12 | Icons for a preferences application (System Preferences) and for a file                                    |
|            |              | that stores preferences (for the iTunes application)<br>199                                                |
|            | Figure 11-13 | A plug-in icon<br>199                                                                                      |
|            | Figure 11-14 | Icons for external (top row) and internal hardware devices<br>200                                          |
|            | Figure 11-15 | Icons for removable media<br>200                                                                           |
|            | Figure 11-16 | Finder toolbar icons<br>201                                                                                |
|            | Figure 11-17 | Toolbar icons and their dominant shapes<br>201                                                             |
|            | Figure 11-18 | The circled icons appear elsewhere in the interface; they retain their                                     |
|            |              | perspective when used in a toolbar<br>202                                                                  |
|            | Figure 11-19 | The Mail toolbar<br>202                                                                                    |
|            | Figure 11-20 | Perspective for application icons: Sitting on a desk in front of                                           |
|            |              | you<br>203                                                                                                 |
|            | Figure 11-21 | Perspective for flat utility icons: On a shelf in front of you, with a<br>shadow on the wall behind<br>203 |
|            | Figure 11-22 | Perspective for three-dimensional object: Sitting on a shelf in front of                                   |
|            |              | you, with the shadow below the object<br>204                                                               |
|            | Figure 11-23 | Perspective for toolbar icons: Straight-on, with subtle shadow on the                                      |
|            |              | "floor"<br>204                                                                                             |
|            | Figure 11-24 | Materials: Transparency used to convey meaning<br>205                                                      |
|            |              |                                                                                                            |

| Chapter 12 | Drag and Drop                                                         | 209                                                                                                                                                                                                                         |
|------------|-----------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|            | Table 12-1                                                            | Common drag-and-drop operations and results<br>211                                                                                                                                                                          |
| Chapter 13 | Help                                                                  | 219                                                                                                                                                                                                                         |
|            | Figure 13-1<br>Figure 13-2<br>Figure 13-3                             | A help tag and an expanded help tag<br>223<br>The icon for AirPort Setup Assistant<br>225<br>A typical setup assistant pane<br>226                                                                                          |
| Chapter 14 | Language                                                              | 229                                                                                                                                                                                                                         |
|            | Figure 14-1<br>Figure 14-2<br>Figure 14-3<br>Table 14-1<br>Table 14-2 | A poorly written alert message<br>233<br>An improved alert message<br>233<br>A well-written alert message<br>234<br>Translating developer terms into user terms<br>230<br>Proper capitalization of onscreen elements<br>231 |
| Appendix C |                                                                       | Document Revision History<br>261                                                                                                                                                                                            |
|            | Table C-1                                                             | Document revision history<br>261                                                                                                                                                                                            |

Figure 11-25 [Being emotive: The same message conveyed two ways 205](#page-204-2)

<span id="page-18-0"></span>This document describes what you need to do to design your application for Aqua, the Mac OS X user interface. Primarily intended for Carbon and Cocoa developers who want their applications to look right and behave correctly in Mac OS X, these guidelines provide examples of how to use Aqua interface elements. Java application developers will also find these guidelines useful.

Mac OS X is the world's most advanced operating system, combining a powerful core foundation with a new and compelling user interface called Aqua. With brilliant new features and an aesthetically refined use of color, transparency, and animation, Aqua makes computing even easier for new users, while providing the productivity that professional users have come to expect of the Macintosh. The user interface features, behaviors, and appearances introduced in Aqua deliver a well organized and cohesive user experience available to all applications developed for Mac OS X.

This document assumes that you are familiar with the basic software design principles and considerations originally described in *Macintosh Human Interface Guidelines.* [The principles are often overlooked, so they are summarized in the next](http://developer.apple.com/membership/index.htm)  [chapter. You can download the original document, and later supplements, from](http://developer.apple.com/membership/index.htm)  [http://developer.apple.com/techpubs/macos8/mac8.html.](http://developer.apple.com/techpubs/macos8/mac8.html)

#### <span id="page-18-2"></span>**Important**

This document has been reviewed for technical accuracy, but the information herein is subject to change.

<span id="page-18-1"></span>[To receive notification of updates to this document and](http://developer.apple.com/membership/index.html)  [others, you can sign up for Apple Developer Connection's](http://developer.apple.com/membership/index.html)  free Online Program and receive the weekly ADC News email newsletter. For more details about the Online [Program, see http://developer.apple.com/membership/](http://developer.apple.com/membership/index.html) [index.html](http://developer.apple.com/membership/index.html).

## <span id="page-19-0"></span>The Benefits of Applying the Interface Guidelines

<span id="page-19-2"></span>These guidelines are designed to assist you in developing products that provide Mac OS X users with a consistent visual and behavioral experience across applications and the operating system. Following the guidelines is to your advantage because

- users will learn your application faster if the interface looks and behaves like applications they're already familiar with
- users will accomplish their tasks quickly, because well-designed applications don't get in the user's way
- your application will have the same modern, elegant appearance as other Mac OS X applications
- your application will be easier to document, because an intuitive interface and standard behaviors don't require as much explanation
- customer support calls will be reduced (for the reasons cited above)
- your application will be easier to localize, because Apple has worked through many localization issues in the Aqua design process
- media reviews of your product will be more positive; reviewers easily target software that doesn't look or behave the way "true" Macintosh applications do

<span id="page-19-3"></span>The implementation of Apple's human interface principles make the Macintosh what it is: intuitive, friendly, elegant, and powerful.

## <span id="page-19-1"></span>Tools for Applying the Guidelines

Tools are available to help you apply the design principles and interface specifications outlined in this document. Which tool to use depends on your application's type:

■ **Carbon:** If your application is written and compiled using the Carbon API (Universal Interfaces 3.3.2 or later), use **Interface Builder** [to import existing](http://developer.apple.com/membership/index.html)  resources and convert them to nib files. Interface Builder provides a rich environment for creating application menus, windows, dialogs, palettes, and [other standard Aqua interface elements. Interface Builder is on the Mac OS X](http://developer.apple.com/membership/index.html)  Developer Tools CD, or you can download it from the Apple Developer [Connection website \(http://developer.apple.com/membership/index.html\)](http://developer.apple.com/membership/index.html).

<span id="page-20-4"></span><span id="page-20-3"></span><span id="page-20-2"></span><span id="page-20-1"></span><span id="page-20-0"></span>If your application uses standard system resources (such as 'WIND', 'DLOG', 'DITL') and you don't wish to transition to nib files, use ResEdit or Resorcerer to modify your window layouts. If you have custom controls ('CDEF') or nonstandard interface elements that you want to display properly in Aqua, use the Appearance Manager.

- **Cocoa:** If your application is written using Cocoa, use Interface Builder to design your menus, windows, dialogs, and standard controls. (See the previous paragraphs for more information about Interface Builder.)
- <span id="page-20-5"></span>■ **Java:** If your application is written using Java, take advantage of the JFC/Swing toolkit, which provides the Aqua look and feel by default. For more information, go to http://java.sun.com/products/jfc[/.](http://java.sun.com/SFC)

If you are a Carbon developer and your application uses custom interface elements —elements drawn by your application rather than being defined as system controls—this section describes steps to make your application Aqua-compliant. If you are a Cocoa developer using the Application Kit to create your application interface, you don't need to concern yourself with this process. Cocoa developers who want to customize standard controls or create entirely new ones should subclass existing Application Kit objects.

<span id="page-20-6"></span>If you design your Carbon application to be fully compliant with the Appearance Manager, your application will work with Aqua, even if Apple makes changes to Aqua after you've finished developing your application. Using the Appearance Manager doesn't involve any additional complexity; as *Programming With the Appearance Manager* states, "The key to making your program Appearance-compliant is to allow the system to do as much of your interface work for you as possible." All Appearance Manager calls are Carbon-compliant, as well.

Here is a quick review of how to work with the Appearance Manager:

- Register with the Appearance Manager.
- <span id="page-20-7"></span>■ Use the system-defined windows supplied by the Window Manager instead of creating your own.

- <span id="page-21-4"></span><span id="page-21-3"></span>■ Use the wide assortment of system-defined controls available through the Control Manager instead of creating your own.
- When you absolutely cannot use standard interface elements, use Appearance Manager functions to make your custom elements Appearance-compliant.
- Remove table resources for windows, controls, menus, dialogs, and alerts from your application.
- <span id="page-21-2"></span>■ Make no assumptions about color values for your interface. Instead of hard-coding color values, use the Appearance Manager constants of type ThemeBrush and ThemeTextColor.
- Make no assumptions about the dimensions of menus, windows, or controls, since they could change in the future.

<span id="page-21-1"></span>For more information and code samples, see *Programming With the Appearance Manager* [and the source code for the Appearance Sample, available as part of the](http://developer.apple.com/sdk)  [Appearance Manager SDK available at http://developer.apple.com/sdk.](http://developer.apple.com/sdk)

## <span id="page-21-0"></span>If You Have a Need Not Covered by the Guidelines

If your application requires an element or a behavior that doesn't already exist, or has a need that this document doesn't address, you can extend the set of controls using these guidelines, provided that the new element or behavior supports Apple's interface design principles.

Be very cautious about creating new interface elements because you may introduce unnecessary complexity. Make sure that you can't use existing elements or a combination of them to achieve the desired result. Usability testing is essential for determining whether a new element works.

If you must invent a new element or behavior, consider the following recommendations:

■ **Build on the existing interface.** Begin with the already-defined visual and behavioral language that users are familiar with. Think about what the appearance means to people (the look) and how they expect elements to behave (the feel). Visual cues, such as the drop shadow and arrow on a pop-up menu, help people recognize how to use an element.

■ **Don't assign new behaviors to existing objects.** When you need a new behavior, design a new element for it, rather than changing the behavior of a standard element. If the same element behaves differently in different situations, the interface becomes unpredictable and harder to figure out.

## <span id="page-22-0"></span>What's New in Aqua

To help you identify areas of an existing application that need attention, this section highlights new elements introduced in Aqua, and how the Aqua interface differs from that of Mac OS 9. All of the behaviors and elements mentioned here are discussed in further detail in other chapters. When relevant, each chapter also begins with a "what's new" section that describes major differences between Mac OS 9 and Mac OS X.

- <span id="page-22-2"></span>■ **Filename extension hiding:** Mac OS X 10.1 introduces per-file hiding of filename extensions. For more information, see ["Filename Extension Hiding"](#page-24-1) [\(page 25\).](#page-24-1)
- **Keyboard focus and navigation:** Mac OS X 10.1 provides more capability for navigating through interface elements using the keyboard instead of the mouse. For more information, see ["Keyboard Focus and Navigation" \(page 168\).](#page-167-0)
- **Universal Access:** A preferences pane implemented in Mac OS X 10.1 provides functionality to assist users with special needs.
- **The Dock:** Designed to help combat onscreen clutter and aid in organizing work, the Dock displays an icon for each open application and minimized document, as well as website links and commonly used items such as System Preferences and the Trash. Dock icons display documents in preview mode. The Dock replaces the Mac OS 9 Application menu. For more information, see ["The](#page-38-0)  [Dock" \(page 39\)](#page-38-0).
- <span id="page-22-1"></span>■ **Sheets:** A sheet is a dialog "attached" to a specific window, ensuring that the user never loses track of which window the dialog belongs to. The ability to keep a dialog attached to its pertinent window enables users to take full advantage of the Mac OS X window layering model. Sheets also promote modelessness; users can continue to work in other documents or applications because they don't have to address the dialog immediately. For more information, see ["Document-Modal Dialogs \(Sheets\)" \(page 93\)](#page-92-0).

- **Window layering:** In Mac OS 9 and earlier, all windows belonging to a particular application are in the same layer. In Mac OS X, document windows and each application's main window are in their own layers, so documents from different applications can be interleaved. Clicking a window to bring it to the front doesn't disturb the layering of any other window.
- **Icons:** Graphic limitations of earlier operating systems constrained icons to a two-dimensional style. Mac OS X icons, on the other hand, are "photo-illustrative": they approach photo-realism while still providing the flexibility of stylized illustrations.
  - A new concept in Mac OS X is classifying applications by role; for example, user applications, utilities, and administrator's tools. Each icon genre has its own icon style. When icons are next to one another—in the Dock, for example—the user can easily classify them because of their visually distinct genre. For more information, see ["Icon Genres and Families" \(page 192\).](#page-191-0)
- **Drawers:** A drawer is a subwindow that slides out from a parent window, and that the user can open or close (reveal or hide). A drawer contains controls that are accessed frequently but don't need to be visible at all times. For more information, see ["Drawers" \(page 85\)](#page-84-1).
- **Lists:** There are new, standardized looks for column browsers (such as seen in the column view of a Finder window or in an Open dialog) and scrolling lists (such as seen in the list view of a Finder window). These two types of lists are available to Carbon developers via the new data browser functions. The data browser replaces the original List Manager and provides substantially more flexibility and functionality. Cocoa developers can implement these list types using the NSOutlineView and NSBrowserView classes. For more information, see ["Text Fields and Scrolling Lists" \(page 137\)](#page-136-0).
- **Controls:** All controls have a new appearance in Aqua. New controls include round buttons for navigation and combination boxes (pop-up menus that also allow for user input). See ["Controls" \(page 115\).](#page-114-0)
- **Menus:** There's a new application menu, which contains items that apply to the application as a whole, and a new Window menu. Dynamic menus now work while open (commands can be toggled with the Option key). Sticky menus remain open without timing out. For more information, see ["Menus" \(page 43\)](#page-42-0).
- <span id="page-23-0"></span>■ **Help tags:** Help tags replace Balloon Help as the mechanism for answering "what's that?" interface questions. For more information, see ["Help Tags"](#page-221-1) [\(page 222\).](#page-221-1)

- **Fonts:** The default system font is Lucida Grande, rather than Chicago or Charcoal. Application developers should note that many of the standard Mac OS 9 fonts have been removed from Mac OS X. For more information, see ["Fonts" \(page 189\)](#page-188-0).
- **Keyboard commands:** There are several new reserved keyboard equivalents, including Command-H for "Hide <appName>" and Command-M for Minimize. For more information, see ["Keyboard Equivalents" \(page 172\)](#page-171-0).
- **Toolbars:** For Cocoa developers, Mac OS X introduces a standard control for customizable toolbars with a new Aqua appearance and behavior. For more information, see ["Toolbar Icons" \(page 201\)](#page-200-0).
- **User domain directories.** Mac OS X defines a suite of user directories for new user accounts. These directories are provided to assist the user in organizing related types of files, provide a default location for task-specific applications (such as iMovie), and facilitate transferring files to and from iDisks. For more information, see ["File Location" \(page 235\)](#page-234-0).

## <span id="page-24-1"></span><span id="page-24-0"></span>Filename Extension Hiding

With filename extension hiding, every file on the system that has a specific format can have an extension indicating that format, but users don't need to be aware of the extension. When a user copies a file to a computer that uses another operating system, the filename extension gives the system the information it needs to handle the file correctly.

Applications can store type information of filename extensions and still present a readable user-visible name. Filename extensions are hidden by default, but users can choose to display a document's filename extension by deselecting the "Hide extension" checkbox in the expanded Save dialog, and can choose to show all filename extensions in Finder Preferences.

Applications that already write out filename extensions for interoperability purposes now provide an enhanced user experience; these filename extensions can be hidden in Mac OS X but automatically get transferred with the file as it moves to a non-HFS file system. For example, when a user uploads a website containing

Introduction to the Aqua Human Interface Guidelines

HTML and movie files, because the movie files already have filename extensions, they don't need to be renamed, and links in associated Web pages function properly.

To preserve the "what you see is what you typed" user experience, while supporting robust interoperability by using filename extensions to indicate file format, applications have several responsibilities. Apple recommends that applications adopt the following behavior:

- All document files should have an extension indicating the file's format.
- When displaying filenames in the user interface, applications should use the file's **display name**. Mac OS X 10.1 includes a function to get the display name.
- When saving files, users should be able to control whether filename extensions are hidden. For more information, see ["Saving, Closing, and Quitting Behavior"](#page-100-0) [\(page 101\).](#page-100-0)
- Applications should save newly created document files with a filename extension, for easy exchange with other operating systems and other users over the Internet. This filename extension can be hidden, as described above.
- When opening and saving a document file, applications should preserve the value of the document filename extension hidden flag and should preserve the existing filename extension unless the user creates a new document file by choosing Save As.
- When saving a document file without an extension as a new file in a Save As operation, applications should add an extension, as they would when creating a new document file.

<span id="page-26-3"></span><span id="page-26-0"></span>Products from Apple Computer are designed using a number of basic principles of human-computer interaction. This chapter presents these principles, and also points out what to consider for worldwide compatibility and universal access. Keep these considerations in mind as you design your product.

## <span id="page-26-1"></span>Human Interface Design Principles

This section provides a theoretical base for the wealth of practical information on implementing the Aqua interface elements presented in the rest of this book.

You'll undoubtedly find that you can't design in accordance with all of the principles all the time. In those situations, you'll have to make decisions based on which principle or set of principles is most important in the context of the task you're solving. User testing is often an excellent way to decide between conflicting principles in a particular context.

## <span id="page-26-4"></span><span id="page-26-2"></span>Metaphors

Take advantage of people's knowledge of the world by using metaphors to convey concepts and features of your application. Use metaphors that represent concrete, familiar ideas and make the metaphors obvious, so users can apply a set of expectations to the computer environment. For example, the Macintosh uses the metaphor of file folders for storing documents; people can organize their hard disks in a way that's analogous to the way they organize file cabinets.

Metaphors in the computer interface suggest a use for something, but that use doesn't necessarily define or limit the implementation of the metaphor. The Trash, for example, doesn't have to limit its contents to the number of items an actual wastebasket could contain. Try to strike a balance between the metaphor's suggested use and the computer's ability to support and extend the metaphor.

### <span id="page-27-2"></span><span id="page-27-0"></span>Direct Manipulation

Direct manipulation allows people to feel that they are directly controlling the objects represented by the computer. According to this principle, an onscreen object should remain visible while a user performs an action on it, and the impact of the action should be immediately visible. For example, a user moves a file by dragging its icon from one location to another. The drag-and-drop feature enables users to drag selected text directly into another document.

### <span id="page-27-3"></span><span id="page-27-1"></span>See-and-Point

People interact with the interface by pointing at onscreen objects with a device, typically a mouse. The Macintosh operating system works according to two fundamental paradigms, both of which assume that users can see what they're doing onscreen at all times and can point at what they see. The paradigms are based on a general form of user action: noun-then-verb.

In one paradigm, the user selects an object (the noun) and then chooses the action to be performed on the object (the verb). All actions available for a selected object are listed in the menus, so a user who is unsure of what to do next can scan through them. Users can choose an available action without having to remember a specific command.

In the second paradigm, the user drags an object (the noun) onto another object that has an action (the verb) associated with it (dragging a document icon to a folder, for example). The user doesn't choose a menu command, but it's clear what happens to an object when it's placed on another one. For this paradigm to work, the user must recognize what objects are for; the fact that the Trash looks like its real-world counterpart makes the interface easier to use.

### <span id="page-28-2"></span><span id="page-28-0"></span>Consistency

Consistency in the interface allows people to transfer their knowledge and skills from one application to any other. Use the standard elements of the Aqua interface to ensure consistency within your application and to benefit from consistency across applications. Ask yourself the following questions when thinking about consistency in your product.

Is your product consistent

- within itself?
- with earlier versions of your product?
- with Aqua interface standards?
- in its use of metaphors?
- with people's expectations?

Matching everyone's expectations is the most difficult kind of consistency to achieve, since your product is likely used by an audience with a wide range of expertise. You can address this problem by carefully weighing the consistency issues in the context of your target audience and their needs.

### <span id="page-28-3"></span><span id="page-28-1"></span>WYSIWYG (What You See Is What You Get)

In applications that enable users to format data for printing, make sure there are no significant differences between what the user sees onscreen and what the user receives after printing. When the user makes changes to a document, display the results immediately; the user shouldn't have to wait for a printout or make mental calculations of how the document will look when printed. Use a print preview function if necessary.

People should be able to find all the available features in your application. Don't hide features by using abstract commands. For example, menus present lists of commands so people can see their choices instead of having to remember command names.

### <span id="page-29-3"></span><span id="page-29-0"></span>User Control

Allow the user, not the computer, to initiate and control actions. Some applications attempt to take care of the user by offering only alternatives judged good for the user or that protect the user from having to make detailed decisions. This approach mistakenly puts the computer, not the user, in control.

The key is to create a balance between providing users with the capabilities they need to get their work done and helping them avoid dangerous irreversible actions. For a situation in which a user may destroy data accidentally, for example, you can provide a warning, and still allow the user to proceed if desired.

## <span id="page-29-2"></span><span id="page-29-1"></span>Feedback and Dialog

Keep users informed about what's happening with your product. Provide feedback as they do tasks. When a user initiates an action, provide some indicator—visual, auditory, or both—that your application has received the user's input and is operating on it.

Users want to know that a command is being carried out or, if it can't be carried out, they want to know why not and what they can do instead. When used sparingly, animation is one of the best ways to show a user that a requested action is being carried out. When a user clicks an icon in the Dock, for example, the icon bounces to let the user know that the application or document is in the process of opening. In Mac OS X, the kernel environment detects when your application doesn't respond to events for 2 seconds and automatically displays a busy cursor.

For operations that don't execute immediately, use a progress bar to provide useful information about how long the operation will take. See ["Progress Indicators and](#page-134-0)  [Relevance Controls" \(page 135\).](#page-134-0)

Provide direct, simple feedback that people can understand. In error messages, for example, spell out exactly what situation caused the error ("There's not enough space on that disk to save the document") and possible actions the user can take to rectify it ("Try saving the document in another location"). For more information, see ["Writing Good Alert Messages" \(page 232\).](#page-231-1)

### <span id="page-30-4"></span><span id="page-30-0"></span>Forgiveness

You can encourage people to explore your application by building in forgiveness that is, making most actions easily reversible. People need to feel that they can try things without damaging the system; create safety nets, such as the Undo command, so people feel comfortable learning and using your product.

Always warn people before they initiate a task that will cause irretrievable data loss. If alerts appear frequently, however, it may mean that the program has some design flaws; when options are presented clearly and feedback is timely, using a program should be relatively error-free.

## <span id="page-30-5"></span><span id="page-30-1"></span>Perceived Stability

The Macintosh interface is designed to provide an understandable, familiar, and predictable environment.

To give users a visual sense of stability, the interface defines many consistent graphics elements, such as the menu bar, window controls, and so on.

To give users a conceptual sense of stability, the interface provides a clear, finite set of objects and a clear, finite set of actions to perform on those objects. For example, when a menu command doesn't apply to a selected object, it is shown dimmed rather than being omitted.

To help preserve the perception of stability, when a user sets up his or her onscreen environment in a certain layout, it should stay that way until the user changes it.

### <span id="page-30-2"></span>Aesthetic Integrity

<span id="page-30-3"></span>Aesthetic integrity means that information is well organized and consistent with principles of visual design. Your product should look pleasant on screen even when viewed for a long time.

Keep graphics simple, and use them only when they truly enhance usability. Don't overload the user with icons or put dozens of buttons in windows or dialogs. Don't use arbitrary symbols to represent concepts; they may confuse or distract users.

Match a graphic element with users' expectations of its behavior. Don't change the meaning or behavior of standard items. For example, always use checkboxes for multiple choices; don't use them sometimes for exclusive choices.

### <span id="page-31-1"></span><span id="page-31-0"></span>Modelessness

As much as possible, allow people to do whatever they want at all times. Avoid using modes that lock the user into one operation and don't allow the user to work on anything else until that operation is completed.

Most acceptable uses of modes fall into one of the following categories:

- Short-term modes in which the user must constantly do something to maintain the mode. Examples are holding down the mouse button to scroll text or holding down the Shift key to extend a text selection.
- Alert modes, in which the user must rectify an unusual situation before proceeding. Keep these modes to a minimum. See ["Types of Dialogs and When](#page-91-0)  [to Use Them" \(page 92\)](#page-91-0) for more information.

Other modes are acceptable if they do one of the following:

- They emulate a familiar real-life situation that is itself modal. For example, choosing different tools in a graphics application resembles the real-life choice of physical drawing tools.
- They change only the attributes of something, not its behavior. The boldface and underline modes of text entry are examples.
- They block most other normal operation of the system to emphasize the modality. Examples include a dialog that makes all menu commands except Close unavailable and certain error conditions.

If an application uses modes, there must be a clear visual indicator of the current mode, and it should be very easy for users to get in and out of the mode. For example, in many graphics applications, the pointer can look like a pencil, a cross, a paintbrush, or an eraser, depending on the function (the mode) the user selects.

## <span id="page-32-0"></span>Knowledge of Your Audience

<span id="page-32-2"></span>Identifying and understanding your target audience are important first steps when designing your product. The best way to make sure your product meets the needs of your customers is by exposing your design to their scrutiny. You can do this during every phase of the design process to help reveal what works about your product as well as its flaws. The improvements you make as a result of prototype testing can translate into competitive advantages, increased sales, and enhanced customer satisfaction.

It's useful to create scenarios that describe a typical day in the life of a person you think uses the type of product you're designing. Think about the different environments, tools, and constraints that people deal with. If possible, visit actual workplaces and study how people do their jobs.

Analyze the steps necessary to complete each task you anticipate people wanting to accomplish with your product. Look at how they perform similar tasks without a computer. Then design your product to facilitate those tasks, using a step-by-step approach.

Throughout the design process, use people who fit your audience description to test your prototypes. Listen to their feedback and try to address their concerns. Develop your product with people and their capabilities—not computers and their capabilities—in mind.

## <span id="page-32-1"></span>Worldwide Compatibility

<span id="page-32-3"></span>Macintosh system software is designed to address the complex problems you'll encounter when you create an application designed to be compatible with regional, linguistic, and writing system differences around the globe.

It's much easier to include worldwide compatibility from the beginning of your development process rather than try to incorporate support for script systems after your product is complete. Before you develop software for worldwide use, consider the issues discussed in the following sections.

### <span id="page-33-2"></span><span id="page-33-0"></span>Cultural Values

Make sure that visible interface elements can be localized (translated into other languages and adapted for use in other countries). Whenever you design a user interface, consider that various regions of the world may differ in their use of color, graphics, calendars, text, and the representation of time. Specific objects or symbols (such as wall outlets and the \$ sign) may also have a different appearance, or not be understood, in other countries.

Graphics can enhance your application, but certain images can be offensive to certain audiences. Cultures assign varying values and characteristics to living creatures, plants, and inanimate objects. For example, in the United States the owl is a symbol of wisdom and knowledge, whereas in Central America the owl represents witchcraft and black magic. It's a good idea to avoid the use of seasons, holidays, or calendar events in software that you expect to distribute worldwide. If you include images that represent holidays or seasons—such as Christmas trees, pumpkins, or snow—be sure they can be localized.

Different calendars are used to mark time around the world. The United States and most of Europe observe time according the Gregorian calendar. The traditional Arabic calendar, the Jewish calendar, and the Chinese calendar are lunar rather than solar. In many places, time is marked according to one calendar for business and government purposes and another for religious events. Make your application flexible in handling dates; you also may want to provide the user with a way to change the representation of time. Use the text utilities to handle numbers, dates, and sorting.

## <span id="page-33-3"></span><span id="page-33-1"></span>Language Differences

Translating text is a sophisticated, delicate task. Avoid using colloquial phrases or nonstandard usage and syntax. Carefully choose words for menu commands, dialogs, and help text. Translated text can grow up to 50 percent longer than U.S. English text.

<span id="page-34-4"></span>Potential grammar problems may arise with error messages. Use complete sentences whenever possible. Don't use phrases that you then concatenate to create sentences; the word order may become completely different in another language, rendering the message nonsensical when translated. For example, word order in German usually places the verb at the end of a sentence. For more information on handling text in other languages, see *Inside Mac OS X: System Overview,* and *Inside Macintosh: Text.*

### <span id="page-34-5"></span><span id="page-34-0"></span>Text Display and Text Editing

<span id="page-34-8"></span>Writing systems differ in the direction in which their characters and lines flow, the size of the character set used, and whether certain characters are context dependent. Mac OS 9 and earlier relied on WorldScript and the Script Manager, which used a different character set for each script system. Mac OS X supports Unicode, a single character set for most writing systems in the world. Unicode is a cross-platform, international standard for character encoding.

<span id="page-34-3"></span>Text handling for Cocoa is entirely based on Unicode. For Carbon developers, there is a new set of functions for manipulating Unicode text. For more information, go to [http://developer.apple.com/intl.](http://developer.apple.com/intl)

<span id="page-34-6"></span>No matter what level of worldwide text support you provide, it's important to avoid these common assumptions:

- Text isn't always left-aligned and read from left to right.
- <span id="page-34-7"></span>■ Text isn't always read by a person; it might be spoken through a text-to-speech converter.
- System and application fonts may change.

### <span id="page-34-1"></span>Default Alignment of Interface Elements

<span id="page-34-2"></span>When dialogs are localized, the text may become longer or shorter, and the alignment of controls may vary. For items to appear aligned in languages that read right to left, make sure the items' display rectangles are the same size.

### <span id="page-35-4"></span><span id="page-35-0"></span>Resources

It's essential to store region-dependent information in separate resources so user-visible text can be translated during localization without modification of your application's code. When you create resources, consider text size, location, and direction. Text size varies in different languages. Also, depending on the script system, the direction of text may change. Most Middle Eastern languages read from right to left. Text location within a window should be easy to change. For more information, see *Inside Mac OS X: System Overview,* available at the Apple developer website.

## <span id="page-35-1"></span>Universal Accessibility

<span id="page-35-2"></span>Millions of people have some type of disability or special need, and computers hold tremendous promise for increasing these people's productivity. Many countries, including the United States, have laws mandating that certain equipment provide access for users with a disability.

It's a good idea to build in support for universal access from the beginning of your design process rather than having to add it after your product is done.When you think about designing for the wide range of abilities in your target audience, think about increasing productivity for the entire audience; be careful not to overcompensate for the special needs of certain members. Don't let accommodations for a particular disability create a burden for people who do not have that disability.

Mac OS X has many built-in functions designed to accommodate people with special needs. Users can access these functions in the Universal Access pane of System Preferences (introduced in Mac OS X 10.1).

#### **Important**

<span id="page-35-3"></span>Your application should not override any of the accessibility features built into Mac OS X, such as the ability to access all interface functions using the keyboard instead of the mouse, or any preference that a user might select to assist with a disability.

In general, if you follow the design principles in this chapter, and the guidelines in the rest of this book, you will meet the needs of most of your users. Here are several specific accessibility requirements you should be aware of:

- The frequency of a blinking item or display must not be in the range of 2 hertz to 55 hertz, inclusive (to prevent medical complications such as seizures that can be induced in some people with blinking lights).
- When a timed response is required—such as notification that a regularly scheduled action is about to take place—at least one response method that does not require users to respond within the timed interval should be provided. Alternatively, at least one method that allows users to adjust the response time to at least 5 times the default setting should be provided.
- Alerts or other critical feedback should be provided in both audio and visual formats.

The following sections describe the main categories of disabilities and gives suggestions for specific design solutions and adaptations you can make. Keep in mind that there is a wide range of disabilities within each category, and many people have multiple disabilities.

### <span id="page-36-4"></span><span id="page-36-0"></span>Visual Disabilities

People with a visual disability have the most trouble with the display (the screen). Software that can handle different text sizes can make it easier to support people with a visual disability. If your application is specifically used to lay out onscreen elements, you can design the software with a zoom feature that increases the view of characters or graphics.

Color-vision deficiencies are problematic for some people. Don't create interfaces that use only color coding to convey important information. Color coding should always be redundant to other types of cues, such as text, position, or highlighting. If you allow users to select from a variety of colors to convey information, they can choose colors appropriate for their needs.

## <span id="page-36-3"></span><span id="page-36-2"></span><span id="page-36-1"></span>Hearing Disabilities

People with a hearing disability cannot hear auditory output at normal volume levels, or cannot hear it at all. Software should never rely solely on sound to provide information; if important cues are given with sound, they should be available

visually as well. When playing an alert or other sound intended to get the user's attention, your application should call the system alert to ensure that the audio cue also has a visual cue.

To indicate activity, hardware should have visible lights in addition to the sound generated by the mechanisms. Hardware that specifically produces sound should facilitate external amplification. For example, including a jack for external speakers or headphones allows people to amplify sound to an appropriate level.

## <span id="page-37-0"></span>Physical Disabilities

<span id="page-37-4"></span>People who have a physical disability that requires additional access methods include individuals who are without the use of a hand or an arm because of congenital anomalies, spinal cord injuries, or progressive diseases. People in this group mainly have difficulty with computer input devices, such as the mouse or keyboard, and with handling removable storage media.

<span id="page-37-5"></span>Some people have difficulty pressing more than one key at a time (required for many keyboard shortcuts, for example). Sticky Keys, which can be turned on in the Keyboard pane of Universal Access preferences, enables these users to press keys sequentially instead of simultaneously.

<span id="page-37-3"></span>Users who have difficulty with fine motor movements may be unable to use a conventional mouse or may require modifications to keyboard behavior. Keyboard preferences enables users to modify how long they must press a key before it repeats. Mac OS X 10.1 provides ways for users to complete certain actions using the keyboard instead of the mouse. When full keyboard access is on, users can navigate to and select interface items. Mouse Keys, which can be turned on in the Mouse pane of Universal Access preferences, enables users to control the mouse with the numeric keypad, so they can complete tasks such as dragging and resizing windows.

<span id="page-37-2"></span><span id="page-37-1"></span>Make sure that your application does not override any keyboard navigation setting. For more information, see ["Keyboard Focus and Navigation" \(page 168\).](#page-167-0)

If you create hardware, make sure not to impose physical barriers that would impede someone with limited or no use of the hands or arms. For example, a disk drive with a latch would be difficult to open for a user who interacts with the computer with a pencil held in the mouth.

# <span id="page-38-2"></span><span id="page-38-0"></span>3 The Dock

<span id="page-38-4"></span>Designed to help combat onscreen clutter and aid in organizing work, the always-available Dock displays an icon for each open application and minimized document. It also contains icons for several common user applications, such as Mail and System Preferences, and the Trash. The Dock provides an Aqua-compatible replacement for the Mac OS 9 application menu.

Each item in the Dock has its own rectangular area called a tile. Within each tile is an icon that represents the application, document, folder, or other item in the Dock. For most purposes, you can think of the tile and icon as synonymous, even though the icon does not completely fill the tile.

When a user opens an application, its icon appears in the Dock; when a user opens a document and clicks its minimize button, the document's icon appears in the Dock. Users can permanently add other icons to the Dock, and can customize where and when the Dock appears.

When opening new windows, position them so that they don't overlap with the user's current position of the Dock, including its unhidden position when the Dock is hidden. Carbon developers can determine the Dock's size and location using the GetAvailableWindowPositioningBounds function. Cocoa developers can use the Frame and VisibleFrame methods of the NSScreen class.

## <span id="page-38-1"></span>Dock Notification Behavior

<span id="page-38-3"></span>With Mac OS X 10.1, an open application can use its Dock tile to convey important information if needed.

### The Dock

<span id="page-39-5"></span><span id="page-39-3"></span>When appropriate, an application's Dock tile icon can include a small badge superimposed on the icon. In Mail, for example, when a user has unread email, the Dock icon displays a red circle indicating the number of new messages. This type of badging provides important information without being obtrusive or distracting.

<span id="page-39-1"></span>**Figure 3-1** An example of a badged Dock icon: The Mail application icon indicates there are unread messages

![](images/_page_39_Picture_4.jpeg)

<span id="page-39-4"></span>If an open and inactive application needs the user's attention right away and calls the Notification Manager, the application icon in the Dock bounces. This type of notification should be reserved for errors or problems that the user needs to address right away. If you implement this kind of notification, you should also provide a way for the user to turn off the animation. When your application is active, you may wish to display an alert rather than using the Notification Manager.

<span id="page-39-6"></span>To animate an application or document Dock tile in a Carbon application, look for functions that include CollapsedWindowDockTile. In Cocoa, use the SetApplicationIcon method of the NSApplication class or the SetMiniWindowImage method of the NSWindow class.

## <span id="page-39-0"></span>Dock Menus

<span id="page-39-2"></span>When a user presses and holds the mouse button on your application's tile in the Dock, a menu appears. The menu lists the application's open windows and contains these items (when the application is open): Keep In Dock, Show In Finder, and Quit. <span id="page-40-1"></span>The Dock

**Figure 3-2** The iTunes Dock icon menu

![](images/_page_40_Picture_3.jpeg)

Mac OS X 10.1 enables open applications to customize their Dock icon's menu by adding to the default items provided by the Dock. Potential additional items include common commands to initiate actions in your application when it is not frontmost, and commands that are applicable when there is no open document window. For example, a mail application could provide commands to initiate a new message or to check for new messages. Application-specific items appear above the standard Dock menu items. For information on implementing Dock menus, see *Inside Carbon: Customizing Your Application Dock Tile,* available at [http://](http://developer.apple.com/techpubs/macosx/Carbon/carbon.html) [developer.apple.com/techpubs/macosx/Carbon/carbon.html.](http://developer.apple.com/techpubs/macosx/Carbon/carbon.html)

## <span id="page-40-0"></span>Clicking in the Dock

<span id="page-40-3"></span><span id="page-40-2"></span>Clicking an application icon in the Dock should always result in a window—a document or another appropriate window—becoming active.

If the application is not open when the user clicks the Dock icon, the application opens and a new window is active. While the application is open, the Dock icon has a symbol below it.

### The Dock

<span id="page-41-2"></span>When a user clicks an open application's icon in the Dock, the application becomes active and all open unminimized windows are brought to the front; minimized document windows remain in the Dock. If there are no unminimized windows when the user clicks the Dock icon, the last minimized window should be expanded and made active. If no documents are open, the application should open a new window. (If your application is not document based, display the application's main window.)

<span id="page-41-1"></span><span id="page-41-0"></span>When the user quits the application, the icon no longer appears in the Dock, unless the user has chosen to always display it in the Dock. Users can add an application icon permanently to the Dock by choosing Keep In Dock from the Dock menu while the application is open, or by dragging the item from the Finder to the Dock.

<span id="page-42-2"></span><span id="page-42-0"></span>Menus present lists of items—commands, attributes, or states—from which the user can choose. Menus are based on the interface principle of see-and-point: People don't have to remember command names because they can view all the available options at any time. Each application, including the Finder, has its own set of menus.

This chapter describes pull-down menus in the menu bar and contextual menus, which display when the user presses or clicks an object while pressing the Control key. For information about other kinds of menus, see ["Pop-Up Menus" \(page 120\)](#page-119-0), ["Combination Boxes" \(page 123\)](#page-122-1), ["Command Pop-Down Menus" \(page 123\)](#page-122-0), and ["Pop-Up Icon Buttons and Pop-Up Bevel Buttons" \(page 128\).](#page-127-0)

## <span id="page-42-1"></span>What's New in Aqua

<span id="page-42-3"></span>Figure 4-1 (page 44) shows an example of the menu bar in Mac OS X. The region to the right of the Apple menu displays menus belonging to the active application, the Finder, in this case.

<span id="page-43-0"></span>**Figure 4-1** The menu bar

![](images/_page_43_Picture_3.jpeg)

- **Menu bar status items.** In Mac OS X 10.1, the right side of the menu bar may contain icons that display real-time status information on selected hardware or networking facilities, and provide direct access to common settings. See ["Menu](#page-60-2)  [Bar Status Items" \(page 61\).](#page-60-2) This area of the menu bar is reserved by Apple. Developers can use Dock menus (see ["Dock Menus" \(page 40\)\)](#page-39-0).
- **Apple menu.** The system-wide Apple menu has new functionality in Mac OS X. For more information, see ["The Apple Menu" \(page 52\)](#page-51-1).
- **Application menu.** This new menu displays the boldface application name and contains items pertaining to the entire application, such as Hide, Preferences, and Quit. For more information, see ["The Application Menu" \(page 53\).](#page-52-2) (The Mac OS 9 Application menu has been replaced in Mac OS X by the Dock.)
- **Window menu.** A Window menu has been introduced to aid in managing multiple open documents within an application. See ["The Window Menu"](#page-59-3) [\(page 60\).](#page-59-3)
- **Menu separators.** Pull-down menu divisions in Mac OS X are blank space (provided automatically by the Mac OS X application tools) rather than lines.
- **Sticky menus.** Sticky menus no longer close automatically after a period of time; they stay open until an action forces them to close. See ["Sticky Menus" \(page 51\)](#page-50-3).
- <span id="page-43-1"></span>■ **Dynamic menu items.** In Aqua, pull-down menu commands can be toggled while the menu is open. See ["Menu Behavior" \(page 48\).](#page-47-2)

## <span id="page-44-0"></span>Menu Elements

<span id="page-44-5"></span><span id="page-44-3"></span><span id="page-44-2"></span>Menu elements include the menu title, menu items, keyboard equivalents, submenu indicators, and separators.

**Figure 4-2** A pull-down menu and its parts

![](images/_page_44_Picture_5.jpeg)

**Note:** For information about reserved and suggested keyboard equivalents for menu items, see ["Keyboard Equivalents" \(page 172\).](#page-171-0)

## <span id="page-44-4"></span><span id="page-44-1"></span>Menu Titles

<span id="page-44-6"></span>Menu titles should be one word that appropriately represents the items in the menu. For example, the Font menu can contain names of font families such as Helvetica and Geneva, but shouldn't include editing commands such as Cut and Paste.

Menu Elements **45**

### <span id="page-45-4"></span><span id="page-45-0"></span>Menu Items

Menu item names should be one of the following:

- <span id="page-45-2"></span>■ **Actions** (verbs or verb phrases) that declare the action that occurs when the user chooses the item. For example, Save means *save my file* and Copy means *copy the selected data.* Your menu commands should fit into similar sentences.
- **Attributes** (adjectives or adjective phrases) that describe the change the command implements. Adjectives in menus *imply* an action and should fit into the sentence "Change the selected object to …" *bold,* for example.

When a menu item is unavailable—because it doesn't apply to the selected object or nothing is selected—the item appears dimmed (gray) in the menu and isn't highlighted when the user moves the pointer over it.

Capitalize the first letter of the first and last words, and the important words in phrases. For more information on proper capitalization of menu items, see ["Capitalization of Interface Elements" \(page 231\)](#page-230-0).

### <span id="page-45-3"></span><span id="page-45-1"></span>Grouping Items in Menus

Logically grouping menu items is the most important aspect of arranging your menus. Grouping items in a menu makes it easier to quickly locate commands for related tasks.

In general, place the most frequently used items at the top of the menu, but create groups of related items rather than arranging them strictly by frequency of use. For example, although the Find Next or Find Again command may be used infrequently, it should appear right below the Find command. In a menu that contains both actions and attributes, don't put actions and attributes in the same group.

Group interdependent attributes. They can be in a **mutually exclusive attribute group** (the user can select only one item, such as font size) or an **accumulating attribute group** (the user can select multiple items, such as Bold and Italic).

If a menu repeats a term more than twice, consider dedicating a menu or hierarchical menu to the term instead. For example, if you need commands like Show Info, Show Colors, Show Layers, Show Toolbox, and so on, you could create a Show menu or a submenu off of a Show item.

<span id="page-46-3"></span><span id="page-46-0"></span>How many separators to use is partly an aesthetic decision and partly a usability decision. [Figure 4-3](#page-46-1) shows a menu that depicts the right balance of grouping, contrasted with two menus showing insufficient grouping and too much grouping. Use this picture as a visual guide when trying to decide how many separators to use in your menus.

<span id="page-46-1"></span>**Figure 4-3** Grouping items in menus

![](images/_page_46_Picture_4.jpeg)

<span id="page-46-4"></span><span id="page-46-2"></span>In Mac OS X, menu separators are blank space instead of lines. The menu-drawing code in Carbon and Cocoa automatically inserts the right amount of space between menu items to form a separator.

Menu Elements **47**

## <span id="page-47-2"></span><span id="page-47-0"></span>Menu Behavior

<span id="page-47-5"></span>To choose an item in a menu, the user positions the pointer on the menu title and drags to the desired item. Each item is highlighted as it is selected. No action actually happens until the user releases the mouse button. A menu item blinks briefly to indicate that it has been activated.

By moving the pointer off a menu before releasing the mouse button, people can open and scan menus to find out what features are available, without having to actually perform an action.

<span id="page-47-3"></span>It may be appropriate in some cases to provide **dynamic menu items**—commands that change when the user presses a modifier key. For example, if the user opens the File menu in the Finder and then presses the Option key, the Close Window command changes to Close All. The system appropriately sizes the menu to hold the widest item, including Option-enabled commands.

### <span id="page-47-6"></span><span id="page-47-1"></span>Scrolling Menus

A **scrolling menu** contains more items than are visible onscreen. Your application shouldn't have any scrolling menus; they should exist only when a user adds many items to a customizable menu, such as the Font menu.

If a menu becomes too long to fit onscreen, a downward-pointing indicator appears at the bottom of the menu to show that there are more items. When the user starts to scroll, an upward-pointing indicator appears at the top of the menu to show that some items are no longer visible in that direction. When the user drags past the last visible item, the menu scrolls to show the additional items. When the last item is shown, the downward-pointing indicator disappears. This behavior happens automatically if you use the standard system menu definition procedure (MDEF).

<span id="page-47-4"></span>If the user drags back up to the top, the menu scrolls back down in the same manner. The next time the menu is opened, it appears in its original state (with the indicator at the bottom), unless the menu stores a setting, in which case the menu displays the last user-selected item.

### <span id="page-48-2"></span><span id="page-48-0"></span>Toggled Menu Items

A **toggled menu item** changes between two states each time a user chooses it. There are three types of toggled menu items:

- A group of two menu items that are opposite states; for example, Grid On and Grid Off. The state currently in effect has a checkmark next to it. If you have room in your menu, it's a good idea to display both items (rather than changing the name depending on its state) so there's less chance of confusion about each item's effect.
- One menu item whose name changes to reflect the current state; for example, Show Ruler and Hide Ruler. Use this type if your menu doesn't have room to show both states.

<span id="page-48-1"></span>Use two verbs that express opposite actions. Make sure the command name is completely unambiguous. For example, Turn Grid On and Turn Grid Off is unambiguous. Choosing the command Use Grid, however, could turn the grid on (it describes what happens as a result of choosing the command) or off (it describes the current state).

**Figure 4-4** Avoid ambiguous toggled menu items

![](images/_page_48_Picture_8.jpeg)

Menu Behavior **49**

<span id="page-49-2"></span>■ A menu item that has a checkmark next to it when it is in effect; for example, a style attribute such as Bold. Don't use this kind of toggled item to indicate the presence or absence of a feature like a grid or ruler. It's unclear whether the checkmark means that the feature is in effect or whether choosing the command turns the feature on.

<span id="page-49-4"></span><span id="page-49-3"></span>Also see ["Using Special Characters and Text Styles in Menus" \(page 63\)](#page-62-3).

### <span id="page-49-0"></span>Hierarchical Menus (Submenus)

You can use **hierarchical menus** to offer additional menu item choices without taking up more space in the menu bar. When the user points to a menu item with a submenu indicator, a submenu appears. Submenus have all the features of menus, including keyboard equivalents, status markers (such as checkmarks), and so on.

<span id="page-49-1"></span>**Figure 4-5** A hierarchical menu

![](images/_page_49_Picture_7.jpeg)

Because submenus add complexity to the interface and are physically more difficult to use, you should use them only when you have more menus than fit in the menu bar or for closely related commands. Use only *one level* of submenus.

When you use submenus, include them in a menu with a logical relationship to the choices they contain; the submenu title should clearly represent the choices it contains. Hierarchical menus work best for providing submenus of attributes (rather than actions).

A menu can contain both standard menu items and submenu titles.

## <span id="page-50-6"></span><span id="page-50-3"></span><span id="page-50-0"></span>Sticky Menus

Standard Aqua system menus and submenus are sticky: When a user clicks the menu title, the menu stays open without the user having to continue holding down the mouse button. The user can then move the pointer to an item to select it.

In Mac OS X, once a menu is opened with a click, it remains open until another action forces it to close. Such actions include

- moving the pointer to another menu title
- a click elsewhere
- a system-initiated alert
- <span id="page-50-5"></span><span id="page-50-4"></span>■ a system-initiated application switch or quit

## <span id="page-50-1"></span>Standard Pull-Down Menus (The Menu Bar)

The **menu bar** extends across the top of the main screen and contains pull-down menus. The menu bar

- is always visible and available, except in circumstances such as a slide show (see discussion below)
- always has the Apple menu (provided by the operating system), the application menu containing items that apply to the active application as a whole, a File menu, and a Window menu
- can also contain Edit and Help menus, as well as application-specific menus

<span id="page-50-2"></span>**Figure 4-6** The menu bar displayed when the Finder is active

![](images/_page_50_Figure_16.jpeg)

If there is insufficient room to display all of an application's menus, the menu bar status items are omitted. If there is still insufficient room to display all menus, the application's menus may be omitted, starting with the rightmost menu.

If your application can display full-screen images (such as slide shows), you may allow users to hide the menu bar. If you implement this feature, provide a clearly visible way, such as a button, for the user to make the menu bar reappear. If there is no button visible, pressing the Escape key or moving the mouse to the top of the screen should display the menu bar.

<span id="page-51-4"></span><span id="page-51-3"></span>If *all* of a menu's commands are unavailable (dimmed) at the same time, dim the menu title. (The Menu Manager in Carbon does this automatically if you set the kMenuAttrAutoDisable attribute.) Users should still be able to open a dimmed menu to see its contents.

For information about keyboard equivalents for pull-down menu commands, see ["Keyboard Equivalents" \(page 172\)](#page-171-0).

### <span id="page-51-2"></span><span id="page-51-1"></span><span id="page-51-0"></span>The Apple Menu

The **Apple menu** provides items that are available to users at all times, regardless of which application is active. The Apple menu's contents are defined by the system and cannot be modified by users or developers.

<span id="page-52-1"></span>**Figure 4-7** The Apple menu

![](images/_page_52_Picture_3.jpeg)

### <span id="page-52-3"></span><span id="page-52-2"></span><span id="page-52-0"></span>The Application Menu

The **application menu,** new in Mac OS X, contains items that apply to the application as a whole, rather than to a specific document or other window.

<span id="page-53-1"></span>**Figure 4-8** The Mail application menu

![](images/_page_53_Picture_3.jpeg)

### <span id="page-53-0"></span>The Application Menu Title

To help users identify the active application, the application menu title is in boldface.

In order to fit within the allotted menu bar space, the application menu title should be one word, if possible, and a maximum of 16 characters (128 pixels wide in 14-point Lucida Grande Bold). If the application name is too long, provide a short name (16 characters or fewer) as part of the application package. The Hide and Quit items should also use the short application name; the About window should use the full application name.

If you don't provide a short name, the application name is truncated from the end (and an ellipsis is added), if necessary. For more information about how to provide a short application name, see *Inside Mac OS X: System Overview,* [available at http:/](http://developer.apple.com/techpubs/macosx/macosx.html) [/developer.apple.com/techpubs/macosx/macosx.html.](http://developer.apple.com/techpubs/macosx/macosx.html) Also see *Setting Up Your Carbon Application to Use the Services Menu* at [http://developer.apple.com/](http://developer.apple.com/techpubs/macosx/Carbon/HumanInterfaceToolbox/MenuManager/menumanager.html) [techpubs/macosx/Carbon/HumanInterfaceToolbox/MenuManager/](http://developer.apple.com/techpubs/macosx/Carbon/HumanInterfaceToolbox/MenuManager/menumanager.html) [menumanager.html.](http://developer.apple.com/techpubs/macosx/Carbon/HumanInterfaceToolbox/MenuManager/menumanager.html)

### <span id="page-54-0"></span>The Application Menu Contents

- <span id="page-54-2"></span>■ **About <Application Name>.** Opens your application's About window, which contains copyright information and version number. (For more information, see ["The About Window" \(page 88\)](#page-87-0).
- <span id="page-54-4"></span>■ **Preferences and other application-specific items.** Put all commands that provide access to the application's preference dialogs first, followed by application-specific items. Put a menu separator between the About command and the Preferences command. (If your application provides document-specific preferences, make them available in the File menu.)

**Note:** Your application should present its own preferences dialogs. Applications may add panes to System Preferences only if the application's preferences apply to the system or to the user's environment as a whole. Such exceptions might include an input device that doesn't have its own interface or a server application that always runs in the background. For more information, see *Inside Mac OS X: Preference Panes,* available on the Apple developer website.

- <span id="page-54-7"></span>■ **Services.** The Services submenu provides a way for one application to offer its capabilities to another application. For example, a user could select a name in a document and choose a Services command that looks up the name using an LDAP server, starts up an email application, and opens a new message window with the found email address in the To field.
  - For more information, see *Inside Mac OS X: System Overview* and *Inside Mac OS X: Setting Up Your Application to Use the Services Menu,* available at [http://](http://developer.apple.com/techpubs/macosx/macosx.html) [developer.apple.com/techpubs/macosx/macosx.html.](http://developer.apple.com/techpubs/macosx/macosx.html)
- <span id="page-54-5"></span>■ **Hide <Application Name>.** This command should be preceded by a menu separator, and followed by Hide Others and Show All.
- <span id="page-54-6"></span><span id="page-54-3"></span>■ **Quit <Application Name>.** This last item in the application menu should be preceded by a separator. When a user chooses Quit and there are unsaved documents, present the necessary alerts (see ["Saving, Closing, and Quitting](#page-100-0)  [Behavior" \(page 101\)\)](#page-100-0).

## <span id="page-54-8"></span><span id="page-54-1"></span>The File Menu

The commands in the **File menu** provide housekeeping tasks for documents. In general, each command should apply to a single file. If your application provides document-specific preferences, they should be accessible through the File menu.

Note that the Preferences and Quit commands, which apply to a whole application, are in the application menu. If an application is not document-centered, you can rename the File menu to something more appropriate.

Several items in the File menu—Save As, Print, and Page Setup, for example—open sheets. For more information, see ["Document-Modal Dialogs \(Sheets\)" \(page 93\)](#page-92-0).

<span id="page-55-0"></span>**Figure 4-9** The File menu

![](images/_page_55_Picture_5.jpeg)

Standard File menu commands include these:

- <span id="page-55-1"></span>■ **New:** Opens a new document named "untitled" (or "untitled 2," and so on, as appropriate). If your application requires documents to be named upon creation, you can display a Save dialog (see ["Saving, Closing, and Quitting](#page-100-0)  [Behavior" \(page 101\)\)](#page-100-0). For more information about naming new document windows, see ["Opening and Naming Windows" \(page 70\)](#page-69-0).
- <span id="page-55-3"></span><span id="page-55-2"></span>■ **Open:** Displays a dialog that enables the user to open an existing document.
- **Open Recent:** The Open command should be followed by Open Recent, so people can open recently opened documents without using the Open dialog. The Open Recent submenu displays documents in the order in which they were opened, with the most recent item at the top. Cocoa provides built-in support for populating the Open Recent submenu. (Carbon does not.)

- <span id="page-56-0"></span>■ **Close:** Closes the active window. When the user chooses this command and the active document has been changed since last saved, display the Save Changes alert (see ["Saving, Closing, and Quitting Behavior" \(page 101\)](#page-100-0)). When the user presses the Option key, Close changes to **Close All.** The keyboard equivalents Command-W and Option-Command-W should implement the Close and Close All commands, respectively. The Close command and Command-W should not close utility windows.
  - In a file-based application that supports multiple views of the same file, you can include a Close File command below Close Window, to close a file and all its associated windows. If possible, include the filename in the menu (for example, Close File "Jerry's Kids"). Shift-Command-W can be used as the keyboard equivalent for Close File.
- <span id="page-56-3"></span>■ **Save:** Saves the active document, leaves the document open, and provides feedback indicating that the document is being (or has been) saved. If the document has not previously been saved, display a Save dialog (see ["Saving,](#page-100-0)  [Closing, and Quitting Behavior" \(page 101\)](#page-100-0)). Use sheets for document-specific dialogs (see ["Document-Modal Dialogs \(Sheets\)" \(page 93\)\)](#page-92-0).
- <span id="page-56-4"></span>■ **Save As:** Displays the Save dialog, which allows the user to save a copy of the active document with a new user-defined name, a new location, or both. The newly saved document remains open and active.

<span id="page-56-6"></span>**Note:** Don't use a **Save a Copy** or a **Save To** command. People might not understand the distinction between them and Save As.

- **Save All:** Saves changes to all open documents.
- **Revert to Saved:** Discards all changes made to the active document since the last time it was saved or opened. When the user chooses Revert to Saved, display an alert that warns the user about the potential data loss the operation will cause.
- <span id="page-56-1"></span>■ **Page Setup:** Opens a dialog for specifying printing parameters such as paper size and printing orientation. These parameters are saved with the document.
- <span id="page-56-2"></span>■ **Print:** Opens a dialog for specifying such options as page range and number of copies and prints the active document. These parameters apply to only the current printing operation and are not saved with the document. For more information, see ["The Printing Dialogs" \(page 112\).](#page-111-0)

<span id="page-56-5"></span>**Note:** If you need to add to the standard Print dialog, you can add items to the bottom pop-up menu. For more information, see ["The Printing Dialogs"](#page-111-0) [\(page 112\).](#page-111-0)

If your application provides document-specific preferences, make them available in the File menu.

### <span id="page-57-2"></span><span id="page-57-0"></span>The Edit Menu

The **Edit menu** provides commands that allow people to change, or edit, the contents of documents. It also provides the commands that allow people to share data, within and between applications, via the Clipboard.

<span id="page-57-5"></span>The **Clipboard** stores whatever data is cut or copied from a document until the user replaces the contents by cutting or copying new data. The Clipboard is available to all applications and its contents don't change when the user switches from one application to another.

<span id="page-57-1"></span>**Figure 4-10** The Edit menu

![](images/_page_57_Picture_7.jpeg)

Your application's Edit menu should provide the following commands. Even if your application doesn't handle text editing within its documents, these commands should be available for use in dialogs:

<span id="page-57-4"></span>■ **Undo:** The Undo command reverses the effect of the user's previous operation. When the user chooses Undo, the command changes to **Redo,** which reverses the effect of the last Undo command.

<span id="page-57-3"></span>Support the Undo command for

| ■ | operations that change the contents of a document   |
|---|-----------------------------------------------------|
| ■ | operations that require a lot of effort to recreate |
| ■ | most menu items                                     |
| ■ | most keyboard input                                 |
|   | Operations that may not be undoable include         |
| ■ | selecting                                           |
| ■ | scrolling                                           |
| ■ | splitting a window                                  |
| ■ | changing a window's size or location                |

Add the name of the last operation to the Undo and Redo commands. For example, if the user has just input some text, the command could read **Undo Typing.** If the last operation can't be reversed, change the command to **Can't Undo** and display it dimmed to provide feedback about the current state.

<span id="page-58-6"></span>If a user attempts to perform an operation that could have a detrimental effect on data and that can't be undone, warn the user. See ["Alerts" \(page 95\).](#page-94-1)

<span id="page-58-7"></span><span id="page-58-4"></span>Command-Z should be reserved as a keyboard equivalent for the Undo/Redo command.

- **Cut:** Removes the selected data and stores it on the Clipboard, replacing the previous contents of the Clipboard.
  - Command-X should be reserved as a keyboard equivalent for the Cut command.
- <span id="page-58-3"></span>■ **Copy:** Makes a duplicate of the selected data, which is stored on the Clipboard. Command-C should be reserved as the keyboard equivalent for the Copy command.
- **Paste:** Inserts the Clipboard contents at the insertion point. The Clipboard content remains unchanged, permitting the user to choose Paste multiple times. Command-V should be reserved as the keyboard equivalent for the Paste
- **Delete:** Removes selected data without storing the selection on the Clipboard. Choosing Delete is the equivalent of pressing the Delete key or the Clear key.
- **Select All:** Highlights every object in the document.

<span id="page-58-2"></span><span id="page-58-1"></span>Command-A should be reserved as the keyboard equivalent for the Select All command.

<span id="page-58-5"></span><span id="page-58-0"></span>command.

<span id="page-59-4"></span>■ **Find:** Finds specified text. In some cases—if the application is finding a file on the Internet, for example—it might make more sense to put this command in the File menu.

## <span id="page-59-6"></span><span id="page-59-0"></span>The View Menu

The **View menu** provides commands that affect what users see in a window. In the Finder, for example, the View menu contains commands for displaying windows as columns, icons, or lists.

<span id="page-59-7"></span>Commands for showing, hiding, and customizing a toolbar belong in the View menu. Create a View menu for these commands even if your application doesn't need to have other commands in the View menu. Show/Hide Toolbar should appear right above Customize Toolbar. The Show/Hide Toolbar commands are provided so that people using full keyboard access can implement these functions with the keyboard.

### <span id="page-59-5"></span><span id="page-59-3"></span><span id="page-59-1"></span>The Window Menu

The **Window menu** contains commands for managing document windows. The menu lists an application's open document windows, including minimized windows, in the order in which they were opened. If a document contains unsaved changes, a bullet appears next to its name.

<span id="page-59-2"></span>**Figure 4-11** A Window menu

![](images/_page_59_Picture_9.jpeg)

Mac OS X does not automatically add utility windows to the list in the Window menu. You can add a command to the Window menu to show or hide utility windows in your application.

The Minimize and Zoom commands are provided in the Window menu so that people using full keyboard access can implement these functions with the keyboard. Even if your application consists of only one window, include a Window menu for the Minimize command.

Window menu items appear in this order: Minimize, Zoom, <separator>, <application-specific window commands>, <separator>, Bring All to Front (optional), <separator>, <list of open documents>. The Close command should appear in the File menu, below the Open command.

<span id="page-60-5"></span><span id="page-60-4"></span><span id="page-60-3"></span>Bring All to Front brings forward all of an application's open windows, maintaining their onscreen location, size, and layering order. You can make this command an Option-enabled toggle with Arrange in Front, which brings forward all of the application's windows in their current layering order and changes their location and size so they are neatly tiled.

### <span id="page-60-6"></span><span id="page-60-0"></span>The Help Menu

<span id="page-60-7"></span>If your application provides onscreen help (and it should), the Help menu is the rightmost menu. The first item is the name of the application and the word "Help" (Mail Help, for example). If necessary, you can add more items to the Help menu. For information about creating help content, see ["Help" \(page 219\).](#page-218-0)

### <span id="page-60-2"></span><span id="page-60-1"></span>Menu Bar Status Items

Reserved for use by Apple, the right side of the menu bar may contain items that provide feedback on and access to certain hardware or network settings. The icon for the battery strength indicator, for example, dynamically displays the current state of the battery; clicking the icon displays a menu that enables users to change common battery settings. Users can display or hide a menu bar status item in the appropriate preferences pane.

#### **Important**

Don't create your own menu bar status items. Use the Dock menu functions to open a menu from your application's icon in the Dock.

<span id="page-61-2"></span>If there is not enough room in the menu bar to display all menus, menu bar status items are removed first.

## <span id="page-61-0"></span>Contextual Menus

Many interface elements display a **contextual menu** when the user presses the Control key while clicking or pressing the item. The contextual menu provides convenient access to often-used commands associated with the item.

<span id="page-61-1"></span>**Figure 4-12** A contextual menu in a document (left) and in the Finder

![](images/_page_61_Picture_6.jpeg)

![](images/_page_61_Picture_7.jpeg)

- **Behavior:** A contextual menu behaves like a standard pull-down menu, except that moving the pointer off a contextual menu and onto a standard pull-down menu doesn't activate the second menu; the user must click once to close the contextual menu and again to open the second menu.
  - Contextual menus that are too long to display fully use the scrolling indicator (a downward-pointing triangle) and scroll like standard menus.
  - Don't set a default item. If the user opens the menu and closes it without selecting anything, no action should occur.
- **Contents:** You define the items in your application's contextual menus. Include a small subset of the most commonly used commands in the appropriate context.

<span id="page-62-4"></span>Never provide a contextual menu command that is not also accessible through the menu bar. Use submenus with caution and keep them to one level.

## <span id="page-62-3"></span><span id="page-62-0"></span>Using Special Characters and Text Styles in Menus

You can use several standard characters (described below) to indicate additional information in menus. Don't use other, arbitrary symbols in menus because they add visual clutter and may confuse people.

**Figure 4-13** Don't use arbitrary symbols in menus

![](images/_page_62_Picture_6.jpeg)

<span id="page-62-2"></span>![](images/_page_62_Figure_7.jpeg)

### <span id="page-62-5"></span><span id="page-62-1"></span>Using Symbols in Menus

In the Window menu, a **checkmark** appears next to the active document's name. Checkmarks can also be used in other menus to indicate that the setting applies to the entire selection. You can use checkmarks for mutually exclusive attribute groups (the user can select only one item in the group, such as font size) or accumulating attribute groups (more than one item can be selected at once, such as Bold and Italic.

Use **dashes** to indicate that an attribute applies to only part of the selection. For example, if selected text has two styles applied to it, put a dash next to each style name. When it's appropriate, you can combine checkmarks and dashes in the same menu.

**Note:** Include a menu command, such as Plain, that enables a user to remove all formatting from mixed-state text.

<span id="page-63-2"></span><span id="page-63-1"></span>Use a **bullet** next to a document with unsaved changes, and use a **diamond** for a document the user has minimized into the Dock. A minimized document with unsaved changes should have a diamond only.

**Figure 4-14** Symbols in menus

![](images/_page_63_Picture_6.jpeg)

### <span id="page-63-3"></span><span id="page-63-0"></span>Using Ellipses in Menus

An ellipsis character (…) after a menu item or button label indicates to the user that additional information is required to complete a command. You should use an ellipsis in the following cases:

- An action that requires further user input to complete or presents an alert allowing the user to cancel the action. Examples include Find, Go To, Open, Page Setup, and Print.
- An action that opens a settings window. The main function of settings windows is to allow the user to change some aspect of the application, not the document content. Examples include Set Title, Preferences, and Options.

Don't use an ellipsis in the following cases:

- An action that requires no further user input to complete and does not present an alert. Often the item to be acted upon is already selected. Examples: New, Cut, Bold, Print One, and Quit.
- An action that opens an informational, accessory, or tool window. These windows can be implemented as either utility windows (as in the case of a color palette) or modeless windows. These windows provide tools that help create or manage the content in the main window and are frequently left open to assist in accomplishing the task of the main window.

### <span id="page-64-2"></span><span id="page-64-0"></span>Using Text Styles and Fonts in Menus

<span id="page-64-4"></span><span id="page-64-3"></span>In a Style or Font menu, you can display menu items in the actual style or font so users can see what effect the text attribute will have.

Don't use text styles in menus other than a Style or Font menu.

<span id="page-64-1"></span>**Figure 4-15** A Font menu displayed with different fonts

![](images/_page_64_Picture_11.jpeg)

<span id="page-66-5"></span><span id="page-66-0"></span>Windows provide a way for people to view and interact with their data. There are various kinds of windows, each with its own function and appearance.

<span id="page-66-1"></span>**Document windows** contain file-based user data. They present a view into the content that people create and store. If the document is larger than the window, the window shows a portion of the document's contents.

<span id="page-66-2"></span>Other windows, commonly called **utility windows**, float above other windows and provide tools or controls that users can work with while documents are open. Some utility windows are system-wide (such as those of type kUtilityWindowClass in Carbon). To create windows such as tools palettes in Carbon, use kFloatingWindowClass. In Cocoa, create a window specifying NSUtilityWindowMask as the style mask or call setFloatingPanel:YES.

<span id="page-66-4"></span><span id="page-66-3"></span>Some applications are not document-based. Such applications typically still have at least one main window, which can use the standard Aqua document window features.

**Note:** Dialogs and alerts are also types of windows; they are discussed in ["Dialogs" \(page 91\).](#page-90-0)

## <span id="page-67-0"></span>What's New in Aqua

- <span id="page-67-6"></span><span id="page-67-3"></span>■ **Filename extension hiding:** Mac OS X 10.1 introduces per-file hiding of filename extensions. For more information, see ["Filename Extension Hiding"](#page-24-0) [\(page 25\).](#page-24-0) If your application creates documents, new document titles should reflect the user's preference. This feature is described in context in ["Saving,](#page-100-0)  [Closing, and Quitting Behavior" \(page 101\)](#page-100-0).
- **Window layering:** In Mac OS 9 and earlier, all windows belonging to a particular application are in the same layer. In Mac OS X, each document exists in its own layer, so documents from different applications can be interleaved. Clicking a window to bring it to the front doesn't disturb the layering of any other window.

<span id="page-67-4"></span>A window's depth in the layers is determined by when the window was last accessed. You can bring all windows of a given application forward by clicking the application's icon in the Dock or by choosing Bring All to Front in the application's Window menu.

To ensure that alerts and other dialogs don't get lost amidst windows from different applications, and to provide greater modelessness, Mac OS X introduces a new type of dialog called *sheets*. See ["Document-Modal Dialogs](#page-92-0)  [\(Sheets\)" \(page 93\).](#page-92-0)

- **Click-through:** In Mac OS X, the user can activate many items on an inactive window with a single click, rather than having to click once to activate the window and again to activate the item. For more information, see ["Click-Through" \(page 78\)](#page-77-3).
- **Drawers:** A drawer is a child window that slides out from a parent window, and which the user can open or close (reveal or hide). For more information, see ["Drawers" \(page 85\)](#page-84-3).
- <span id="page-67-7"></span><span id="page-67-5"></span><span id="page-67-2"></span><span id="page-67-1"></span>■ **Window controls:** The standard window controls—the close box, zoom box, scroll bars, and so on—have been redesigned in Aqua. In Mac OS X, the window shade feature is replaced by the minimize button, which puts the window in the Dock. Users can also double-click a window's title bar to put it in the Dock. Moving and resizing a window displays the actual window at all times, rather than the outline displayed in Mac OS 9.

## <span id="page-68-0"></span>Window Appearance and Behavior

<span id="page-68-5"></span><span id="page-68-2"></span>Every document and utility window should have a title bar and a close button. Even if the window does not have an actual title (a tools palette, for example), the user should be able to move the window by dragging the title bar.

<span id="page-68-7"></span>A standard document window has

- <span id="page-68-4"></span>■ a title bar
- a resize control
- <span id="page-68-3"></span>■ scroll bars (if not all the window's contents are visible)
- <span id="page-68-6"></span>■ close, minimize, and zoom buttons, although only the close button must be present at all times

<span id="page-68-1"></span>**Figure 5-1** Standard window parts

![](images/_page_68_Picture_10.jpeg)

<span id="page-69-3"></span>When a document has unsaved changes, the close button displays a dot. Carbon developers can set this control with the SetWindowModified function. In Cocoa, use the setDocumentEdited: method in the NSWindow class.

<span id="page-69-1"></span>**Figure 5-2** The close button in its unsaved changes state

![](images/_page_69_Picture_4.jpeg)

<span id="page-69-5"></span>After a document is saved for the first time, a **proxy icon** appears in the title bar. Users can manipulate this icon as if they were manipulating the corresponding file-system object. For example, you can drag a document's proxy icon to a folder in the Finder. A proxy icon appears in its normal state as long as the state of the document and the file system object are the same. When a document has unsaved changes, its proxy icon appears dimmed. Command-clicking the title or the proxy icon displays a pop-up menu illustrating the document path.

<span id="page-69-2"></span>**Figure 5-3** Document path pop-up menu, opened by Command-clicking the proxy icon

![](images/_page_69_Picture_7.jpeg)

## <span id="page-69-4"></span><span id="page-69-0"></span>Opening and Naming Windows

Users can open a document window by

- double-clicking a document icon in the Finder
- selecting the document in the Finder and choosing open from the File menu or pressing Command-O

### Windows

- choosing a file from an Open dialog
- choosing the New command from the File menu

<span id="page-70-3"></span><span id="page-70-1"></span>When your application displays a new document window, name it "untitled"; leaving it lowercase makes it more obvious that the window doesn't have a name and encourages people to save the document.

<span id="page-70-2"></span>If the user chooses New again before saving the first untitled window, name the second window "untitled 2," and so on. Add numbers to window titles only when there is more than one open untitled window. Don't put a "1" on the first untitled window, even after the user opens other new windows. If the user dismisses all untitled windows by saving or closing them, then the next new document should start over as "untitled," the next should be "untitled 2," and so on.

<span id="page-70-4"></span><span id="page-70-0"></span>**Figure 5-4** Appropriate titles for a series of unnamed windows

![](images/_page_70_Picture_7.jpeg)

<span id="page-71-0"></span>**Figure 5-5** Examples of correct and incorrect window titles

![](images/_page_71_Figure_3.jpeg)

<span id="page-71-2"></span>When the user opens an existing document, display its name exactly as it appears in the Finder.

<span id="page-71-1"></span>**Note:** In Mac OS X 10.1, filename extensions (".jpg," for example) are, by default, not visible to users, but a user can choose to show extensions on all filenames or on a particular document. The document title in the title bar should display the filename extension when the user has chosen to show it. Existing documents should retain their filenames; don't add or remove a filename extension until the user chooses Save As.

### <span id="page-72-2"></span><span id="page-72-0"></span>Positioning Windows

<span id="page-72-1"></span>Whenever your application displays a window, you must decide where to put it and how big to make it. For typical document-based applications, or dialog-based applications without supporting utility windows, the preference is to open new windows visually centered on the screen. For the first window, "visually centered" placement is 63 pixels below the menu bar. Subsequent windows are moved to the right 20 pixels and down 20 pixels. Make sure that no part of a new window is obscured by the Dock.

<span id="page-73-0"></span>**Figure 5-6** "Visually centered" new window placement]

![](images/_page_73_Picture_3.jpeg)

Spaces should be equal.

If a user changes a window's initial size or location, maintain the user's choices the next time the window opens. If a user opens, moves, and closes a document window without making any other changes, save the new window position but don't modify the file's date stamp.

### Windows

Before reopening a window, make sure that the size and state are reasonable for the user's current monitor setup, which may not be the same as the last time the document was open. For example, if a user opens a document to full size on a Cinema Display, then next opens the file on an iMac, open the document in a window sized for the smaller monitor, rather than the saved size. For more information on appropriate window size, see ["Resizing and Zooming Windows"](#page-76-2) [\(page 77\).](#page-76-2)

<span id="page-74-1"></span><span id="page-74-0"></span>On a computer with more than one monitor, display the first new window visually centered in the screen containing the menu bar. If the user doesn't move that first window, display each additional window below and to the right of its predecessor. If the user moves the window, display each additional window on the screen that contains the largest portion of the frontmost window. If there is sufficient room on the screen, display subsequent windows to the lower right of the frontmost window. If there isn't enough room on the screen, display subsequent windows starting in the upper-left corner of the screen, and then continue to display additional windows slightly offset in relation to this new position. For example, if the user creates a window, drags it to a second monitor, and then creates a new window, display the new window on the second screen.

<span id="page-75-1"></span>**Figure 5-7** Appropriate placement of a new window on a system with multiple monitors (the user moved the first window to span the screens))

![](images/_page_75_Picture_3.jpeg)

When you open several windows on multiple screens, continue to place the windows on the screen where the user is working, each new one below and to the right of its predecessor. Don't open a window so that it spans monitors; the *initial position* of a window should always be contained on a single screen.

## <span id="page-75-2"></span><span id="page-75-0"></span>Closing Windows

Users can close a window by

- choosing Close from the File menu
- pressing Command-W
- clicking the close button

When a user closes a document window, your application should

■ decide what to do with unsaved data (see ["Saving, Closing, and Quitting](#page-100-0)  [Behavior" \(page 101\)\)](#page-100-0)

■ store the window's onscreen position and size (so they can be used when the window is reopened)

## <span id="page-76-4"></span><span id="page-76-0"></span>Moving Windows

The user moves a window by dragging its title bar. As a user drags, the full window and its contents move (unlike in Mac OS 9, which dragged the window's outline).

As in Mac OS 9, pressing the Command key while dragging an inactive window moves the window but does not make it active.

Your application should never allow users to move a window to a position from which they can't reposition it.

### <span id="page-76-3"></span><span id="page-76-2"></span><span id="page-76-1"></span>Resizing and Zooming Windows

Your application determines the minimum and maximum window size. Base these sizes on the resolution of the display and on the constraints of your interface. For document windows, try to show as much of the content as possible, or a reasonable unit, such as a page.

<span id="page-76-5"></span>Your application also sets the values for the initial size and position of a window, called the **standard state.** Don't assume that the standard state should be as large as possible; some monitors are much larger than the useful size for a window. Choose a standard state that is best suited for working on the type of document your application creates.

The user can't change the standard size and location of a window, but your application can change the standard state when appropriate. For example, a word processor might define the standard size and location as wide enough to display a document whose width is specified in the Page Setup dialog.

The user changes a window's size by dragging the size control in the lower-right corner. As a user drags, the visible content in the window changes. The upper-left corner of the window remains in the same place and the appearance of the visible contents stays the same. In Mac OS X, the actual window contents are displayed at all times, rather than only the window outline displayed in Mac OS 9.

<span id="page-77-7"></span><span id="page-77-6"></span>If the user changes a window's size or location by at least 7 pixels, the new size and location is the **user state.** The user can toggle between the standard state and the user state by clicking the **zoom button.** When the user clicks the zoom button of a window in the user state, first determine the appropriate size of the standard state. Move the window as little as possible to make it the standard size, and keep the entire window on the screen.

When a user with more than one monitor zooms a window, the standard state should be on the monitor containing the largest portion of the window, not necessarily the monitor with the menu bar. This means that if the user moves a window between monitors, the window's position in the standard state could be on different monitors at different times. The standard state for any window must always be fully contained on a single monitor.

### <span id="page-77-4"></span><span id="page-77-0"></span>Active and Inactive Windows

People should be able to open as many windows as they want, but they interact with only one at a time. The **active window** is frontmost and is visually distinct from the other windows onscreen. The controls in active windows have color, which is absent from inactive controls.

<span id="page-77-2"></span>**Figure 5-8** Window controls in active and inactive states

![](images/_page_77_Picture_7.jpeg)

### <span id="page-77-5"></span><span id="page-77-3"></span><span id="page-77-1"></span>Click-Through

An item that provides click-through is one that a user can activate on an inactive window with one click, rather than clicking first to make the window active and then clicking the item. Click-through provides greater efficiency in performing such

tasks as closing or resizing inactive windows, and copying or moving files. In many cases, however, click-through could confuse a user who clicks an item unintentionally.

Click-through is not a property of a class of controls; any control could support click-through in many contexts, but the same control could disable click-through when its use could be destructive in a particular context.

In an inactive window, an item that provides click-through has its text or glyph (such as arrows) in 100-percent black; if the item usually has color (such as a radio button), it is colorless in its click-through state. Items that do not provide click-through appear in their disabled state (50-percent dimmed).

<span id="page-78-0"></span>**Figure 5-9** An inactive window with controls that support click-through

![](images/_page_78_Picture_6.jpeg)

You can provide click-through for such items as

- pop-up menus
- text fields

### Windows

- window controls in title bars (close, minimize, and zoom buttons)
- title bars, including proxy icons
- toolbar buttons (when the button's action is not potentially harmful)
- scroll bars

Don't provide click-through for items or actions that

- are potentially harmful (for example, the Delete button in Mail)
- are difficult to recover from, such as
  - actions that are difficult or impossible to cancel (the Send button in Mail)
  - dismissing a dialog without knowing what action was taken (for example, it's not easy to "unsave" a document)
  - removing the user from the current context (selecting a new item in a column, for example, can change the target of the Finder window)

Clicking in one of these situations results in the window being brought forward but no action being taken.

<span id="page-80-1"></span>**Figure 5-10** The Save button on the inactive window does not support click-through

![](images/_page_80_Picture_3.jpeg)

In general, you can implement click-through for an item that provides confirmation feedback before taking place—in other words, the user can cancel the action—such as deleting a user in Users preferences. If you want to implement click-through on an item that doesn't provide confirmation feedback, consider how difficult it will be for the user to undo the action. For example, in Mail, it would be inadvisable to implement click-through for the Delete button, which deletes a message without providing feedback first, because its resulting action is harmful. You could, however, provide click-through for the Add to Favorites button in the Save dialog because its resulting action is not harmful and is fairly easy to undo.

### <span id="page-80-3"></span><span id="page-80-2"></span><span id="page-80-0"></span>Scrolling Windows

<span id="page-80-4"></span>People use **scroll bars** to view areas of a document or a list that is larger than can fit in the current window. Only the active window can be scrolled. A window can have a horizontal scroll bar, a vertical scroll bar, both, or neither.

<span id="page-81-0"></span>**Figure 5-11** The elements of a scroll bar

![](images/_page_81_Picture_3.jpeg)

The **scroller** size reflects how much of the document is visible; the smaller the scroller, the less of the content the user can see at that time. The scroller represents the relative location, in the whole document, of the portion that can be seen in the window.

If the entire contents of a document is visible in a window, the scroll bars do not contain scrollers. Scroll bars in inactive windows have an inactive appearance. See Figure 5-8 (page 78).

The user can use scroll bars by doing the following:

- <span id="page-81-1"></span>■ Dragging the scroller: This method is usually the fastest way to move around a document. In Mac OS X, the window's contents changes in "real time" as the user drags the scroller.
- Clicking a scroll arrow: This means, "Show me more of the document that's hidden in this direction." The scroller moves in the direction of the arrow. Each scroll arrow click moves the content one unit; your application determines what one unit equals. For example, a word processor would move a line of text per click, a spreadsheet could move one row or column. To ensure smooth scrolling effects, specify units of the same size throughout a document.
- <span id="page-81-2"></span>■ Clicking or pressing in the scroll track: Clicking advances the document by a windowful (the default) or to the pointer's hot spot, depending on the user's choice in General preferences. A "windowful" is the height or width of the

<span id="page-82-3"></span>window, minus at least one unit of overlap to maintain the user's context. This unit of overlap should be the same as one scroll arrow unit. The Page Up and Page Down keys also move the document view by a windowful.

Pressing in the scroll track displays consecutive windowfuls of the document, until the location of the indicator catches up to the location of the pointer (or until the user releases the mouse button).

It's best not to add controls to scroll bars. If you add more than one control to this area, it's hard for people to distinguish among controls and click the right one. Acceptable additions to the scroll bar include a splitter bar and a status bar. To ensure that window controls are easy to use and understand, it's best to place the majority of your features in the menus as commands. If you really want to provide additional access to features, consider creating a utility window such as a palette with buttons.

<span id="page-82-2"></span>Make sure you don't use a scroll bar when you should really use a slider. Use sliders to change settings; use scroll bars only for representing the relative position of the visible portion of a document and in scrolling lists. For more information, see ["Slider Controls" \(page 131\).](#page-130-0)

Some windows, such as utility windows, may require small scroll bars. If a window uses small scroll bars, all other controls within the window content area should also be the smaller version. For more information, see ["Using Small Versions of](#page-152-0)  [Controls" \(page 153\)](#page-152-0).

### <span id="page-82-1"></span><span id="page-82-0"></span>Automatic Scrolling

Most of the time, the user should be in control of scrolling. Your application must perform automatic scrolling in these four cases:

- When your application performs an operation that results in making a new selection or moving the insertion point (for example, when the user searches for some text and your application locates it), scroll the document to show the new selection.
- When the user enters information from the keyboard at the edge of a window, scroll the document automatically to incorporate and display the new information.

Your application determines the distance to scroll. In general, a word processor scrolls vertically by a line of text, a database or spreadsheet scrolls by one field, a graphics application scrolls to display an entire object, if possible.

- When the user moves the pointer past the edge of the window while holding down the mouse button to make an extended selection, scroll the document automatically in the direction the pointer moves.
- When the user selects something, scrolls to a new location, and then tries to perform an operation on the selection, scroll so the selection is showing before your application performs the operation.

Whenever your application scrolls a document automatically, move the document only as much as necessary. That is, if part of a selection is showing after the user performs an operation, don't scroll at all. If your application can scroll in only one direction to reveal the selection, don't scroll in both.

<span id="page-83-5"></span>When autoscrolling to a selection, try to show the selection in context. When the selection is too large to show in its entirety, it might be a good idea to show some context rather than having the selection fill the window.

### <span id="page-83-2"></span><span id="page-83-0"></span>Minimizing and Expanding Windows

<span id="page-83-6"></span><span id="page-83-3"></span>When the user clicks the **minimize button** or double-clicks the title bar, the window minimizes into the Dock. The window's icon remains in the Dock until the user clicks it again or, if it is the application's only open window, until the user clicks the application icon in the Dock. For more information, see ["Clicking in the Dock"](#page-40-0) [\(page 41\).](#page-40-0)

## <span id="page-83-7"></span><span id="page-83-1"></span>Windows With Changeable Panes

<span id="page-83-4"></span>The content of some windows changes depending on the user's selection. For example, when the user clicks one of the icons at the top of the Mail Preferences window, the display at the bottom of the window changes. Some windows, such as Displays in System Preferences, switch panes using a **tab control** (see ["Tab](#page-131-0)  [Controls" \(page 132\)](#page-131-0)).

<span id="page-84-6"></span>Windows with changeable panes should reopen in their previous state as long as the application is open, and return to their default views when the user quits. A tabbed window, for example, should open in its previous state until the user quits the application; the next time the user opens the window, its leftmost tab should be active.

## <span id="page-84-0"></span>Special Windows

<span id="page-84-7"></span>This section describes special types of windows—including drawers, utility windows, and About windows—and how each type differs from what's described elsewhere in this chapter.

### <span id="page-84-4"></span><span id="page-84-3"></span><span id="page-84-1"></span>Drawers

A **drawer** is a child window that slides out from a parent window, and which the user can open or close (show or hide) while the parent window is open. A drawer contains frequently accessed controls that don't need to be visible at all times.

<span id="page-84-5"></span>Built-in support for drawers is available to Cocoa developers via the NSDrawer class.

<span id="page-84-2"></span>![](images/_page_84_Picture_8.jpeg)

**Figure 5-12** An open drawer next to its parent window

Special Windows **85**

### <span id="page-85-0"></span>When to Use Drawers

Use drawers only for controls that need to be accessed fairly frequently but that don't need to be visible all the time. (Contrast this criterion with a utility window, which should be visible and available whenever its main window is in the top layer.) Some examples of uses of drawers include access to favorites lists, the Mailbox drawer (in the Mail application), or browser bookmarks.

Although a drawer is somewhat similar to a sheet in that it attaches to a window and slides out, the two elements are not interchangeable. Sheets are primarily intended to replace modal dialogs, as described in ["When to Use Sheets" \(page 94\)](#page-93-1), whereas drawers provide additional functionality. When a sheet is open, it is the focus of the window and it obscures the window contents; when a drawer is open, the entire parent window is still visible and accessible.

### <span id="page-85-1"></span>Drawer Behavior

The user shows or hides a drawer, typically by pressing a button or choosing a command. If a drawer contains a valid drop target, you may also wish to have the drawer open when the user drags an appropriate object to where the drawer appears.

When a drawer opens or closes, it appears to be sliding from behind its parent window, to the left, right, or down. You should ensure that a parent window's default position allows its drawer to open fully without disappearing offscreen.

To support the illusion that a closed drawer is hidden behind its parent window, an open drawer should be smaller than its parent window. When the parent window is resized vertically, an open drawer resizes if necessary to ensure that it does not exceed the height of the parent window. (A drawer can be shorter than its parent window.) The illusion is further reinforced by the fact that the inner border of a drawer is hidden by the parent window and that the parent window's shadow is seen on the drawer when appropriate.

The user can resize an open drawer by dragging its outside border. The degree to which a drawer can be resized is determined by the content of the drawer. If the user resizes a drawer to the point where content is significantly obscured, the drawer should simply close. For example, if a drawer contains a scrolling list, the user should be able to resize the drawer to cover up the edge of the list. But if the user makes the drawer so small that the items in the list are difficult to identify, the drawer should close. If the user sets a new size (that is allowable) for a drawer, the new size is used the next time the drawer is opened.

A drawer should maintain its state (open or closed) when its parent window becomes inactive, or when the window is closed and then reopened. When a parent window with an open drawer is minimized, the drawer should close; the drawer should reopen when the window is made active again.

A drawer can contain any control that is appropriate to its intended use. Follow normal layout guidelines, as stated in ["Positioning Controls in Dialogs and](#page-142-1)  [Windows" \(page 143\).](#page-142-1)

<span id="page-86-2"></span>Consider a drawer part of the parent window; don't dim a drawer's controls when the parent window has focus, and vice versa. When full keyboard access is on, a drawer's contents are included in the window components that the user can select by pressing Tab.

## <span id="page-86-3"></span><span id="page-86-0"></span>Utility Windows

You can create a modeless utility window, such as a tools palette, to present controls or settings that affect the active document window. A user can open several utility windows at a time; they float on top of document windows. When a user makes a document active, all of the application's utility windows are brought to the front, regardless of which document was active when the user opened the utility window.

<span id="page-86-1"></span>**Figure 5-13** Examples of tool palettes (utility windows)

![](images/_page_86_Picture_8.jpeg)

Special Windows **87**

<span id="page-87-3"></span>Utility windows are useful for keeping extremely important controls or information accessible at all times in the context of a user task. Because utility windows take up screen space, however, don't use them when you can solve the need with a modeless dialog (the user changes settings and then closes the dialog) or by adding a few appropriate controls to a window frame.

You need to create and maintain any utility windows for your application. Whenever your application is in the background, hide all utility windows. Utility windows should not be listed in the Window menu as documents, but you may put commands to show or hide utility windows in the Window menu.

Most utility windows don't have titles, but they do have an 11-pixel-high drag region at the top. If you don't want users to access the minimize or zoom button on a utility window, you can delete both of these buttons and leave only the close button. Don't delete only the zoom or minimize button; a utility window should have either all three title-bar controls or only the close button. You can specify the attributes for these controls in Interface Builder or, for Carbon developers, when creating windows with CreateNewWindow or CreateCustomWindow.

For information about designing Aqua palette windows, see ["Using Small Versions](#page-152-0)  [of Controls" \(page 153\)](#page-152-0).

### <span id="page-87-1"></span><span id="page-87-0"></span>The About Window

The **About window,** also called an About box, is a window that contains your application's version and copyright information. It should be modeless so the user can leave it open and perform other tasks in the application.

Your application's About window should

- <span id="page-87-2"></span>■ have a title bar and be movable
- include the close button as the only active window control (if you include the minimize and zoom buttons, dim them)
- display a centered application icon and the full application title

You can also provide text that briefly describes what the application does. The recommended version in Figure 5-14 (page 89) has an application description.

<span id="page-88-1"></span><span id="page-88-0"></span>**Figure 5-14** Examples of About windows (all specifications apply to both versions)

![](images/_page_88_Figure_3.jpeg)

All text in an About window is centered, except for the optional descriptive text, which is flush left. If you want to include a scrolling list (for credits, for example), put it between the descriptive text and the copyright information.

An About window (or splash screen) is the appropriate place for your corporate logo. Avoid putting product branding elements in document windows and dialogs.

For Cocoa developers, About window support is provided by the Application Kit. Carbon developers need to create their own or use a ".nib" file.

Special Windows **89**

Windows

<span id="page-90-3"></span><span id="page-90-0"></span>A **dialog** is a window designed to elicit a response from the user. Many dialogs the Print dialog, for example—permit the user to provide many responses at one time.

<span id="page-90-2"></span>**Alerts** are dialogs that appear when the system or an application needs to communicate information to the user. They provide messages about error conditions and warn users about potentially hazardous situations or actions.

For information about using the keyboard to interact with dialogs, see ["Keyboard](#page-167-0)  [Focus and Navigation" \(page 168\).](#page-167-0)

<span id="page-90-4"></span>For specific design information on how to lay out dialogs, see ["Layout Guidelines"](#page-142-0) [\(page 143\).](#page-142-0)

## <span id="page-90-1"></span>What's New in Aqua

- <span id="page-90-5"></span>■ **Filename extension hiding:** Mac OS X 10.1 introduces per-file hiding of filename extensions. For more information, see ["Filename Extension Hiding"](#page-24-0) [\(page 25\).](#page-24-0) This feature is also described in context in ["Saving, Closing, and](#page-100-1)  [Quitting Behavior" \(page 101\).](#page-100-1) Many of the behaviors described occur automatically with the Mac OS X Save dialog.
- **Sheets:** A sheet is a new type of dialog that is attached to a particular document or window, ensuring that the user never loses track of which window the dialog applies to. The ability to keep a dialog attached to its pertinent window enables users to take full advantage of the Mac OS X window layering model and also

- <span id="page-91-5"></span>encourages modelessness; users can work on other documents or in other applications while a sheet is open. For more information, see ["Document-Modal](#page-92-1)  [Dialogs \(Sheets\)" \(page 93\)](#page-92-1).
- **Application icon in alerts:** To help the user identify which application an alert belongs to, all alerts should display the application's icon. In rare cases, when there is a critical need to warn the user of a potentially data-damaging operation, the alert can display the caution icon (an exclamation point in a triangle) with the application icon.
- <span id="page-91-3"></span><span id="page-91-2"></span>■ **Modality:** There are very few situations in Mac OS X where a dialog must be addressed before the user is allowed to do anything else on the system. The vast majority of dialogs should be either application modal (the user must address the dialog before doing anything else in the application) or document modal (a sheet), not system modal. All modal dialogs should be movable.

## <span id="page-91-0"></span>Types of Dialogs and When to Use Them

<span id="page-91-6"></span>Your Mac OS X application can use these types of dialogs:

- <span id="page-91-4"></span>■ **Modeless:** Enables users to change settings in a dialog while still interacting with document windows; the "find and replace" feature in many word processors is an example of a modeless dialog. Modeless dialogs have title bar controls (close, minimize, and zoom buttons).
- **Document modal:** Prevents the user from doing anything else within a particular document. The user can switch to other documents in the application, and to other applications. Document-modal dialogs should be sheets, which are discussed in ["Document-Modal Dialogs \(Sheets\)" \(page 93\)](#page-92-1).
- <span id="page-91-1"></span>■ **Application modal:** Prevents the user from doing anything else within the owner application; the user can still switch applications. Most application-modal dialogs do not have the standard title bar controls (close, minimize, zoom); the user dismisses these dialogs by clicking a push button, such as OK or Cancel. Application-modal dialogs that appear as the result of the user choosing a command, such as the Open dialog in Figure 6-4 (page 100), should display a title that matches the command.

Alerts can be either document modal or application modal. If the error condition or notification applies to a single document, the alert should be documental modal (a sheet). See the Save Changes alert in Figure 6-7 (page 106) for an example. If the alert applies to the state of the application as a whole, or to more than one document or window belonging to that application, the alert should be application modal. Both the Review Changes alert for multiple unsaved documents (Figure 6-10 (page 108)) and the Save Changes alert for applications that are not document-based (Figure 6-8 (page 107)) are application modal.

## <span id="page-92-3"></span><span id="page-92-1"></span><span id="page-92-0"></span>Document-Modal Dialogs (Sheets)

A **sheet** is a modal dialog attached to a particular document or window, ensuring that the user never loses track of which window the dialog applies to. The ability to keep a dialog attached to its pertinent window enables users to take full advantage of the Mac OS X window layering model. Sheets also enable users to perform other tasks before dismissing the dialog, so there's no longer the sense of the system being "hijacked" by the application.

<span id="page-92-2"></span>You lay out sheets like any other dialog in Mac OS X. Carbon developers are responsible for creating, showing, handling the events for, and closing sheets. Other sheet behavior, such as the animation when it appears, is handled automatically by the Window Manager. Cocoa developers are responsible for loading, showing, and closing sheets. While a sheet it displayed, events are handled by the Application Kit just as for any other window. Other sheet behavior, such as the animation when it appears and is dismissed, is handled automatically by the Application Kit.

<span id="page-93-2"></span>**Figure 6-1** The Save Changes alert: An example of using a sheet to display a document-modal dialog

![](images/_page_93_Picture_3.jpeg)

### <span id="page-93-0"></span>Sheet Behavior

Sheets are displayed as an animation that appears to emerge from the window's title bar. When a sheet opens on a window near the edge of the screen, and the sheet is wider than the window it's attached to, the sheet moves the window away from the edge; when the sheet is dismissed, the window returns to its previous position.

Only one sheet may be open for a window at any one time. A sheet prevents any other operation on that window until the sheet is dismissed. If, when the user responds to a sheet, another sheet for that document must open, the first sheet closes before the second one opens.

A sheet on an active document window should cover (appear on top of) any active utility windows (if necessary). However, if the user leaves a sheet open and clicks another document in the same application, the inactive window and its sheet should go *behind* any open utility windows.

### <span id="page-93-1"></span>When to Use Sheets

Use sheets for dialogs specific to a document when the user interacts with the dialog and dismisses it before proceeding with work. Some examples of when to use sheets:

- A modal dialog that is specific to a particular document, such as saving or printing.
- A modal dialog that is specific to a single-window application that does not create documents. A single-window utility program might use a sheet to request acceptance of a licensing agreement from the user, for example.
- Other window-specific dialogs typically dismissed by the user before proceeding. Use a sheet when a dialog benefits from being attached to the window as a modal dialog, even if you might otherwise design the dialog as a modeless dialog.

### <span id="page-94-0"></span>When Not to Use Sheets

- Don't use sheets for dialogs that apply to several windows. Sheets are strictly intended to be used in situations when a particular dialog is associated only with the window to which it is attached.
- Sheets are not appropriate for modeless operations where the dialog should be left open to allow the user to observe the effects of changes applied. Such tasks are better suited to modeless dialogs, utility windows (palettes), or drawers.
- <span id="page-94-3"></span>■ Don't use a sheet on a window that doesn't have a title bar. Sheets should emerge from a definite visual edge.

## <span id="page-94-2"></span><span id="page-94-1"></span>Alerts

Alerts display messages to inform users of situations that are notable or potentially dangerous.

<span id="page-95-0"></span>**Figure 6-2** A standard alert

![](images/_page_95_Picture_3.jpeg)

An alert should contain only the following elements:

- *Alert message text.* This text, in emphasized (bold) system font, provides a short, simple summary of the error or condition that summoned the alert. Often the message is presented as a question.
- *Informative text.* This text appears in the small system font and provides a fuller description of the situation, its consequences, and how to get out of it. For example, a warning that an action cannot be undone is an appropriate use of informative text.
- <span id="page-95-2"></span>■ *Buttons* for addressing the alert. Button names should correspond to the action the user performs when pressing the button—for example, Erase, Save, or Delete.
- *The application icon.* Because of the new window layering model (described in ["What's New in Aqua" \(page 23\),](#page-22-0) an icon is necessary to make it clear to the user which application is displaying the alert.

<span id="page-95-1"></span>In rare cases, you may want to display a caution icon in your alert, badged with the application icon as shown in Figure 6-3 (page 97). A badged alert is appropriate only if the user is performing a task, such as installing software, and a possible side effect of that task would be the inadvertent destruction of data.

<span id="page-96-1"></span>Don't use a caution icon for tasks whose only purpose is to overwrite or remove data, such as Save or Empty Trash; too-frequent use of the caution icon dilutes its significance.

#### **Important**

Mac OS X dialogs should not use the different icons for "note," "caution," and "stop" alerts, as was done in Mac OS 9. Most alerts should simply show the application icon.

<span id="page-96-0"></span>**Figure 6-3** A customized alert showing the caution icon badged with an application icon

![](images/_page_96_Picture_6.jpeg)

To produce the application icon, Carbon developers should use a standard alert with either the note or stop parameter, and Cocoa developers should use NSBeginAlertSheet. To produce the rare caution icon, Carbon developers should use the caution parameter and Cocoa developers should use NSBeginCriticalAlertSheet.

For more information, see ["Layout Guidelines" \(page 143\)](#page-142-0) and ["Writing Good Alert](#page-231-1)  [Messages" \(page 232\)](#page-231-1).

## <span id="page-97-0"></span>Dialog Behavior

<span id="page-97-2"></span>When appropriate, your application's dialogs should display default values for controls and text fields so the user can verify information rather than generating it from scratch. Display a selection or an insertion point in the first location—a text entry field or a list, for example—that accepts user input.

When it provides an obvious user benefit, text in a dialog should be selectable. Some error message text, for example, could be selectable. Facilitating the copying of text (such as a serial number or a hostname) so it can be pasted accurately into another context is another example.

In dialogs that display columns and are user resizable, such as the Open dialog, as the dialog is made bigger, the columns grow and additional columns appear. All other elements remain the same size and anchor to the right, center, or left side of the dialog.

### <span id="page-97-3"></span><span id="page-97-1"></span>Accepting Changes

In general, all changes a user makes in a dialog should appear to take effect immediately. There are three possible opportunities for data validation in a dialog:

- 1. When the user types data
- 2. When the user moves out of a data field (by pressing Tab, for example)
- 3. When the user clicks a button to apply changes

It is your responsibility to make the three states as clear as possible to the user. For example, checkboxes and radio buttons update immediately and display the appropriate results.

<span id="page-97-4"></span>You need to decide when your application does error checking of user input. Possible approaches:

- Implement the input and error checking as the user tabs from one field to the next. The drawback is that it isn't clear to the user that the changes are taking effect as he or she tabs among items. The user doesn't click a button, and so isn't aware of completing an action.
- Save user input in a queue and apply it when the user clicks a button, closes the dialog, or switches to another application. If your application waits to check user-input errors until the user tries to dismiss the dialog, you may have to present an alert, thereby forcing the user to revisit the dialog. If you do error checking as the user enters input, it takes more time up front, but you can warn the user immediately when invalid data is entered.

In most cases, validating input after each keystroke is annoying and unnecessary. It's better to design your interface to automatically disallow invalid input. For example, your application could automatically convert lowercase characters to uppercase when appropriate.

In addition to error checking, you need to decide when to apply user input. In some cases, changes can take effect immediately—for example, View Options for Finder windows. In other cases, it may be appropriate to wait until the user performs an action, such as clicking an Apply button.

In a dialog that has multiple panes (selected by tabs or a pop-up menu), avoid validating data when a user switches from one pane to another.

Finally, you need to determine whether your application should automatically perform an operation based on user input or whether the user should initiate the operation, for example, by clicking a button. It's probably OK to automatically perform an operation that completes quickly and returns user control within a couple of seconds. For an operation that takes a longer time to execute, it's best to warn the user of the estimated time required and let the user initiate it.

### <span id="page-98-0"></span>The Open Dialog

<span id="page-98-4"></span><span id="page-98-3"></span><span id="page-98-2"></span><span id="page-98-1"></span>The Open dialog appears when the user chooses the Open command or presses Command-O. The Open dialog is application modal (the user can switch to other applications).

Dialog Behavior **99**

If you implement an Open command, you should also include an Open Recent command so users can access recently opened documents without going through the dialog.

<span id="page-99-1"></span>**Note:** The Carbon functions in Navigation Services, introduced in Mac OS 8.5, has been enhanced to add support for Mac OS X. Its predecessor, the Standard File Package, is not supported in Mac OS X.

<span id="page-99-0"></span>**Figure 6-4** An Open dialog

![](images/_page_99_Picture_5.jpeg)

The Open dialog contain these elements:

■ A default title ("Open"); you should add your application's name to the Open dialog title—"TextEdit: Open," for example.

- A From pop-up menu that contains Favorite Places (all containers in the user's Favorites folder) and Recent Places (the five most recent folders the user opened or saved documents to). Your application specifies the default location, typically one of the predefined folders in the user's home folder. (For recommended default locations, see ["File Location" \(page 235\).](#page-234-0)) If the user selects another folder, the dialog should "remember" the user's selection the next time the dialog appears.
- A column browser for navigating the file system.
- A "Go to" text field, into which expert users can type file-system paths to navigate in the dialog. Pathnames must begin with "/" or "~".
- <span id="page-100-2"></span>■ An Add to Favorites button, which adds an alias of the chosen folder to the user's Favorites folder and immediately updates the Favorite Places list in the From pop-up menu. The Add to Favorites button is always active.
- A Cancel button and an Open (default) button.
- A resize control in the lower-right corner.

An Open dialog can include a Show pop-up menu, which allows the user to filter the type of files that appear in the list. Items that do not meet the filtering criteria appear dimmed. The system creates a list of native file types supported by the application to populate the menu. You can supplement this list with custom types and specify the default to show when the dialog opens. You should include an "All applicable files" item, but it does not have to be the default.

Open dialogs should support document preview and can support multiple selection if your application allows more than one document to be open at a time.

### <span id="page-100-3"></span><span id="page-100-1"></span><span id="page-100-0"></span>Saving, Closing, and Quitting Behavior

<span id="page-100-4"></span>As described in ["Filename Extension Hiding" \(page 25\),](#page-24-0) your application should pass in a filename extension as part of every filename. Users can control its visibility using the "Hide extension" checkbox in the expanded Save dialog; for more information, see ["The Expanded Save Dialog" \(page 103\).](#page-102-0) Existing documents do not get extensions added to or removed from their filenames unless the user chooses Save As and changes the setting in the Save dialog.

Dialog Behavior **101**

### <span id="page-101-0"></span>Save Dialogs

An application that saves the contents of individual windows—which would be most text and graphics applications—should use document-specific sheets for its Save dialogs. In Aqua, the Save dialog has two states: minimal and expanded. Clicking the disclosure button toggles between these states. If the user changes the state, the next Save dialog should open in the selected state.

### <span id="page-101-2"></span>**The Minimal Save Dialog**

The minimal Save dialog enables users to save changes to a particular document, to name or rename the document, and to choose a frequently accessed location to store it.

<span id="page-101-1"></span>**Figure 6-5** The minimal (collapsed) Save dialog

![](images/_page_101_Picture_7.jpeg)

The minimal Save dialog contains these elements:

■ "Save as" text field for the document name. (Expert users can enter pathnames by typing "/" or "~" as the first character.)

If the document has not been saved previously, your application should put the default name (such as "untitled") in this field, and the filename should be selected. If the user has chosen to make the filename extension visible, the extension is not selected.

<span id="page-102-1"></span>If the document has been saved previously and the user chooses Save As, the Save dialog should open with the document name, highlighted, in the "Save as" field. The filename extension (if it is visible) is not selected.

- Where pop-up menu, containing Favorite Places (all folders in the user's Favorites folder) and Recent Places (the five most recent folders the user opened or saved documents to). Your application specifies the default location, typically the predefined Documents folder in the user's home folder. (For recommended default locations, see ["File Location" \(page 235\).](#page-234-0)) If the user selects another folder, the dialog should "remember" the user's selection the next time the dialog appears.
- Save button (default).
- Cancel button. Dismisses the dialog and returns to the application's previous state.
- <span id="page-102-4"></span><span id="page-102-3"></span>■ A disclosure button. Clicking it displays the expanded Save dialog.

### <span id="page-102-2"></span><span id="page-102-0"></span>**The Expanded Save Dialog**

The expanded Save dialog enables the user to save a document in a location not accessible in the Where pop-up menu in the minimal Save dialog.

Dialog Behavior **103**

<span id="page-103-0"></span>**Figure 6-6** The expanded Save dialog

![](images/_page_103_Picture_3.jpeg)

Clicking the disclosure button in the minimal Save dialog displays the following:

- A column browser for navigating the file system.
- A New Folder button, which displays an application-modal dialog that asks the user to name the new folder, and then creates it.
- <span id="page-103-1"></span>■ An Add to Favorites button, which adds an alias of the chosen folder to the user's Favorites folder and immediately updates the Favorite Places list in the Where pop-up menu. The Add to Favorites button is always active.
- A "Hide extension" checkbox, which allows the user to control whether or not the filename's extension (".jpg," for example) is visible. The "Hide extension" checkbox should be selected as the default (that is, filename extensions should not appear in user-visible filenames unless the user requests them).

If the user changes the state of the checkbox for a particular document, the next new document should match the last user-selected state, even after the user quits and reopens the application. The filename in the "Save as" field updates in real time as the checkbox is selected or deselected.

These behaviors happen automatically for Cocoa developers using NSDocument. Carbon developers should set a new flag, PreserveSaveFileExtension, when calling the Save dialog, and use NavCompleteSav to set the flag to hide the filename extension.

To enable the user to specify the document's format, you can add a Format pop-up menu between the "Save as" text field and the Where pop-up menu. The system creates a list of native file types supported by the application to populate the menu. You can supplement this list with custom types and specify the default format to show when the dialog opens. When a user changes a document's type with the Format menu, the filename extension (visible or hidden) should change accordingly. Cocoa applications handle this updating automatically.

If you add other elements to customize the expanded Save dialog, they appear above the Cancel and Save buttons. All custom elements should be visible in the dialog's minimal (collapsed) state, below the Where pop-up menu. When the dialog is expanded, custom elements appear below the New Folder and Add to Favorites buttons.

<span id="page-104-1"></span>In default keyboard navigation mode, pressing Tab in the expanded Save dialog shifts the keyboard focus from the "Save as" text field to the visible columns, and then back to the text field.

### <span id="page-104-2"></span><span id="page-104-0"></span>Closing a Document With Unsaved Changes

When the user attempts to close a document that has unsaved changes, present a Save Changes alert. An application that saves the contents of individual windows like most text and graphics applications—should use document-specific sheets, like the one shown in Figure 6-7, for its Save Changes alert. In an application that can display multiple views of the same file, if the user chooses the Close File command (instead of Close Window; see ["The File Menu" \(page 55\)](#page-54-1)), open the sheet on the frontmost window and change the alert message text from "document" to "file"; after the user clicks Save or Don't Save, close all open views of the file.

Dialog Behavior **105**

<span id="page-105-1"></span>**Figure 6-7** A Save Changes alert for a document-based application

![](images/_page_105_Picture_3.jpeg)

When a Save Changes sheet is open, the document's close button and the Close command in the File menu are unavailable; the user can't close the document until the Save Changes sheet is addressed.

### <span id="page-105-2"></span><span id="page-105-0"></span>Saving Documents During a Quit Operation

In Mac OS X, users can interrupt a quit operation with documents still unsaved. For example, if a user chooses Quit and a save alert (a sheet) opens for a document, the user can work on other documents or switch to another application without addressing the save alert. To minimize the impact of such interruptions, all save alerts initiated by a Quit command should include a message that alerts users that they are in the midst of a quit operation. See Figure 6-9 (page 108) for an example.

When a user quits an application in which all open documents have been saved, all documents close immediately and the application quits.

### **Quitting an Application That is Not Document-Based**

When a user attempts to quit an application that is not document-based (the contents of many windows are saved simultaneously), present an application-modal Save Changes alert, such as the one shown in Figure 6-8 (page 107).

<span id="page-106-0"></span>**Figure 6-8** A Save Changes alert for an application that is not document-based

![](images/_page_106_Picture_3.jpeg)

### **Quitting an Application With One Unsaved Document Open**

When a user attempts to quit a document-based application and there is only one document with unsaved changes open, present a Save Before Quitting alert (such as the one shown in Figure 6-9 (page 108)) as a sheet attached to the unsaved document, perform the actions described in "The Minimal Save Dialog" (page 102), and then quit the application as appropriate.

Note that the Don't Save button, which can result in data loss, is positioned away from the "safe" buttons (Cancel and Save). The keyboard combination Command-D should be implemented for the Don't Save button.

Dialog Behavior **107**

<span id="page-107-0"></span>**Figure 6-9** The Save Before Quitting alert (sheet) that appears when the user quits with only one unsaved document

![](images/_page_107_Figure_3.jpeg)

### **Quitting an Application With Multiple Unsaved Documents Open**

When a user attempts to quit a document-based application and there is more than one document with unsaved changes open, present an application-modal Review Changes alert, such as the one shown in Figure 6-10.

<span id="page-107-1"></span>**Figure 6-10** The Review Changes alert (application modal) that appears when the user quits with more than one unsaved document open

![](images/_page_107_Picture_7.jpeg)

The appropriate action for each button is as follows:

- **Discard Changes.** Closes all documents without saving changes and quits the application.
- **Cancel.** Cancels the Quit command.
- **Review Changes.** All open documents (including those minimized in the Dock) come forward, with the unsaved documents on top. The active document presents the Save Before Quitting alert (see Figure 6-9 (page 108)). If the user clicks Save, the Save dialog appears (if the document has not previously been saved). If the user clicks Don't Save, the next unsaved document comes forward with its Save Before Quitting alert. If the user dismisses the last Save Before Quitting alert with Save or Don't Save, all documents close and the application quits.

<span id="page-108-2"></span>During the review, if the user activates another unsaved document, it should come forward with its Save Before Quitting sheet open. Already-opened Save Before Quitting sheets on other documents remain open. During the review, if the user activates a saved document, the review process continues when the next unsaved document becomes active.

<span id="page-108-1"></span>If, in the midst of a quit operation, the user clicks the application icon in the Dock or chooses Bring All to Front from the Window menu, documents should appear in this order: documents with open sheets on top, unsaved documents next, and then saved documents.

<span id="page-108-3"></span>At any time during the review process, the user can click Cancel to stop the quit operation. If the user initiates a Quit command while in the review state, the process begins again with the application-modal alert shown in Figure 6-10 (page 108).

### <span id="page-108-0"></span>Saving a Document With the Same Name as an Existing Document

<span id="page-108-4"></span>If the user types the name of a document that already exists in the same location into the "Save as" field of a Save dialog, and then clicks Save, present an application-modal alert that enables the user to confirm whether or not to replace the previous document.

Dialog Behavior **109**

<span id="page-109-1"></span>**Figure 6-11** Alert for confirming replacing a file

![](images/_page_109_Figure_3.jpeg)

### <span id="page-109-2"></span><span id="page-109-0"></span>The Choose Dialog

A Choose dialog enables the user to select an item as the target of a customized task. For example, when a user attempts to open a broken alias, the Fix Alias dialog lets the user choose another item for the alias to open. An application can have more than one Choose dialog, but only one can be open at a time. In some situations, it may be appropriate for a Choose dialog to be a sheet.

<span id="page-110-0"></span>**Figure 6-12** A Choose dialog

![](images/_page_110_Picture_3.jpeg)

### A Choose dialog

- can be opened by various commands
- can support multiple selection
- supports document preview
- can be resized with the resize control in the lower-right corner
- can include a Show pop-up menu, which allows the user to filter the type of files that appear in the list. Items that do not meet the filtering criteria appear dimmed. The system creates a list of native file types supported by the application to populate the menu. You can supplement this list with custom types and specify the default to show when the dialog opens. You should include an "All applicable files" item, but it does not have to be the default.

Dialog Behavior **111**

The dialog's default title is "Choose," but you should change it to include the name of the task. For example, if the command that brings up the dialog is Choose Picture, the dialog should be titled "Choose Picture." Also include some instructional text at the top, such as "Choose a picture to display in the background of the folder 'Documents.'" If it's helpful, also change the Choose button to something more specific.

The default location is the user's home folder. If the dialog is targeted to only volumes, the default location is the Computer directory. Files not appropriate for the target selection are dimmed; for navigation purposes, all folders are selectable. If it's appropriate for the target to be a folder, you can add a New Folder button to the Choose dialog.

<span id="page-111-1"></span>**Note:** Recent Places (in the Where pop-up menu of a Save dialog) does not record folders selected in Choose dialogs.

The Choose dialog is available to Carbon developers through Navigation Services. Cocoa developers can use a variation of the Open dialog.

### <span id="page-111-3"></span><span id="page-111-0"></span>The Printing Dialogs

<span id="page-111-5"></span><span id="page-111-4"></span><span id="page-111-2"></span>Printing dialogs include the Print dialog and the Page Setup dialog. User options are provided in the features pop-up menu, which contains panes drawn and controlled by printing dialog extensions (PDEs). PDEs are provided by the operating system, printer modules, and applications. Apple provides a number of printing dialogs.

<span id="page-112-0"></span>**Figure 6-13** A Print dialog

![](images/_page_112_Picture_3.jpeg)

If you create custom printing dialogs, follow the interface guidelines provided throughout this book and the layout guidelines described in ["Positioning Controls](#page-142-1)  [in Dialogs and Windows" \(page 143\).](#page-142-1) Here are some specific guidelines to keep in mind if you implement custom printing features.

- Make sure the item name that appears in the pop-up menu doesn't conflict with already existing menu items.
- Make sure the pane name enables a user to easily determine the options it contains.
- If you include a help button, put it in the lower-right corner of the pane's group box. To help users distinguish between the purpose of your help button and the general one (the round button with a question mark), your help button should include an icon and a text label identifying your printer.
- Make sure the features you implement are appropriate for your application. For example, an option to print in reverse order should be provided by the operating system, not your application. (Implementing this feature requires the application to know the hardware's capabilities.)
- Make interdependencies among options clear to users. For example, if a user selects double-sided printing, the option to print on transparencies should become unavailable.

Dialog Behavior **113**

### Dialogs

- Consider separating more advanced features from frequently used features. Most people, for example, won't need access to controls for specifying precise percentages of cyan, yellow, and magenta.
- Provide visual feedback (such as the preview in the Layout pane) when appropriate. A thumbnail showing the effect of changing a Tone control, for example, helps users determine desired settings.

<span id="page-113-1"></span><span id="page-113-0"></span>If you are a Carbon application developer, you can write a PDE to customize panes in the Page Setup or Print dialogs. For more information, see *Inside Mac OS X: Extending Printing Dialogs,* available at http://developer.apple.com/techpubs/ macosx/Carbon/graphics/CarbonPrintingManager/carbonprintingmgr.html[. If](http://developer.apple.com/techpubs/macosx/Carbon/graphics/CarbonPrintingManager/carbonprintingmgr.html)  [you are a Cocoa application developer, you can implement an "accessory view" by](http://developer.apple.com/techpubs/macosx/Carbon/graphics/CarbonPrintingManager/carbonprintingmgr.html)  using NSPageLayout and NSPrintPanel, both Application Kit classes.

<span id="page-114-5"></span><span id="page-114-0"></span>**Controls** are graphic objects that cause instant actions or visible results when the user manipulates them with the mouse. Standard controls include buttons, scroll bars, checkboxes, sliders, pop-up menus, and more.

<span id="page-114-4"></span><span id="page-114-3"></span><span id="page-114-2"></span>For Carbon developers, the Control Manager determines the overall appearance of all controls. For Cocoa developers, the overall appearance of interface elements is provided by the Application Kit. You are responsible for positioning the controls within your windows, according to the guidelines given here.

**Note:** In this document, control sizes are compatible with platinum appearance metrics, but layout guidelines for Mac OS X differ somewhat from Mac OS 9. Carbon developers in particular should review the material in ["Layout](#page-142-0)  [Guidelines" \(page 143\)](#page-142-0), ["Menus" \(page 43\)](#page-42-0), and ["Fonts" \(page 189\)](#page-188-0). Apple reserves the right to make changes in future releases.

## <span id="page-114-1"></span>What's New in Aqua

<span id="page-114-6"></span>All interface elements have a new look in Aqua. Controls have new dimensions, colors, and transparency. New controls include combination boxes and round navigation buttons.

## <span id="page-115-0"></span>Control Behavior and Appearance

<span id="page-115-7"></span><span id="page-115-5"></span>**Note:** The Control Manager (Carbon) and Application Kit (Cocoa) include smaller versions of some controls, for use in utility windows when necessary. The specifications listed here are for the standard size controls. If a small version of a control is available, it's shown (with its dimensions) after the standard-size version. For more information, see ["Using Small Versions of Controls"](#page-152-0) [\(page 153\).](#page-152-0)

### <span id="page-115-6"></span><span id="page-115-4"></span><span id="page-115-1"></span>Push Buttons

A **push button** is a rounded rectangle with a text label on it. Clicking a push button performs an instantaneous action, such as saving a document, completing operations defined by a dialog, or acknowledging an error message. Button names should be verbs that describe the action performed—Save, Close, Print, Delete, and so on. Don't use push buttons to indicate a state such as On or Off.

<span id="page-115-3"></span>In some circumstances, it's appropriate to implement an Apply button—for example, to permit a user to see the effect of multiple text attributes before committing to them. In cases like these, clicking Cancel should undo any of the applied changes. Be cautious about using an Apply button for operations that take a long time to implement or undo; it might not be obvious to users that they can interrupt or reverse the process.

<span id="page-115-2"></span>**Figure 7-1** Example of standard push buttons

![](images/_page_115_Picture_8.jpeg)

### <span id="page-116-4"></span><span id="page-116-0"></span>Push Button Specifications

<span id="page-116-3"></span><span id="page-116-1"></span>**Figure 7-2** Stacked push buttons

### If stacking vertically, leave a minimum of 12 pixels in between. If stacking vertically, leave a minimum of 8 pixels in between. **Standard push button Small push button** <sup>8</sup> <sup>12</sup>

<span id="page-116-2"></span>**Figure 7-3** Push button dimensions

![](images/_page_116_Figure_6.jpeg)

- **Height:** 20 pixels (fixed), not including the shadow. For small push buttons, height is 17 pixels.
- **End caps:** 14 pixels wide (fixed). For small push buttons, 10 pixels.
- **Width:** Depends on button text. If you don't specify a wide enough button, the end caps clip the text. The standard width for OK and Cancel buttons is 69 pixels, as shown in Figure 7-1 (page 116). Push buttons used in other contexts may be sized differently if appropriate.
- **Text:** System font (13-point Lucida Grande Regular). If you need to use a font larger than the system font, use a bevel button instead. For small push buttons, use the small system font (11-point Lucida Grande Regular).

- <span id="page-117-3"></span><span id="page-117-2"></span>■ **Color:** All push buttons are clear except the default button—the button selected by pressing the Return key—which uses the default color (in addition to pulsing). For example, in a dialog containing a default OK button and a Cancel button, the Cancel button is clear and the OK button uses color and pulses. When the user presses a nondefault button such as Cancel, the button acquires color and the default button loses its color. If you use standard controls, this behavior is automatic.
- **Spacing:** Leave at least 12 pixels of space between buttons placed horizontally or stacked. For small push buttons, leave at least 8 pixels.
- **Positioning:** The default button should go in the lower-right corner of the dialog. If there's a Cancel button, it should be to the left of the default button. If there's a third, or alternate, button (Don't Save, for example), it should go to the left of the Cancel button. Leave more than 12 pixels between the alternate button and Cancel; you may want to align the left edge of the button with the main dialog text, or put it 12 pixels to the right of the help button, if there is one.

## <span id="page-117-1"></span><span id="page-117-0"></span>Radio Buttons and Checkboxes

Use **radio buttons** for a set of mutually exclusive, but related, choices. A set of radio buttons should contain at least two items and a maximum of about seven. (For more than seven items, consider using a pop-up menu.) A set of radio buttons is never dynamic (changing contents depending on the context). A radio button should never initiate an action.

Use **checkboxes** to indicate one or more options that must be either on or off. Each checkbox label should clearly imply two opposite states so it's clear what happens when the box is checked or unchecked. If you can't find an unambiguous label, consider using radio buttons so you can clarify the states with two different labels.

### <span id="page-118-0"></span>Radio Button and Checkbox Specifications

<span id="page-118-2"></span>**Figure 7-4** Radio button spacing

![](images/_page_118_Picture_4.jpeg)

<span id="page-118-3"></span>Align the baselines of the label and the first button's text. The box indicates the hit region.

**Figure 7-5** Checkbox spacing

![](images/_page_118_Picture_7.jpeg)

Align the baselines of the label and the first checkbox's text. The hit region includes the checkbox border.

- **Size:** 18 x 18 pixels, including the shadow. Small radio buttons are 14 x 15 pixels. Small checkboxes are 14 x 16 pixels.
- **Label:** 8 pixels from label (colon) to control
- **Spacing:** 8 pixels of space between controls when stacked.
- **Text:** System Font (13-point Lucida Grande Regular). Small: Small system font (11-point Lucida Grande Regular).

### <span id="page-118-4"></span><span id="page-118-1"></span>Selections Containing More Than One Checkbox State

When a user selection comprises more than one state, use a dash in the appropriate checkboxes.

<span id="page-119-1"></span>**Figure 7-6** Dashes in checkboxes representing a selection with more than one state

![](images/_page_119_Picture_3.jpeg)

### <span id="page-119-3"></span><span id="page-119-0"></span>Pop-Up Menus

<span id="page-119-4"></span>Use **pop-up menus** to present a list of mutually exclusive choices in a dialog or window. Pop-up menus are used as a means of selecting one choice from a list of many. If you have a dialog with five or more radio buttons in one section, consider using a pop-up menu instead.

<span id="page-119-2"></span>**Figure 7-7** An open pop-up menu

![](images/_page_119_Picture_7.jpeg)

### A pop-up menu

- has a label to the left (in left-to-right scripts)
- has a drop shadow and a double-triangle indicator
- contains nouns (things) or adjectives (states or attributes), but not verbs (commands); use pull-down menus for commands

A pop-up menu behaves like other menus: Users drag to choose an item—which then flashes briefly and appears as the current choice—or move outside the menu to leave the current value active. An exploratory press in the menu to see what's available doesn't select a new value.

In special cases, you may want to include a command that affects the contents of the pop-up menu itself. For example, in the Print dialog, the Printer pop-up menu contains Edit Printer List, so users can add a printer to the menu; the new printer becomes the menu's default selection. Put such commands at the bottom of a pop-up menu, below a separator.

Use pop-up menus to present up to 12 mutually exclusive choices that the user doesn't need to see all the time.

Don't use pop-up menus

- for more than 12 items; use a scrolling list
- for 4 or fewer items; use radio buttons
- when more than one selection is appropriate, such as text styles (in which you can select bold and italic, for example); use checkboxes or a pull-down menu in which checkmarks appear

Be very cautious about creating a pop-up menu with submenus. Doing so hides choices too deeply and is physically difficult to use.

Bevel buttons and icon buttons can also be pop-up menus. See ["Pop-Up Icon](#page-127-2)  [Buttons and Pop-Up Bevel Buttons" \(page 128\)](#page-127-2).

### <span id="page-121-0"></span>Pop-Up Menu Specifications

<span id="page-121-2"></span><span id="page-121-1"></span>**Figure 7-8** Pop-up menu spacing

![](images/_page_121_Figure_4.jpeg)

- **Height:** 20 pixels. Small: 17 pixels.
- **Width:** Wide enough to accommodate the longest menu item.
- **Spacing:** Leave at least 12 pixels of space between stacked controls. Small: Leave at least 8 pixels of space.
- **Menu item text:** System font (13-point Lucida Grande Regular), 9 pixels from left edge and at least 9 pixels from the double-triangle section. Small: Small system font (11-point Lucida Grande Regular), 7 pixels from left edge and at least 7 pixels of space on the right.
- **Menu label text:** Emphasized system font (13-point Lucida Grande Bold), 8 pixels from text (colon) to left edge of menu. Small: Emphasized small system font (11-point Lucida Grande Bold), 8 pixels from text (colon) to left edge of menu.

### <span id="page-122-5"></span><span id="page-122-0"></span>Command Pop-Down Menus

A command pop-down menu is a menu that appears in a window rather than in the menu bar. Use of this control is limited to cases where the window is shared among multiple applications and the menu contains commands that affect the window's contents. For example, Color Picker, which can be used in any application, contains a List menu with commands that can be used to change the contents of Color Picker itself. Each application that uses the Color Picker doesn't have to populate a menu with these commands.

<span id="page-122-2"></span>**Figure 7-9** A command pop-down menu

![](images/_page_122_Picture_5.jpeg)

Command pop-down menus should contain between 3 and 12 commands. A closed command menu always displays the same text, which acts as the menu title.

### <span id="page-122-4"></span><span id="page-122-3"></span><span id="page-122-1"></span>Combination Boxes

A **combination box** (or combo box) is a text entry field combined with a pop-up menu or a drop-down scrolling list. Combo boxes are useful for displaying a list of likely choices while still allowing the user to type in an item not in the list.

<span id="page-123-1"></span>**Figure 7-10** Combo box with scrolling list and with pop-up menu (closed and open)

![](images/_page_123_Picture_3.jpeg)

The default state of the combo box is closed, with the text field empty or displaying a default selection. The default selection (not necessarily the first item in the list) should provide a meaningful clue to the hidden choices. The combo box should also have a useful label.

<span id="page-123-3"></span>Combo boxes are available for Cocoa applications. Carbon developers should use the Appearance Manager to simulate these controls.

### <span id="page-123-0"></span>Combo Box Specifications

<span id="page-123-2"></span>**Figure 7-11** Combo box dimensions

![](images/_page_123_Figure_8.jpeg)

- **Height:** 20 pixels. Small: 17 pixels.
- **Width:** Wide enough to accommodate the longest menu item.
- **Spacing:** Leave at least 12 pixels of space between stacked controls. Small: Leave at least 8 pixels of space.

- **Menu item text:** System font (13-point Lucida Grande Regular), 9 pixels from left edge and at least 9 pixels from the double-triangle section. Small: Small system font (11-point Lucida Grande Regular), 7 pixels from left edge and at least 7 pixels of space on the right.
- **Menu label text:** Emphasized system font (13-point Lucida Grande Bold), 8 pixels from text (colon) to left edge of menu. Small: Emphasized small system font (11-point Lucida Grande Bold), 8 pixels from text (colon) to left edge of menu.

### <span id="page-124-0"></span>The Text Entry Field

The user can type any appropriate characters into the text field. If the user types in an item already in the menu or list, or types in a few characters that match the first characters of an item in the menu or list, the item is highlighted when the user opens the menu or list. A user-typed item does *not* get added to the permanent menu or list.

### <span id="page-124-3"></span><span id="page-124-1"></span>The Pop-Up Menu or Scrolling List

Use a pop-up menu to display up to 12 choices. If you want to offer more than 12 items, use a scrolling list.

The user opens the menu or list by pressing the arrows to the right of the text field. The menu or list is a window that descends from the text field; the window is the same width as the text field and has a drop shadow. Don't extend the right edge of the menu or list beyond the right edge of the arrow box; if an item is too long, it gets truncated.

When the user selects an item in the menu or list, the item replaces whatever is in the text entry field and the menu or list closes. If the user presses the Up Arrow or Down Arrow key to move through the items, the selected item is highlighted and appears in the text entry field. The user can accept an item by pressing the Space bar, Enter, or Return.

<span id="page-124-2"></span>If the menu or list is open and the user clicks outside it, including within the text entry field, the menu or list closes.

### <span id="page-125-4"></span><span id="page-125-0"></span>Placards

A **placard** is a control that you can use as an information display or as background fill for a control area. Typically placards are used in document windows as a way to quickly modify the view of the contents—for example, to change the current page or the magnification.

The most familiar use of the placard is as a small information panel, often placed at the bottom of a window to the left of the horizontal scroll bar. You can extend the functionality of a placard by, for example, having it provide a pop-up menu.

<span id="page-125-2"></span>**Figure 7-12** A placard pop-up menu

![](images/_page_125_Picture_6.jpeg)

Placards are 15 pixels high and use either 10-point or 11-point Lucida Grande Regular.

## <span id="page-125-3"></span><span id="page-125-1"></span>Bevel Buttons

A **bevel button** has a beveled edge that gives the button a three-dimensional appearance.

- Bevel buttons can display text, an icon, or a picture
- They mimic the behavior of other button types; for example, a bevel button can behave like a standard push button. Bevel buttons can be grouped and used like radio buttons or checkboxes.
- Bevel buttons can have a menu attached, so the button behaves like a pop-up menu. See ["Pop-Up Icon Buttons and Pop-Up Bevel Buttons" \(page 128\)](#page-127-2)
- They can have rounded or square corners. The square buttons work well for tiling together in groups, to be used as radio buttons, for example.

### <span id="page-126-0"></span>Bevel Button Specifications

**Figure 7-13** Bevel button specifications

#### <span id="page-126-1"></span>**Rounded corners**

![](images/_page_126_Picture_5.jpeg)

Leave at least 5 pixels between edge of icon and edge of button.

#### **Rounded corners with label below icon**

![](images/_page_126_Figure_8.jpeg)

#### **Square corners**

![](images/_page_126_Figure_10.jpeg)

- **Size of button:** 20 x 20 pixels minimum
- **Size of icon:** 32 x 32 pixels recommended, with at least 5 pixels between icon and button edge
- **Spacing:** Leave at least 8 pixels between buttons with rounded corners, stacked vertically or aligned horizontally.
- **Text:** Label font (10-point Lucida Grande Regular)

If a bevel button has an icon and a label, you can put the text anywhere in relation to the icon. Carbon and Cocoa developers can specify the location in Interface Builder.

In some situations—providing text-alignment options, for example—it is appropriate to use bevel buttons to graphically represent several mutually exclusive choices. You can also use bevel buttons for nonstandard-size push buttons.

<span id="page-127-1"></span>**Figure 7-14** Bevel buttons as radio buttons and push buttons

![](images/_page_127_Picture_5.jpeg)

### <span id="page-127-4"></span><span id="page-127-2"></span><span id="page-127-0"></span>Pop-Up Icon Buttons and Pop-Up Bevel Buttons

<span id="page-127-3"></span>An **icon button** does not have a rectangular edge around it; the clickable area is the graphic itself (for example, the toolbar buttons in Finder windows). An icon button or a bevel button containing a pop-up menu has a single downward-pointing arrow, as shown in Figure 7-15 (page 129). The button can behave like a standard pop-up menu, in which the image on the button is the current selection, or the button can represent the menu title and always display the same image.

The menu and the button (or the bounding rectangle around the icon) are left-aligned, with no space between the top of the menu window and the bottom of the button. The arrow is 7 pixels wide at the top. The tip of the arrow is positioned 1 pixel below the icon's bottom edge. There should be 3 pixels from the tip of the arrow to the top of the menu window.

<span id="page-128-0"></span>**Figure 7-15** Pop-up icon button

![](images/_page_128_Picture_3.jpeg)

<sup>4</sup> pixels between the top of the menu window and the bottom of the button

<span id="page-129-0"></span>**Figure 7-16** Pop-up bevel button with square corners

![](images/_page_129_Figure_3.jpeg)

<span id="page-129-2"></span>with no space between the top of the menu window and the bottom of the button.

<span id="page-129-1"></span>**Figure 7-17** Pop-up bevel button with rounded corners

![](images/_page_129_Figure_6.jpeg)

### <span id="page-130-5"></span><span id="page-130-4"></span><span id="page-130-0"></span>Slider Controls

<span id="page-130-6"></span>Use a **slider control** to enable users to choose among a continuous range of allowable values. Slider controls can be horizontal or vertical and can display labeled tick marks to represent increments you specify. The slider itself (the thumb) can be directional or round. In deciding whether a slider should be horizontal or vertical, try to meet users' expectations of similar real-world controls.

Slider controls support live feedback (live dragging), so users can see the effect of moving the slider as it is dragged. Dock preferences, for example, shows the effect of moving the Dock Size slider.

### <span id="page-130-1"></span>Slider Control Specifications

<span id="page-130-2"></span>**Figure 7-18** Slider control dimensions

**Sliders:** The control region is 15 x 18 pixels on directional sliders and 15 x 15 on nondirectional sliders.

![](images/_page_130_Figure_8.jpeg)

<span id="page-130-3"></span>**Figure 7-19** Small slider dimensions

**Small sliders:** The control region for all slider types is 11 x 12 pixels.

![](images/_page_130_Figure_11.jpeg)

### <span id="page-131-2"></span><span id="page-131-0"></span>Tab Controls

The **tab control** provides a convenient way to present information in a multipage format. Tabs can display centered horizontally across the top or bottom edge, or centered vertically along the left or right side. Figure 7-20 shows the proper orientation of text on tabs on each of the four sides.

<span id="page-131-1"></span>**Figure 7-20** Orientation of tab text on each side

![](images/_page_131_Picture_5.jpeg)

<span id="page-131-3"></span>The content area below a tab is called a **pane.** You can use other controls such as push buttons and scroll bars in tabbed windows too. The controls can be global affecting the settings of all panes—or specific to an individual pane. Make it clear through labeling and placement (within or outside of a tab pane's boundary, for example) whether a control affects one pane or all panes.

### <span id="page-132-3"></span><span id="page-132-0"></span>Tab Control Specifications

<span id="page-132-1"></span>**Figure 7-21** Tab control dimensions

![](images/_page_132_Figure_4.jpeg)

Tabs use the system font.

<span id="page-132-2"></span>**Figure 7-22** Small tab control dimensions

![](images/_page_132_Figure_7.jpeg)

Small tabs use the small system font.

- **Text**: System font (13-point Lucida Grande), centered in tab with 12 pixels on each side. Small tabs: Small system font (11-point Lucida Grande), centered in tab with 10 pixels on each side.
- **Tab height:** 23 pixels. Small: 20 pixels
- **Accent bar height:** 6 pixels. Small: 5 pixels.

Tab panes can extend from one edge of a window to the other, or they can be inset within a window. Figure 7-23 shows an example of tab panes that extend from one edge of a window to the other.

<span id="page-133-0"></span>**Figure 7-23** Tab panes edge to edge

![](images/_page_133_Picture_3.jpeg)

For inset tab panes, the recommended inset is 20 pixels on each side within a window, although 16 is also allowed. You can define a window so space remains below the tab pane for global controls such as push buttons. Figure 7-24 shows an example of tab panes inset within a window, with buttons below the panes.

<span id="page-134-3"></span><span id="page-134-1"></span>**Figure 7-24** Tab panes inset from edge of window

![](images/_page_134_Figure_3.jpeg)

### <span id="page-134-2"></span><span id="page-134-0"></span>Progress Indicators and Relevance Controls

<span id="page-134-4"></span>**Progress indicators**, also called progress bars, are used to inform the user about the status of lengthy operations. There are two types:

- **Determinate:** Use when the full length of an operation can be determined. The bar moves from left to right, and the user can see how much of the process has been completed. You might use a determinate progress indicator to show the progress of a file conversion.
- **Indeterminate:** Use when the duration of a process can't be determined. This indicator displays a spinning striped cylinder to indicate an ongoing process. You might use an indeterminate progress indicator to let the user know that the application is attempting a dialup communication connection, for example, when there's no way to accurately determine how long it will take to complete. If an indeterminate process reaches a point where its duration can be determined, switch to a determinate progress indicator.

<span id="page-135-0"></span>**Figure 7-25** Progress bars

### **Determinate progress bar** Active fill Inactive fill Active fill Inactive fill **Indeterminate progress bar** 16

#### **Small progress bar**

**Large progress bar**

![](images/_page_135_Figure_5.jpeg)

The progress bar should fill in completely before it is dismissed.

When the process being performed can be interrupted, the progress dialog should contain a Cancel button (and support the Escape key). If interrupting the process will result in possible side effects, the button should say Stop instead of Cancel.

<span id="page-135-2"></span>In Mac OS X, don't use a progress bar to display relevance. Instead, use the new **relevance control** (available in Carbon) shown in Figure 7-26.

<span id="page-135-1"></span>**Figure 7-26** Relevance control

![](images/_page_135_Picture_10.jpeg)

### <span id="page-136-2"></span><span id="page-136-0"></span>Text Fields and Scrolling Lists

There are various kinds of controls that incorporate text:

- A **text input field**, also called an editable text field, is a rectangular area in which the user enters text or modifies existing text. The text input field can be active or disabled. It supports keyboard focus and password entry.
  - Your application's text input fields should perform appropriate edit checks. For example, if the only legitimate value for a field is a string of digits, the application issues an alert if the user types nondigits. In most cases, the appropriate time to check the data in the field is when the user clicks outside the field or presses the Return, Enter, or Tab key.
  - Combination boxes are text input fields that also contain a menu or a list of choices. See ["Combination Boxes" \(page 123\).](#page-122-3)
- <span id="page-136-6"></span><span id="page-136-1"></span>■ Use a **static text field** for dialog text that the user can't modify. Static text fields have two states: active and dimmed.
  - When it provides an obvious user benefit, static text should be selectable. Error message text, for example, should be selectable. Text that is likely to be copied so that it can be pasted accurately into another context (such as a serial number or a host name) is another example.
- A **scrolling list** can contain as many items as necessary. Users can scroll through the list without selecting anything, or can click an item to select it, use Shift-click to select more than one continuous item, or use Command-click for a discontinuous selection. Users can press the arrow keys to navigate through the list and can quickly select an item by typing the first few characters.

<span id="page-136-4"></span><span id="page-136-3"></span>If an item is too long to fit in the list box, insert ellipses in the middle and preserve the beginning and end of the item. Users often add version numbers to the end of document names.

<span id="page-136-5"></span>Don't use scrolling lists to provide choices in a limited range. Because the full range may not be visible all at once, it can be difficult for users to understand the scope of their choices. Use sliders, discussed in ["Slider Controls" \(page 131\),](#page-130-4) instead.

### <span id="page-137-0"></span>Tools for Creating Lists

<span id="page-137-2"></span><span id="page-137-1"></span>Functions, data types, and constants for creating and managing the new **data browser** control have been added to the Control Manager. The data browser (available to Carbon applications) provides a convenient way to create easily customized lists and consistent sortable, movable, and resizable columns. If your application uses the data browser functions to display lists, they will always look right in Mac OS 9 and Mac OS X

The data browser control has two versions: list view and column view. Finder windows have examples of both, selectable with the View control (in the upper-left area of the toolbar). The middle button is the list-view button; the button on the right is the column-view button.

Similar functionality is available to Cocoa developers through three classes of interface objects:

- **NSOutlineView.** You can see an example in the Mailboxes drawer of the Mail application, which can show a list hierarchy with disclosure triangles.
- **NSTableView.** You can see an example in the list of contents of a mailbox in the Mail application. It is multicolumn and row-based.
- **NSBrowser.** You can see an example in the Open dialog of a Cocoa-based application. This class provides the same sort of hierarchical data as NSOutlineView in column format.

[For more information, see the data browser control technical note, available at](http://developer.apple.com/technotes/tn/tn2009.html)  <http://developer.apple.com/technotes/tn/tn2009.html>.

### <span id="page-138-0"></span>Text Input Field Specifications

<span id="page-138-1"></span>**Figure 7-27** Text input field specifications

![](images/_page_138_Figure_4.jpeg)

<span id="page-138-2"></span>**Figure 7-28** Small text input field specifications

![](images/_page_138_Picture_6.jpeg)

- **Height:** 22 pixels (to accommodate the system font, which is 16 pixels high without line spacing). If you specify the small system font, the text input field dimensions are reduced proportionally. To accommodate the small system font, the text field height is 19 pixels.
- **Selection rectangle:** 16 pixels high. Small: 13 pixels.
- **Spacing:** Leave a minimum of 12 pixels between stacked text input fields (8 pixels between stacked small text input fields).
- **Text:** System font (13-point Lucida Grande Regular). Small: Small system font (11-point Lucida Grande Regular).

For more information about highlighting selections in text fields, see ["Keyboard](#page-167-0)  [Focus and Navigation" \(page 168\)](#page-167-0) and ["Selections in Text" \(page 181\)](#page-180-0).

### <span id="page-139-0"></span>Scrolling List Specifications

<span id="page-139-4"></span><span id="page-139-2"></span>**Figure 7-29** Scrolling list dimensions

![](images/_page_139_Figure_5.jpeg)

When you define dimensions, make sure that the list displays only full lines of text (don't cut text off vertically), and make sure that the scrolling increment is one list element.

■ **Text:** 12 points

■ **Frame:** 3 pixels wide

## <span id="page-139-3"></span><span id="page-139-1"></span>Image Wells

Use an **image well** to display an icon or picture that serves as a drag-and-drop target. You could use a set of image wells to manage thumbnails in a clip-art catalog, for example.

Don't use image wells in place of push buttons or bevel buttons.

<span id="page-140-1"></span>**Figure 7-30** Image wells

![](images/_page_140_Picture_3.jpeg)

## <span id="page-140-5"></span><span id="page-140-0"></span>Disclosure Triangles

A **disclosure triangle** allows the display, or disclosure, of information that elaborates on the primary information in a window. Disclosure triangles are used in the Finder's list view, where clicking a triangle displays a folder's contents.

<span id="page-140-2"></span>**Figure 7-31** Disclosure triangles in the Finder list view

![](images/_page_140_Picture_7.jpeg)

<span id="page-140-4"></span><span id="page-140-3"></span>Disclosure triangles are available to Carbon developers through the Control Manager (CreateDisclosureTriangle) or the Appearance Manager (DrawThemeButton). Cocoa provides this control only as part of the NSOutlineView class.

Controls

<span id="page-142-0"></span>This chapter provides basic suggestions for arranging controls in dialogs and windows. These guidelines use many of the default control sizes defined in Interface Builder; any exceptions are noted. To simplify the process of resizing and repositioning existing dialogs and windows, most values are based on a multiple of 2 pixels. All user-visible text should use the standard fonts described in ["Fonts"](#page-188-0) [\(page 189\).](#page-188-0)

## <span id="page-142-1"></span>Positioning Controls in Dialogs and Windows

<span id="page-142-2"></span>Keep these guidelines in mind when designing dialogs and windows:

- <span id="page-142-3"></span>■ In general, try for a more centered approach to dialog layout, as opposed to the strongly left-biased approach of the traditional Mac OS 9 dialog. Most of the sample layouts in this document illustrate the center-biased approach.
- All spacing between dialog elements involves a multiple of 2 pixels—2, 4, 6, 8, and so on.
- For most document windows that contain a single view (scrolling text or tables, for example), do not specify any space between the window edge and scroll bars (when using the Control Manager) or the frame of the view (in Interface Builder).
- Try to maintain a 20-pixel space between the left and right edge of the window and any controls. Keep 20 pixels of space between the bottom edge and any controls; this can include the shadow of any push buttons in that area. Top spacing is determined by which controls are placed closest to the top of the

dialog. For example, Figure 8-5 (page 149) uses a radio button as the topmost control, so the spacing is set to 14 pixels. In contrast, [Figure 8-6 \(page 150\)](#page-149-1) uses a tab control as the topmost element, so the spacing is set to 12 pixels.

- For dialogs that contain a mix of controls, set 16 pixels of vertical space between groups of controls. Vertical spacing between controls is determined by the tallest control in the row.
- Groups of controls should be separated by 20 pixels of vertical spacing and subgroups of controls within groups should be separated by 16 pixels.
- <span id="page-143-1"></span>■ The minimum screen resolution a dialog needs to accommodate is 800 by 600. (Support for 640 by 480 is provided for games.)

## <span id="page-143-0"></span>Group Boxes

<span id="page-143-2"></span>A **group box** is used to associate a set of related items—such as radio buttons or pop-up menus—in a dialog.

As much as possible, *use additional space between controls to create groups of controls, rather than group boxes.* Excessive use of group boxes creates visual clutter; too many lines and edges can distract users. Also use space or separator lines, rather than secondary group boxes, for subgroupings. The following figures show examples of how to successfully re-create dialogs using space rather than group boxes. When space alone isn't enough to clearly divide areas, use a label and a separator, as shown in the following "after" examples.

Within a group box, no control or label should be positioned within 16 pixels of the box's top, bottom, left, or right borders.

Group boxes can be untitled or titled. Titles can be static text, a checkbox label, or text in a pop-up menu.

<span id="page-144-0"></span>**Figure 8-1** Dialog redesigned without group boxes (first example)

![](images/_page_144_Figure_3.jpeg)

Before (with group boxes)

![](images/_page_144_Figure_5.jpeg)

After (example 1, with separator)

![](images/_page_144_Figure_7.jpeg)

After (example 2)

Group Boxes **145**

### Layout Guidelines

<span id="page-145-0"></span>**Figure 8-2** Dialog redesigned without group boxes (second example)

![](images/_page_145_Figure_3.jpeg)

Before

![](images/_page_145_Figure_5.jpeg)

After

<span id="page-146-1"></span>**Figure 8-3** Dialog redesigned without a group box (third example)]

![](images/_page_146_Picture_3.jpeg)

## <span id="page-146-0"></span>Sample Dialog Layouts

<span id="page-146-2"></span>This section contains sample layouts illustrating how to position various types of controls. Unless specified otherwise, all measurements are in pixels.

<span id="page-147-0"></span>**Figure 8-4** A standard alert with dimensions

![](images/_page_147_Figure_3.jpeg)

<span id="page-148-0"></span>**Figure 8-5** Sample application preferences dialog

![](images/_page_148_Figure_3.jpeg)

<span id="page-149-2"></span><span id="page-149-0"></span>**Figure 8-6** Sample dialogs with panes

<span id="page-149-1"></span>![](images/_page_149_Figure_3.jpeg)

![](images/_page_149_Picture_4.jpeg)

![](images/_page_150_Picture_2.jpeg)

<span id="page-151-0"></span>**Figure 8-7** Sample dialog with scrolling list

![](images/_page_151_Figure_3.jpeg)

## <span id="page-152-0"></span>Using Small Versions of Controls

<span id="page-152-2"></span>Small versions of controls are available in Carbon and Cocoa. Use the smaller versions only when absolutely necessary, and use them sparingly. When converting existing dialogs for use with Aqua, redesign layouts as necessary, rather than relying on the smaller versions of controls. Your first choice in designing for Aqua should always be to use the full-size controls.

You can use small versions of controls when space is at an extreme premium, such as in tool palettes or other utility windows. Don't mix full-size and small versions of controls in the same window.

Figure 8-8 shows the specifications for small scroll bars and the resize control. [Figure 8-9](#page-153-1) shows a sample utility window using small controls.

<span id="page-152-3"></span><span id="page-152-1"></span>**Figure 8-8** Sample window using small scroll bars and resize control

![](images/_page_152_Figure_7.jpeg)

<span id="page-153-0"></span>**Figure 8-9** Sample utility window using small controls

<span id="page-153-1"></span>![](images/_page_153_Figure_3.jpeg)

<span id="page-153-2"></span>![](images/_page_153_Picture_4.jpeg)

<span id="page-154-2"></span><span id="page-154-0"></span>Like other graphical user interfaces, Mac OS X is optimized for use with a pointing device, such as a mouse. Many users, however, prefer or need to interact with the computer using the keyboard instead of the mouse. In Mac OS X (version 10.1), users have the option of enabling keyboard access for all functions available using a point-and-click device.

## <span id="page-154-1"></span>What's New in Aqua

- **Full keyboard access:** Starting with Mac OS X 10.1, users can turn on a mode enabling them to navigate through more of the interface using the keyboard (instead of the mouse). For more information, see ["Keyboard Focus and](#page-167-2)  [Navigation" \(page 168\).](#page-167-2)
- **New keyboard equivalents:** Command-H is reserved as an equivalent to the "Hide <Application Name>" menu command that appears in the application menu of all applications. Command-M is reserved as an equivalent to the Minimize menu command in the Window menu. It applies to any active window that can be minimized. The command initiated in Mac OS 9 by Command-M, Make Alias, now has the keyboard equivalent Command-L. For more information, see ["Keyboard Equivalents" \(page 172\)](#page-171-1).

## <span id="page-155-0"></span>The Mouse and Other Pointing Devices

<span id="page-155-5"></span>In the Macintosh interface the standard pointing device is the mouse. Users can substitute other devices—such as trackballs and stylus pens—that maintain the behavior of direct manipulation of objects on screen.

<span id="page-155-4"></span>Moving the mouse without pressing the mouse button moves the **pointer.** The onscreen pointer can assume different shapes according to the context of the application and the pointer's position. For example, in a word processor, the pointer takes the I-beam shape while it's over the text and changes to an arrow when it's over a tools palette. Change the pointer's shape *only* to provide information to the user about changes in the pointer's function.

<span id="page-155-2"></span>Each pointer has a **hot spot**—the portion of the pointer that must be positioned over a screen object before mouse clicks have an effect on the object. The hot spot should be intuitive, such as the tip of an arrow pointer or the center point of a crosshair. Screen objects have a **hot zone**—the area that the pointer's hot spot must be within in order for mouse clicks to have an effect.

### <span id="page-155-3"></span><span id="page-155-1"></span>Using the Mouse

Just *moving* the mouse changes only the pointer's location, and possibly its shape. *Pressing* the mouse button indicates the intention to do something, and *releasing* the mouse button completes the action. Pressing by itself should have no more effect than clicking does, except in well-defined areas, such as scroll arrows, where it has the same effect as repeated clicking. For example, pressing a Finder icon should select the icon but not open it.

The mouse devices provided with Macintosh computers have only one button, and these guidelines apply to single-button mice. Other input devices may include additional buttons that can be programmed to replicate functionality provided in Mac OS X through keystrokes.

### <span id="page-156-3"></span><span id="page-156-0"></span>Clicking

Clicking has two components: pushing down on the mouse button and releasing it without moving the mouse. (If the mouse moves between button down and button up, it's *dragging,* not clicking.)

The effect of a click should be immediate and obvious. If the function of the click is to cause an action (such as clicking a button), the *selection is made* when the button is pressed, and the *action takes place* when the button is released. For example, if a user presses down the mouse button while the pointer is over an onscreen button, thereby putting the button in a selected state, and then moves the pointer *off* the button before releasing the mouse button, the onscreen button is not clicked. If the user presses an onscreen button and rolls over another button before releasing the mouse, neither button is clicked.

### <span id="page-156-4"></span><span id="page-156-1"></span>Double-Clicking

Double-clicking involves a second click that follows immediately after the first click. If the two clicks are close enough to each other in terms of time (as set by the user in Mouse preferences) and location (usually within a couple of pixels), they constitute a double click.

Double-clicking is most commonly used as a shortcut for other actions, such as pressing Command-O to open a document or dragging to select a word. Because not everyone is physically able to perform a double click, it should *never* be the only way to perform an action.

Some applications support triple-clicking. For example, in a word processor, the first click sets the insertion point, the second click selects the whole word, and the third click selects the whole sentence or paragraph. Supporting more than three clicks is inadvisable.

### <span id="page-156-5"></span><span id="page-156-2"></span>Pressing

Pressing means holding down the mouse button while the mouse remains stationary. Pressing certain objects, such as scroll arrows, has the same effect as repeatedly clicking the object.

### <span id="page-157-2"></span><span id="page-157-0"></span>Dragging

Dragging means pressing the mouse button, moving the mouse to a new position, and releasing the mouse button. The uses of dragging include selecting blocks of text, choosing a menu item, selecting a range of objects, moving an icon from one place to another, and shrinking or expanding an object.

Dragging a graphic object should move the entire object (or a transparent representation of it), not just the object's outline.

Your application can restrict an object from being moved past certain boundaries, such as the edge of a window. If the user drags an object and releases the mouse button outside the boundary, the object stays in the original location. If the user drags the item out of the boundary and then back in before releasing the mouse button, the object moves to the new location. Your application can also automatically scroll a document if the user moves an object beyond the boundary of a window (see ["Automatic Scrolling" \(page 83\)\)](#page-82-0).

<span id="page-157-4"></span><span id="page-157-3"></span>Also see ["Drag and Drop" \(page 209\)](#page-208-0) for some more information about dragging and automatic scrolling.

## <span id="page-157-1"></span>The Keyboard

The keyboard's primary use is to enter text. The keyboard may also be used for navigation, but it should always be an alternative to using the mouse. For more information about using the keyboard instead of the mouse, see ["Keyboard Focus](#page-167-2)  [and Navigation" \(page 168\)](#page-167-2).

### <span id="page-158-0"></span>The Functions of Specific Keys

There are four kinds of keys: character keys, modifier keys, arrow keys, and function keys. A **character key** sends a character to the computer. When the user holds down a **modifier key,** it alters the meaning of the character key being pressed or the meaning of a mouse action.

<span id="page-158-4"></span>**Note:** Not all the keys described here exist on all Macintosh keyboards. Don't depend on a key as the only way for users to accomplish a task.

### <span id="page-158-2"></span><span id="page-158-1"></span>Character Keys

Character keys include letters, numbers, punctuation, the Space bar, and nonprinting characters—Tab, Enter, Return, Delete (or Backspace), Clear, and Escape (Esc). It is essential that your application use these keys consistently.

### **Space Bar**

<span id="page-158-5"></span>In text, pressing the Space bar enters a space between characters.

When full keyboard access is turned on, pressing the Space bar selects the item that currently has the keyboard navigation focus (the equivalent of clicking the mouse button).

### <span id="page-158-6"></span>**Tab**

In text-oriented applications, the Tab key moves the insertion point to the next tab stop. In other contexts, Tab is a signal to proceed; it means "move to the next item in a sequence." The next item can be a table cell or a dialog text field. Shift-Tab navigates in the reverse direction. Pressing Tab can cause data to be entered before focus moves to the next item. For more details about navigating with the Tab key, see ["Keyboard Focus and Navigation" \(page 168\)](#page-167-2).

### <span id="page-158-3"></span>**Enter**

Most applications add information to a document as soon as the user enters it. In some cases, however, the application may need to wait until a whole collection of information is available before processing it. The Enter key tells the application that

The Keyboard **159**

the user is through entering information in a particular area of the document, such as a text field. While the user is entering text into a *text* document, pressing Enter has no effect.

If a dialog has a default button, pressing Enter (or Return) is the same as clicking it.

### <span id="page-159-3"></span>**Return**

In text, the Return key inserts a carriage return (a line break) and moves the insertion point to the beginning of the next line. In arrays, the Return key signals movement to the leftmost field one step lower (like a carriage return on a typewriter). Like Tab, pressing Return can cause data to be entered before focus moves to the next item.

If a dialog has a default button, pressing Return (or Enter) is the same as clicking it.

### <span id="page-159-0"></span>**Delete (or Backspace)**

Generally, if an item is selected, pressing Delete (or Backspace) removes the selection without putting it on the Clipboard. If nothing is selected, pressing Delete removes the character preceding the insertion point, without putting it on the Clipboard. The Delete key has the same effect as the Delete command in the Edit menu.

<span id="page-159-2"></span>**Note:** The Delete key is different from the Forward Delete key (labeled *Del*), which removes characters following the insertion point. See "Forward Delete (Del)" (page 167).

Recommended key combinations for text applications are Command-Delete to delete the previous word, and Command–Forward Delete to delete the next word. You can support Option-Delete to delete the part of the word to the left of the insertion point, and Option–Forward Delete to delete the part of the word right of the insertion point.

### <span id="page-159-1"></span>**Clear**

The Clear key has the same effect as the Delete command in the Edit menu: It removes the selection without putting it on the Clipboard. Not all keyboards have a Clear key, so don't require its use in your application.

### <span id="page-160-3"></span>**Escape**

The Escape (Esc) key basically means "let me out of here." It has specific meanings in certain contexts:

- The user can press Escape instead of clicking Cancel in a dialog.
- The user can press Escape to stop an operation in progress (such as printing), instead of pressing Command-period.

<span id="page-160-2"></span>Pressing Escape should never cause the user to back out of an operation that would require extensive time or work to reenter. When the user presses Escape during a lengthy operation, display a confirmation dialog to be sure that the key wasn't pressed accidentally.

### <span id="page-160-4"></span><span id="page-160-0"></span>Modifier Keys

Modifier keys alter the way other keystrokes or mouse clicks are interpreted. You should use these keys—Shift, Caps Lock, Option, Command, and Control consistently as described here.

### <span id="page-160-6"></span>**Shift**

When pressed at the same time as a character key, the Shift key produces the uppercase alphabetic letter or the upper symbol on the key.

The Shift key is also used with the mouse for extending a selection or for constraining movements in graphics applications. For example, in some applications pressing Shift while using a rectangle tool draws squares.

### <span id="page-160-1"></span>**Caps Lock**

When activated, the Caps Lock key has the same effect on alphabetic keys as the Shift key, but it has no effect on nonalphabetic keys. When the Caps Lock key is down, the user must press Shift to type the upper character on a nonalphabetic key.

### <span id="page-160-5"></span>**Option**

When used with other keys, the Option key produces special symbols. The Key Caps application shows which keys generate each symbol.

The Keyboard **161**

The Option key can also be used with the mouse to modify the effect of a click or drag. For example, in some applications pressing Option while dragging an object makes a copy of the object.

### <span id="page-161-4"></span><span id="page-161-1"></span>**Command**

On most keyboards, the Command key is labeled with a cloverleaf ( ) symbol and an Apple logo (). Pressing the Command key at the same time as a character key tells the application to interpret the key as a command rather than a character. These key combinations are described in ["Keyboard Equivalents" \(page 172\).](#page-171-1)

In some applications, the Command key is used with other keys to provide special functions or shortcuts. It can also be used with the mouse to modify the effect of a click or drag.

### <span id="page-161-5"></span>**Control**

<span id="page-161-6"></span>The Control key is used to modify the functions of other keys, with terminal-emulation programs for Control-key sequences, and, with a mouse click, to display contextual menus (see ["Contextual Menus" \(page 62\)\)](#page-61-0).

In Mac OS X 10.1, Control-F7 temporarily overrides a user's preference for simple navigation or full keyboard navigation in windows and dialogs. For more information, see ["Keyboard Focus and Navigation" \(page 168\).](#page-167-2)

[Cocoa developers should also consider additional behaviors, as described in the](http://developer.apple.com/techpubs/macosx/Cocoa/CocoaTopics.html)  [text defaults and binding document, available in the programming topics section at](http://developer.apple.com/techpubs/macosx/Cocoa/CocoaTopics.html)  [http://developer.apple.com/techpubs/macosx/Cocoa/TasksAndConcepts/](http://developer.apple.com/techpubs/macosx/Cocoa/TasksAndConcepts/ProgrammingTopics/TextDisplay/Tasks/TextDefaultsAndBindings.html) [ProgrammingTopics/TextDisplay/Tasks/TextDefaultsAndBindings.html](http://developer.apple.com/techpubs/macosx/Cocoa/TasksAndConcepts/ProgrammingTopics/TextDisplay/Tasks/TextDefaultsAndBindings.html).

### <span id="page-161-2"></span><span id="page-161-0"></span>Arrow Keys

Apple keyboards have four arrow keys: Up Arrow, Down Arrow, Left Arrow, and Right Arrow. They can be used alone or in combination with other keys. Keyboard combinations using the arrow keys should be used only for shortcuts for mouse actions. It is *never* appropriate to implement only a keyboard combination and not provide a mouse-based way to perform the same action.

### <span id="page-161-3"></span>**Appropriate Uses for the Arrow Keys**

You can use arrow keys in these ways:

- In text, the arrow keys move the insertion point. When used with the Shift key, they extend or shrink the selection. If the user makes a selection and then presses the Right Arrow or Left Arrow, shrink the selection to zero length and place the insertion point at the right or left edge of the selection.
- In lists, the arrow keys change the selection.
- In a graphics application, the arrow keys can be used to move a selected object the smallest possible increment (one pixel or one grid unit).
- In full keyboard access mode, the arrow keys move between values within a control. This behavior is described in ["Keyboard Focus and Navigation"](#page-167-2) [\(page 168\).](#page-167-2)

Don't use the arrow keys to

- move the mouse pointer onscreen
- duplicate the function of the scroll bars

If it's important for your application to make use of the numeric keypad, don't use the Shift–arrow key combinations to extend text selections; the keypad's codes for the four Shift–arrow key combinations are the same as those for the keypad's +, \*, /, and = keys.

### <span id="page-162-0"></span>**Moving the Insertion Point**

When the insertion point moves vertically in a text document, its horizontal position is maintained in terms of screen pixels, not characters (in other words, the insertion point could move from the twenty-fifth character in a line down to the fiftieth character, depending on the font and size). As the insertion point moves from line to line, keep it as close as possible to its original horizontal position, moving it slightly left or right to the nearest new character boundary.

The Option and Command keys are used as semantic modifiers with the arrow keys. As a general rule, the Option key increases the size of the semantic unit by one compared to the arrow keys alone, and Command key enlarges the semantic unit again. The application determines what the semantic units are. In a word processor, typically the units are characters, words, lines, paragraphs, and documents. In a spreadsheet, a basic semantic unit could be a cell.

The Keyboard **163**

### User Input

Table 9-1 describes the appropriate behavior of the arrow keys in text documents and fields. In some cases, the behavior describes what happens when the indicated keys are pressed more than once in succession.

<span id="page-163-1"></span><span id="page-163-0"></span>**Table 9-1** Moving the insertion point with the arrow keys

<span id="page-163-10"></span><span id="page-163-9"></span><span id="page-163-8"></span><span id="page-163-7"></span><span id="page-163-6"></span><span id="page-163-5"></span><span id="page-163-4"></span><span id="page-163-3"></span><span id="page-163-2"></span>

| Key                 | Moves insertion point                                                                                                                         |
|---------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|
| Right Arrow         | One character to the right                                                                                                                    |
| Left Arrow          | One character to the left                                                                                                                     |
| Up Arrow            | To the line above, to the nearest character boundary<br>at the same horizontal location                                                       |
| Down Arrow          | To the line below, to the nearest character boundary<br>at the same horizontal location                                                       |
| Option–Right Arrow  | To end of current word, then to the end of the next<br>word                                                                                   |
| Option–Left Arrow   | To the beginning of the current word, then to the<br>beginning of the previous word                                                           |
| Option–Up Arrow     | To the beginning of the current paragraph, then to<br>the beginning of the previous paragraph                                                 |
| Option–Down Arrow   | To the end of the current paragraph, then to the end<br>of the next paragraph (not to the blank line after the<br>paragraph, if there is one) |
| Command–Right Arrow | To the next semantic unit, typically the end of the<br>current line, then the end of the next line                                            |
| Command–Left Arrow  | To the previous semantic unit, typically the<br>beginning of the current line                                                                 |
| Command–Up Arrow    | Upward in the next semantic unit, typically the<br>beginning of the document                                                                  |
| Command–Down Arrow  | Downward in the next semantic unit, typically the<br>end of the document                                                                      |

<span id="page-164-3"></span>**Note:** For non-Roman script systems, Command–Left Arrow and Command–Right Arrow are reserved for changing the direction of keyboard input.

### <span id="page-164-1"></span>**Extending Text Selection With the Shift and Arrow Keys**

Table 9-2 describes how to extend text selection by pressing the Shift key with the arrow keys.

If no text is selected, the extension begins at the insertion point. If text is selected by dragging, then the extension begins at the selection boundary. For example, in the phrase *stop time,* if the user places the insertion point between the "s" and "t" and then presses Shift–Option–Right Arrow, *top* is selected. However, if the user double-clicks so the whole word is selected, and then extends the selection left or up, it's as if the insertion point were before the "s." If the user extends the selection right or down, it's as if the insertion point were between the "p" and the space after the word.

Reversing the direction of the selection deselects the appropriate unit. In the previous example, if the word *stop* is selected and the user presses Shift–Option–Right Arrow, so *stop time* is selected, and then presses Shift–Option–Left Arrow, *time* is deselected and *stop* remains selected.

<span id="page-164-2"></span><span id="page-164-0"></span>**Table 9-2** Extending text selection with the Shift and arrow keys

| Keys                     | Extends selection                                                                       |
|--------------------------|-----------------------------------------------------------------------------------------|
| Shift–Right Arrow        | One character to the right                                                              |
| Shift–Left Arrow         | One character to the left                                                               |
| Shift–Up Arrow           | To the line above, to the nearest character<br>boundary at the same horizontal location |
| Shift–Down Arrow         | To the line below, to the nearest character<br>boundary at the same horizontal location |
| Shift–Option–Right Arrow | To the end of the current word, then to the end<br>of the next word                     |
| Shift–Option–Left Arrow  | To the beginning of the current word, then to<br>the beginning of the previous word     |

<span id="page-164-4"></span>The Keyboard **165**

User Input

**Table 9-2** Extending text selection with the Shift and arrow keys (continued)

<span id="page-165-2"></span>

| Keys                      | Extends selection                                                                                                                                                  |
|---------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Shift–Option–Up Arrow     | To the beginning of the current paragraph, then<br>to the beginning of the next paragraph                                                                          |
| Shift–Option–Down Arrow   | To the end of the current paragraph, then to the<br>end of the next paragraph (include the blank<br>line between paragraphs in cut, copy, and paste<br>operations) |
| Shift–Command–Right Arrow | To the next semantic unit, typically the end of<br>the current line                                                                                                |
| Shift–Command–Left Arrow  | To the previous semantic unit, typically the<br>beginning of the current line                                                                                      |
| Shift–Command–Up Arrow    | Upward in the next semantic unit, typically the<br>beginning of the document                                                                                       |
| Shift–Command–Down Arrow  | Downward in the next semantic unit, typically<br>the end of the document                                                                                           |

### <span id="page-165-1"></span>**Moving the Insertion Point in "Empty" Documents**

Various text-editing programs treat empty documents in different ways. Some assume that an empty document contains no characters, in which case clicking at the bottom of a blank screen causes the insertion point to appear at the top. In this situation, Down Arrow cannot move the insertion point into the blank space because there are no characters there.

<span id="page-165-0"></span>Other applications treat an empty document as a page of space characters, in which case clicking at the bottom of a blank screen puts the insertion point where the user has clicked and lets the user type characters there, overwriting the spaces. Whichever of these methods you choose for your application, it's essential that you be consistent throughout.

### <span id="page-166-1"></span><span id="page-166-0"></span>Function Keys

There are fifteen nondedicated function keys on desktop Macintosh keyboards (F1 through F15). Default function key combinations are listed in Table 9-3 (page 171). Desktop Macintosh keyboards provide the following six dedicated function keys with standard behaviors. Because not all Macintosh computers have all function keys, don't rely on these keys for critical keyboard shortcuts.

### **Help**

Pressing the Help key (or Command-? or Command-/) invokes the application's help, if it's available. If a help system isn't available, the Help key should at least display some sort of helpful screen.

### **Forward Delete (Del)**

Pressing this key deletes the character *after* the insertion point, shifting everything following the removed character one position back. The effect is that the insertion point remains stationary while it "vacuums" the character or selection ahead of it.

If something is selected when Del is pressed, it has the same effect as pressing Delete (Backspace) or choosing Delete from the Edit menu.

You can support Option-Del to delete the next larger semantic unit, as described in "Moving the Insertion Point" (page 163), but deleting more than one word at a time is inadvisable. Users prefer to select large amounts of text with the mouse so they have more control over what they're deleting.

### **Home, End**

Pressing the Home key is equivalent to moving the scrollers all the way to the top and to the left. In a text document, for example, pressing Home scrolls to the beginning of the document; in a spreadsheet, it may scroll to the beginning of the spreadsheet or to the beginning of a row.

End is the opposite of Home: It scrolls to the end of a document.

If the beginning or end of the document is already reached, pressing Home or End produces a system alert sound. *Pressing the Home or End key has no effect on the location of the insertion point or selected data.*

The Keyboard **167**

### **Page Up, Page Down**

<span id="page-167-3"></span>Pressing Page Up or Page Down scrolls the document up or down one page (the equivalent of clicking in the gray area of the scroll bar). If an entire page can't be displayed in the window, these keys first scroll incrementally up or down, until the top or bottom of the page is visible, before scrolling to the next page.

If the beginning or end of the document is reached, pressing Page Up or Page Down produces a system alert sound. *Pressing the Page Up or Page Down key has no effect on the location of the insertion point or selected data.*

## <span id="page-167-4"></span><span id="page-167-2"></span><span id="page-167-0"></span>Keyboard Focus and Navigation

You can use the keyboard to move the focus (highlight) between onscreen items. This feature enables a user to access controls, menus, the Dock, toolbars, and so on when using the mouse is undesirable, difficult, or impossible. In Roman systems, focus always begins at the first field that accepts keyboard input and follows a reading path from upper left to bottom right.

<span id="page-167-1"></span>Focus is indicated with a ring in the appearance color (Aqua or Graphite).

**Figure 9-1** Keyboard focus for a text field

![](images/_page_167_Picture_9.jpeg)

<span id="page-168-0"></span>**Figure 9-2** Keyboard focus for a scrolling list

![](images/_page_168_Picture_3.jpeg)

**Figure 9-3** Keyboard focus for columns

<span id="page-168-1"></span>![](images/_page_168_Picture_5.jpeg)

In list and column views, a selected item should be highlighted across the full row. In column view, the selected item has a dark highlight and the folders containing the item have a lighter highlight. When a window becomes inactive, all selections inside it should become the lighter highlight color.

The Keyboard **169**

User Input

<span id="page-169-7"></span><span id="page-169-5"></span><span id="page-169-0"></span>Navigation between most controls in achieved by pressing the Tab key and the arrow keys. Shift-Tab navigates in reverse direction.

<span id="page-169-4"></span><span id="page-169-2"></span>In **default keyboard access mode,** focus moves only between fields that receive keyboard input, such as text entry fields, list boxes that support type-ahead, and scrolling lists. Mac OS X 10.1 provides the option of **full keyboard access mode,** which enables users to navigate through windows and dialogs. Cocoa applications that use system controls get this functionality automatically.

<span id="page-169-1"></span>Users can turn on full keyboard access in the Full Keyboard Access pane of Keyboard preferences. Control -F1 is a reserved keyboard shortcut for turning full keyboard access on or off; don't use this combination for any other purpose. Control-F7 temporarily overrides the current mode in windows and dialogs.

In full keyboard access mode, the arrow keys move between values within a control. For example, if the user selects a slider with the Tab key, the arrow keys move the slider control along the slider track. For vertically oriented choices, such as menu items, the Up Arrow and Down Arrow keys move the slider. For horizontally oriented choices, such as a row of tabs, the Right Arrow and Left Arrow keys move the slider. In some cases, it makes sense to support both orientations. For example, a vertical slider could use both the Up Arrow and the Right Arrow to increase the value.

<span id="page-169-6"></span>In some cases, such as radio buttons, moving the focus to an item selects it as well. In other cases, such as push buttons, the user chooses a selected item by pressing the Space bar. In full keyboard access mode, pressing the Space bar is equivalent to clicking the mouse button.

<span id="page-169-3"></span>The Escape key is used to cancel a dialog and to cancel a selection in a pop-up menu or list. In a Dock pop-up menu, Escape dismisses the menu and moves focus to the frontmost window.

### User Input

The user can also quickly place focus in the menu bar, the Dock, toolbars, and utility windows using the key combinations described in Table 9-3.

<span id="page-170-0"></span>**Table 9-3** Key combinations for moving focus in full keyboard access mode

<span id="page-170-5"></span><span id="page-170-4"></span><span id="page-170-3"></span><span id="page-170-2"></span><span id="page-170-1"></span>

| Key combinations                      | Action                                                                                                      |
|---------------------------------------|-------------------------------------------------------------------------------------------------------------|
| Control-F1                            | Turns full keyboard access on or off                                                                        |
| Control-F7                            | Temporarily overrides the current keyboard access mode in<br>windows and dialogs                            |
| Control-F2 (Control-m)*               | Moves focus to the menu bar                                                                                 |
| Control-F3 (Control-d)*               | Moves focus to the Dock                                                                                     |
| Control-F4 (Control-w)                | Moves focus to the active (or next) window                                                                  |
| Control-F5 (Control-t)*               | Moves focus to the toolbar                                                                                  |
| Control-F6 (Control-u)*               | Moves focus to the first (or next) utility window (palette)                                                 |
| Shift-Control-F6<br>(Shift-Control-w) | Moves focus to the previous utility window                                                                  |
| Control-Tab                           | Moves focus to the next grouping of controls in a dialog or the<br>next table (when Tab moves to next cell) |
| Shift-Control-Tab                     | Moves focus to the previous grouping of controls                                                            |
| Command-Tab                           | Moves focus to the first (or next) open application's Dock icon                                             |
| Shift-Command-Tab                     | Moves focus to the previous open application's Dock icon                                                    |
| Arrow key                             | Moves focus to the next value in a text field or certain controls,<br>such as menus; also opens Dock menus  |
| Control–arrow key                     | Moves focus to another value or cell within a control such as a<br>table                                    |
| Command-~                             | Moves focus to the next open window in an application                                                       |

**<sup>\*</sup>Users can change these defaults in the Full Keyboard Access pane of Keyboard preferences. The mnemonic alternatives are in parentheses. User-selected combinations override their functionality in applications while full keyboard access is on.**

The Keyboard **171**

User Input

**Table 9-3** Key combinations for moving focus in full keyboard access mode (continued)

| Key combinations | Action                                                                                                                                             |
|------------------|----------------------------------------------------------------------------------------------------------------------------------------------------|
| Space bar        | Selects the highlighted control (equivalent to clicking the mouse<br>button)                                                                       |
| Return (Enter)   | Selects the default button                                                                                                                         |
| Escape           | Cancels a dialog or a selection in a pop-up menu or list; in a Dock<br>menu, Escape closes the menu and moves the focus to the<br>frontmost window |

**<sup>\*</sup>Users can change these defaults in the Full Keyboard Access pane of Keyboard preferences. The mnemonic alternatives are in parentheses. User-selected combinations override their functionality in applications while full keyboard access is on.**

#### **Important**

<span id="page-171-2"></span>Your application should not override the implementation of keyboard focus and navigation in Mac OS X 10.1. These features provide functionality for users with special needs.

### <span id="page-171-3"></span><span id="page-171-1"></span><span id="page-171-0"></span>Keyboard Equivalents

Mac OS X reserves certain keyboard combinations as equivalents to menu commands; these shortcuts affect all applications. Even if your application doesn't support all the combinations shown in Table 9-4, don't use any of them for another

### User Input

function. If you choose not to implement these functions in your product, and use these equivalents for other actions, that could make your application less intuitive for users accustomed to the combinations shown here.

<span id="page-172-20"></span><span id="page-172-0"></span>**Table 9-4** Reserved and recommended keyboard equivalents

<span id="page-172-19"></span><span id="page-172-15"></span><span id="page-172-14"></span><span id="page-172-13"></span><span id="page-172-12"></span><span id="page-172-11"></span><span id="page-172-10"></span><span id="page-172-9"></span><span id="page-172-7"></span><span id="page-172-2"></span>

| Menu        | Keys       | Command          |
|-------------|------------|------------------|
| Application | Command-H* | Hide             |
| Application | Command-Q* | Quit             |
| Window      | Command-M* | Minimize         |
| File        | Command-N* | New              |
| File        | Command-O  | Open             |
| File        | Command-W  | Close            |
| File        | Command-S  | Save             |
| File        | Command-P  | Print            |
| Edit        | Command-Z  | Undo             |
| Edit        | Command-X  | Cut              |
| Edit        | Command-C  | Copy             |
| Edit        | Command-V  | Paste            |
| Edit        | Command-A  | Select All       |
| Edit        | Command-F  | Find             |
| Edit        | Command-G  | Find Again       |
| Format      | Command-T  | Open Font dialog |
| Format      | Command-B  | Bold             |
| Format      | Command-I  | Italic           |
| Format      | Command-U  | Underline        |

<span id="page-172-18"></span><span id="page-172-17"></span><span id="page-172-16"></span><span id="page-172-8"></span><span id="page-172-6"></span><span id="page-172-5"></span><span id="page-172-4"></span><span id="page-172-3"></span><span id="page-172-1"></span>**<sup>\*</sup>These combinations are reserved by the system; the others are recommended.**

The Keyboard **173**

**Apple Computer, Inc. October 2001**

### User Input

[Table 9-5](#page-173-2) shows several key combinations that are reserved for use with localized versions of system software, localized keyboards, keyboard layouts, and input methods. These key combinations don't correspond directly to menu commands.

<span id="page-173-8"></span><span id="page-173-2"></span><span id="page-173-1"></span>**Table 9-5** Key combinations reserved for international systems

<span id="page-173-7"></span><span id="page-173-6"></span><span id="page-173-5"></span><span id="page-173-4"></span>

| Keys                           | Action                                                               |
|--------------------------------|----------------------------------------------------------------------|
| Command–Space bar              | Rotate through enabled script systems                                |
| Command–Option–Space bar       | Rotate through keyboard layouts and input<br>methods within a script |
| Command–modifier key–Space bar | Apple reserved                                                       |
| Command–Right Arrow            | Changes keyboard layout to current layout<br>of Roman script         |
| Command–Left Arrow             | Changes keyboard layout to current layout<br>of system script        |

### <span id="page-173-9"></span><span id="page-173-3"></span><span id="page-173-0"></span>Creating Your Own Keyboard Equivalents

Apple reserves the right to reserve other keyboard equivalents in the future, so be careful about adding your own, and add them *only for frequently used commands.* For example, if users typically open the Preferences dialog when they first start using your application, but not after their preferences are set, don't assign it a keyboard equivalent.

Use the Command key as the main modifier key for keyboard equivalents. For a command that complements another more common command, you can add Shift. The table below shows some recommended keyboard equivalents using Shift.

<span id="page-174-0"></span>**Table 9-6** Recommended keyboard equivalents using Shift to complement other commands

| Keys             | Command                              | Complemented command   |
|------------------|--------------------------------------|------------------------|
| Shift-Command-G  | Find Previous                        | Command-G (Find Again) |
| Shift-Command-P  | Page Setup                           | Command-P (Print)      |
| Shift-Command-S  | Save As                              | Command-S (Save)       |
| Shift-Command-V  | Paste as (Quotation, for<br>example) | Command-V (Paste)      |
| Shift-Command-Z* | Redo                                 | Command-Z (Undo)       |

**<sup>\*</sup> This combination would be used only if Undo and Redo are separate commands (rather than toggled using Command-Z).**

If there's a third, less common command that's related to a pair of commands that use Command and Shift-Command, you can use Option-Command for the third command's keyboard equivalent. In the example in Table 9-7, Save All could be a dynamic menu item (see ["Menu Behavior" \(page 48\)](#page-47-0)) that appears in place of Save when the user presses the Option key (rather than a separate menu item). Use combinations like these very rarely.

<span id="page-174-1"></span>**Table 9-7** Example of using Option to modify a shortcut already using Command

| Command  |
|----------|
| Save     |
| Save As  |
| Save All |
|          |

The Keyboard **175**

Also use Option for a keyboard equivalent that is a convenience or power user feature. For example, the Finder uses Option-Command-W for Close All Windows and Option-Command-M for Minimize All Windows.

Remember that other languages may require modifier keys to generate certain characters. For example, the "[" character on a U.S. keyboard translates to Option-5 on a French or German keyboard. You can safely modify any character with the Command key, but avoid using Command and an additional modifier with characters not available on all keyboards. If you must use a modifier key in addition to the Command key, use them only with the alphabetic characters (*a* through *z*).

### <span id="page-175-5"></span><span id="page-175-3"></span><span id="page-175-2"></span><span id="page-175-0"></span>Type-Ahead and Auto-Repeat

If the user types faster than the computer can handle or when the computer is unable to process the keystrokes, the keystrokes are queued for later processing. This queuing is called **type-ahead.** There is a limit (varying with the computer) to the number of keystrokes that can be queued, but it's usually not reached unless the user types while the application is performing a lengthy operation.

When a character key is held down for a certain amount of time, it starts repeating automatically. The user can make adjustments to this feature, called **auto-repeat,** in Keyboard preferences.

An application can tell whether keystrokes are generated by auto-repeat or by the same key being pressed numerous times. Your application can disregard auto-repeat keystrokes; it probably should ignore them in keyboard equivalents.

<span id="page-175-4"></span>Auto-repeat works only when the application is ready to accept keyboard input; it does not function during type-ahead.

## <span id="page-175-1"></span>Selecting

Before performing an operation on an object, the user must select it to distinguish it from other objects. There is always immediate visual feedback to show that something is selected.

Selecting an object never alters the object itself, and a selection is always undoable by clicking outside the selection.

How something is selected depends on what it is. It's useful to distinguish among three types of objects that are each dealt with in a different way when selected:

- **Text.** An application considers all text appearing together in a particular context as a block of text—a one-dimensional string of characters. A block of text can range from a single field, as in a dialog, to an entire document, as in a word processor. Regardless of where it appears, text is edited in the same way.
- **Arrays** are tabular arrangements of fields. A one-dimensional array is a *list* and a two-dimensional array is a *table*. Each field contains information such as text or graphics.
- **Graphics.** For the purposes of this discussion, a graphic, or picture, is a discrete object that can be selected individually.

The following sections discuss the general methods of selecting and the specific methods that apply to text, arrays, and graphics.

## <span id="page-176-0"></span>Selection Methods

This section describes various selection techniques.

Selecting **177**

<span id="page-177-2"></span>**Figure 9-4** Selection techniques

![](images/_page_177_Picture_3.jpeg)

### <span id="page-177-3"></span><span id="page-177-0"></span>Selection by Clicking

The most straightforward method of selecting an object is by clicking it once. Icons, for example, are selected in this way.

### <span id="page-177-4"></span><span id="page-177-1"></span>Selection by Dragging

The user can select a range of some objects by following this procedure:

- 1. The user positions the pointer at one corner of the range and presses the mouse button. This position is called the **anchor point** of the range.
- 2. Without releasing the mouse button, the user moves the pointer in any direction.
  - As the pointer moves, visual feedback indicates the objects that would be selected if the mouse button were released. For text and arrays, the selected area is continuously highlighted. For graphics, a dotted rectangle expands or contracts to show the selected area. If appropriate, the view should scroll to allow extending the selection beyond a window.
- 3. When the desired range is selected, the user releases the mouse button. The point at which the button is released is called the **active end** of the range.

### <span id="page-178-2"></span><span id="page-178-0"></span>Changing a Selection With Shift-Click

A user can extend a selection by holding down the Shift key and clicking the mouse button. This action is called **Shift-clicking.**

In text, a Shift-click typically results in a **continuous selection**—the selection is extended to include everything between the old anchor point and the new active end. Graphics applications typically support **discontinuous selection,** in which the user can extend a selection by adding nonadjacent objects to already selected objects, and the objects *between* the current selection and the new object are *not* included in the selection.

In text, if the user Shift-clicks within an already selected range, the new range is smaller than the old range.

In an array, a Shift-click can extend the selected range or it can move the selection from the current cell to wherever the user Shift-clicks.

There are two models for extending a continuous selection using Shift-click. In the **addition model,** new text is added to a current selection. In the **fixed-point model,** the user can extend the selection on either side of the insertion point. Figure 9-5 illustrates the results of three consecutive steps in both models.

<span id="page-178-1"></span>**Figure 9-5** Shift-clicking in the addition model and the fixed-point model

|                         | Addition<br>model           | Fixed-point<br>model        |
|-------------------------|-----------------------------|-----------------------------|
| Setting insertion point | This is some<br>sample text | This is some<br>sample text |
| Extending selection     | This is some                | This is some                |
| to the right.           | sample text                 | sample text                 |
| Extending selection     | This is some                | This is some                |
| to the left.            | sample text                 | sample text                 |

Selecting **179**

When considering which model to use in your application, keep in mind that the addition model provides more flexibility by allowing users to extend a selection in *both* directions.

### <span id="page-179-2"></span><span id="page-179-0"></span>Changing a Selection With Command-Click

In arrays and text in which Shift-click extends a continuous selection, the user can make discontinuous selections by holding down the Command key and clicking. Each Command-click adds the new object to the existing selection. If one of the objects selected with Command-click is already within an existing part of the selection, then it is removed from the selection instead of being added.

<span id="page-179-1"></span>**Figure 9-6** Discontinuous selection within an array

![](images/_page_179_Figure_6.jpeg)

Not all applications support discontinuous selections, and those that do might restrict the operations a user can perform on them. For example, a word processor might allow the user to choose a font after making a discontinuous selection, but not allow the user to type replacement characters, because it wouldn't be obvious which part of the selection the characters would replace.

## <span id="page-180-3"></span><span id="page-180-0"></span>Selections in Text

A block of text is a string of characters. A text selection is a substring of this string, which has any length from zero characters to the whole block.

The **insertion point** (a zero-length text selection) shows where text will be inserted when the user starts typing, or where the contents of the Clipboard will be pasted. The user establishes the location of the insertion point by clicking somewhere in the text; the insertion point appears at the nearest character boundary. If the user clicks anywhere to the right of the last character on a line, the insertion point appears immediately after the last character. If the user clicks to the left of the first character on a line, the insertion point appears immediately before the first character.

Selected text in an active window displays the highlight color chosen by the user in General preferences. When the window becomes inactive, the text should remain highlighted, but in the secondary color, which is a percentage of the original highlight color. When the window becomes active again, the text selection displays in the primary highlight color. Both Carbon and Cocoa contain functions that return the current highlight color, as well as other important colors in the user interface. Your application should use these defined colors in any custom controls you create, rather than hard-coding in specific color values.

### <span id="page-180-1"></span>Selecting With the Mouse

The user can select a range of text by dragging. A range can consist of characters, words, lines, or paragraphs, as defined by the application.

In text fields, clicking should perform the following actions:

- Single-clicking places the insertion point at the pointer's location in the text.
- <span id="page-180-2"></span>■ Double-clicking within a word selects the word. The selection should provide "smart" behavior; if the user deletes the selected word, for example, the space after the word should also be deleted.
- Double-clicking in a space selects the space.

Selecting **181**

### User Input

<span id="page-181-3"></span>■ Triple-clicking selects the next logical unit, as defined by the application. In a word-processing document, triple-clicking in a word selects the paragraph containing the word. In a table, triple-clicking selects the cell.

### <span id="page-181-2"></span><span id="page-181-1"></span><span id="page-181-0"></span>What Constitutes a Word

The following definition of a word applies in the United States, Canada, and some other countries. In many countries, the definition differs to reflect local formats for numbers, dates, and currency. Double-clicking a character *not* in the list below results in the selection of only that character.

A word is defined as any continuous string that contains any of the following characters:

- a letter
- a digit
- a nonbreaking space (Option-space or Command-space)
- a currency symbol (\$, ¢, £, ¥)
- a percent sign
- a comma between digits
- a period before a digit
- an apostrophe between letters or digits
- a hyphen, but not Option-hyphen (–) or Option-Shift-hyphen (—)

These are examples of words:

- \$123,456.78
- shouldn't
- 3 1/2 (with a nonbreaking space)
- .5%

These are examples of strings treated as more than one word:

- 7/10/6
- blue cheese (with a regular space)
- "Wow!" (The quotation marks and exclamation point are not part of the word.)

In some contexts—in a programming language, for example—it may be appropriate to allow users to select both the left and right parentheses (or braces or brackets) in a pair, as well as all the characters between them, by double-clicking either one of them. That would mean that a user could select the entire expression

$$[x+y-(4*3)^{n-1}]$$

by double-clicking [ or ].

For more information about defining strings as words, see *Inside Macintosh: Text.*

### <span id="page-182-5"></span><span id="page-182-0"></span>Selecting Text With the Arrow Keys

See "Extending Text Selection With the Shift and Arrow Keys" (page 165).

## <span id="page-182-4"></span><span id="page-182-1"></span>Selections in Graphics

There are several conventions for selecting graphic objects. This section describes two ways to show selection feedback; other situations may require other solutions.

An object-based graphics document is a collection of individual graphic objects. To select an object, the user clicks it once. The object is then bracketed with handles, which the user can use to move or resize the item.

In object-based graphics applications, there are two ways to select more than one object at a time. A user can drag a dotted rectangle and select every object that falls completely within the rectangle's outline, or the user can use the Shift key to select particular objects.

In a bitmap-based graphics document—where images are a series of pixels rather than discrete objects—a user selects the range of pixels enclosed within a selection tool.

## <span id="page-182-3"></span><span id="page-182-2"></span>Selections in Arrays and Tables

To select a single field (cell), the user clicks in it. The user can also select a field by moving to it with the Tab or Return key.

To select part of the contents of a field, the user must first select the field, then click again to select the desired part.

Selecting **183**

A user should be able to select a row or column in a table by clicking a header, for example. Tables can also support Command-click for selecting discontinuous fields.

Pressing the Tab key cycles through the fields in an order determined by your application, and Shift-Tab navigates in the opposite direction. Typically, the sequence is from left to right, then from top to bottom. Pressing Tab from the last field selects the first field.

<span id="page-183-4"></span><span id="page-183-3"></span>The Return key selects the first field in the next row; Shift-Return selects the previous row. If the concept of rows doesn't make sense in a particular context, the Return key should have the same effect as the Tab key.

## <span id="page-183-0"></span>Editing Text

In addition to the methods for selecting text, there are a number of ways to edit text.

### <span id="page-183-6"></span><span id="page-183-1"></span>Inserting Text

To insert text, the user positions the insertion point by clicking where the text is to go, then starts typing. The application moves the insertion point to the right (or left, depending on the language) as each new character is added.

Applications with multiple-line text blocks should support **word wrap,** the automatic continuation of text from the end of one line to the beginning of the next without breaking in the middle of a word.

### <span id="page-183-5"></span><span id="page-183-2"></span>Deleting Text

When the user presses the Delete (or Backspace) key, one of two things happens:

- If text is selected, the entire selection is deleted.
- If there is no current selection, the character preceding the insertion point is deleted.

In either case, the insertion point replaces the deleted character or characters in the document. The deleted characters don't go on to the Clipboard, but the user can undo the deletion by immediately choosing Undo from the Edit menu.

You can also implement the keyboard combination Option-Delete (or Option-Backspace) to delete the word that currently contains the insertion point. Be sure to document this behavior if you implement it.

If a keyboard has a Forward Delete (Del) key, the character following the insertion point is deleted each time the user presses the key.

### <span id="page-184-3"></span><span id="page-184-0"></span>Replacing a Selection

If the user starts typing when one or more characters are selected, the typed characters replace the selection. The deleted characters don't go on to the Clipboard, but the user can undo the replacement by immediately choosing Undo from the Edit menu.

## <span id="page-184-2"></span><span id="page-184-1"></span>Intelligent Cut and Paste

Intelligent cut and paste is a set of editing features that takes into account the need for spaces between words. To understand why this feature is helpful, consider the following sequence of events in a text application *without* intelligent cut and paste:

1. A sentence in the user's document reads

*Returns are only accepted if the merchandise is damaged.*

The user wants to change this to

*Returns are accepted only if the merchandise is damaged.*

- 2. The user selects the word *only* by double-clicking. The letters are highlighted, but neither adjacent space is selected.
- 3. The user chooses Cut from the Edit menu, clicks just before the word *if,* and chooses Paste.
- 4. The sentence now reads

*Returns are accepted onlyif the merchandise is damaged.*

Editing Text **185**

To correct the sentence, the user has to remove the extra space between *are* and *accepted,* and add a space between *only* and *if.*

If your application supports intelligent cut and paste, follow these guidelines:

- If the user selects a word or a range of words, the selection itself is highlighted, but spaces adjacent to the selection are not highlighted.
- When the user chooses Cut, if the character preceding the selection is a space, cut that space along with the selection. If the character preceding the selection is not a space, but the character following the selection is a space, cut that space along with the selection.
- When the user chooses Paste, if the character to the left or right of the current selection is part of a word (but not inside a word), insert a space before pasting.

Use intelligent cut and paste only if the application supports the definition of a word as described in ["What Constitutes a Word" \(page 182\)](#page-181-1). These rules apply to any selection consisting of one or more whole words, no matter how the user made the selection.

**Note:** Intelligent cut and paste doesn't apply to all languages. Thai, Chinese, and Japanese, for example, don't contain spaces.

### <span id="page-185-1"></span><span id="page-185-0"></span>Editing Text Fields

If your application isn't primarily a text application, but it has text entry fields in dialogs, for example, you may not need to provide the full text-editing features described in this section. The application should, however, be forward-compatible with the full text-editing capabilities. The application should support the following capabilities:

- The user can select the whole field and type in a new value, delete text, select a substring of the field and replace it, and select a word by double-clicking.
- The user can choose Undo, Cut, Copy, Paste, and Delete, as described in ["The](#page-57-0)  [Edit Menu" \(page 58\)](#page-57-0).

Your application can also support intelligent cut and paste.

Even applications with only minimal text editing should perform appropriate edit checks. For example, if the only legitimate value for a field is a string of digits, the application should alert the user if any nondigits are typed.

### <span id="page-186-1"></span><span id="page-186-0"></span>Entering Passwords

When a user types a password into a text field, each typed character should appear as a bullet, matching the number of characters typed by the user. If the user deletes a character with the Delete key, one bullet is deleted from the text field and the insertion point moves back one bullet, as if the bullet represented an actual character. Double-clicking bulleted text in a password field selects all the bullets in the text field.

When the user leaves the text field (by pressing Tab, for example), the number of bullets in the text field should be modified so that the field does not reflect the actual number of characters in the password.

Editing Text **187**

User Input

# <span id="page-188-5"></span><span id="page-188-0"></span>10 Fonts

Mac OS X supports six standard fonts for interface elements.

<span id="page-188-2"></span><span id="page-188-1"></span>**Figure 10-1** Mac OS X standard fonts

| Font |
|------|
|      |
|      |
|      |
|      |
|      |
|      |
|      |

<span id="page-188-8"></span><span id="page-188-3"></span>The **system font** is used for text in menus, modeless dialogs, and titles of document windows. For an example of this font, open a Finder menu.

<span id="page-188-7"></span><span id="page-188-4"></span>**Note:** For text in lists and tables, you can use 12-point Lucida Grande Regular instead of the system font.

<span id="page-188-6"></span>The **small system font** is used for informative text in alerts (see [Figure 6-2 \(page 96\).](#page-95-0) It is also the default font for headers in lists, for help tags, and for text in the small versions of many controls. You can also use it to provide additional information about settings in various windows, such as the QuickTime pane in System Preferences.

Fonts

If your application creates text documents, use the **application font** as the default for user-created content.

<span id="page-189-4"></span><span id="page-189-3"></span>The **label font** is used for labels with controls such as sliders and icon bevel buttons. You should rarely need to use this font in dialogs, but may find it useful in palettes. For an example of this font used to label a slider control, click the Text-to-Speech tab in Speech preferences.

Use **emphasized system fonts** sparingly. Emphasized (bold) system font is used in only two places in the interface: the application name in an About window (see ["The About Window" \(page 88\)](#page-87-0)) and the message text in an alert (see [Figure 6-2](#page-95-0) [\(page 96\)\)](#page-95-0). You might use emphasized small system font to title a group of settings that appear without a group box, or for brief informative text below a text field. For an example of the emphasized small system font, click the Date or Numbers tab in International preferences.

<span id="page-189-2"></span><span id="page-189-1"></span><span id="page-189-0"></span>Carbon developers creating nonstandard elements with text are responsible for drawing their own anti-aliased text, via the Appearance Manager DrawThemeTextBox functions or the Control Manager static text control. In Cocoa, all text is anti-aliased by default.

<span id="page-190-5"></span><span id="page-190-4"></span><span id="page-190-0"></span>This chapter describes the overall philosophy behind Aqua icons and how to design application, document, toolbar, and other types of icons for Mac OS X.

## <span id="page-190-1"></span>What's New in Aqua

### <span id="page-190-2"></span>More Realistic Icons

Icon design in Mac OS X is significantly different from previous versions of the Mac OS. In Mac OS 9 and earlier, graphic limitations constrained designers to use a highly symbolic style. Icons consisted of "jaggy" illustrations that emphasized straight lines rotated in increments of 45 degrees.

<span id="page-190-3"></span>**Figure 11-1** Traditional application icon and Mac OS X icon

![](images/_page_190_Picture_7.jpeg)

![](images/_page_190_Picture_8.jpeg)

Aqua offers a new photo-illustrative icon style—it approaches the realism of photography, but uses the features of illustrations to convey a lot in a small space. Icons can be represented in 128 x 128 pixels to allow ample room for detail. Anti-aliasing makes curves and nonrectilinear lines possible. Alpha channels and translucency allow for complex shading and dimensionality. All of these qualities pave the way for lush imagery that enables you to create vibrant icons that communicate in ways never before possible.

To represent your application in Mac OS X, it's essential to create high-quality Aqua-style application icons that scale well in the various places the icon appears the Dock, Finder previews, alert dialogs, and so on.

## <span id="page-191-2"></span><span id="page-191-0"></span>Icon Genres and Families

<span id="page-191-3"></span><span id="page-191-1"></span>A new concept in Mac OS X is the notion of icon genres, which help communicate what you can do with an application before you open it. Applications are classified by role—user applications, software utilities, and so on—and each category has its own icon style. This differentiation is very important for helping users easily distinguish between types of icons in the Dock.

**Figure 11-2** Application icons of different genres—user applications and utilities—shown as they might appear in the Dock

![](images/_page_191_Picture_7.jpeg)

For example, the icons for user applications are colorful and inviting, while utilities have a more serious appearance. Figure 11-3 shows user application icons in the top row and utility icons in the bottom row. These genres are further described in ["User](#page-193-4)  [Application Icons" \(page 194\)](#page-193-4) and ["Utility Icons" \(page 197\).](#page-196-4)

<span id="page-192-0"></span>**Figure 11-3** Two icon genres: User application icons in top row, utility icons in bottom row

![](images/_page_192_Picture_3.jpeg)

The graphic flexibility of Aqua icons can also help users identify files associated with an application. In iTunes, for example, a visual cue provided in the application icon is carried over into icons for other files associated with iTunes, forming an icon family, as shown in Figure 11-4.

<span id="page-193-3"></span>**Figure 11-4** An icon family: The iTunes application icon and its associated icons

![](images/_page_193_Picture_3.jpeg)

## <span id="page-193-0"></span>Types of Icons

## <span id="page-193-6"></span><span id="page-193-5"></span><span id="page-193-1"></span>Application Icons

### <span id="page-193-4"></span><span id="page-193-2"></span>User Application Icons

Mac OS X user application icons should be vibrant and inviting, and should immediately convey the application's purpose. The TextEdit icon, for example, indicates clearly that you would use this application to create text documents.

<span id="page-194-0"></span>**Figure 11-5** The TextEdit application icon makes it obvious what this application is for

![](images/_page_194_Picture_3.jpeg)

If the primary function of your application is creating or handling media, its icon should display the media the application creates or views. If appropriate, the icon should also contain a tool that communicates the type of task the application allows the user to accomplish. The Preview icon, for example, uses a magnification tool to help convey that the application can be used to view pictures. If you include a supportive tool element, it should closely relate to the base object that it rests upon.

<span id="page-194-1"></span>**Figure 11-6** The Preview application icon: An example of a tool element

![](images/_page_194_Picture_6.jpeg)

In the Stickies application icon, however, the yellow rectangles are easily identifiable as sticky notes; the icon doesn't include a tool because it isn't necessary to tell the icon's story.

Types of Icons **195**

<span id="page-195-1"></span>**Figure 11-7** The Stickies application icon: Effective without the addition of a tool

![](images/_page_195_Picture_3.jpeg)

Notice that the text in the Stickies icon is actual text, not simply wavy lines representing text. If you want to "greek" text in an Aqua icon, use actual text and make it unreadable by shrinking it or doubling the layers.

Generally, Mac OS X user application icons are designed to appear as if they're sitting on a desk in front of you. They have a slightly diminishing perspective (they are wider at the bottom). For more information, see ["Icon Perspectives" \(page 202\).](#page-201-3)

### <span id="page-195-0"></span>Viewer, Player, and Accessory Icons

Some applications that represent objects, such as QuickTime Player and Calculator, are most easily recognized by the objects themselves. When creating icons for such applications, it's more aesthetically pleasing to create a simplified, idealized representation of the object, rather than using an actual screen shot of the software. Re-creating the object is particularly important when users could confuse the icon with the actual interface.

<span id="page-195-2"></span>**Figure 11-8** The icons for QuickTime Player, Calculator, and Chess

![](images/_page_195_Picture_9.jpeg)

![](images/_page_195_Picture_10.jpeg)

![](images/_page_195_Picture_11.jpeg)

These icons, many of which are a precursor of what you'll see when you open the application, use a straight-on perspective (rather than the "on a desktop" user application style). You never see the Calculator on screen in three dimensions, for example, so its icon doesn't depict it that way.

### <span id="page-196-4"></span><span id="page-196-0"></span>Utility Icons

Icons for utility applications—which are used less often and not simply for fun or creative activities— convey a more serious tone than those for user applications. Color in these icons is desaturated, predominantly gray, and added only when necessary to clearly communicate what the applications do.

<span id="page-196-3"></span>**Figure 11-9** Discriminating use of color in the Process Viewer and Print Center icons

![](images/_page_196_Figure_6.jpeg)

![](images/_page_196_Figure_7.jpeg)

<span id="page-196-5"></span>Because utility applications are normally focused on a narrow set of tasks, it's best to keep the number of elements in the icon to a minimum. The focus should be a single object that represents what the utility does. The perspective of utility icons is straight-on, as if they are on a shelf in front of you. For more information, see ["Icon](#page-201-3)  [Perspectives" \(page 202\)](#page-201-3).

## <span id="page-196-6"></span><span id="page-196-1"></span>Non-Application Icons

### <span id="page-196-2"></span>Document Icons

Traditionally, a document icon looks like a piece of paper with its top-right corner folded down. As previously suggested, Aqua document icons should make it obvious which application they are associated with. Preview documents, for

Types of Icons **197**

example, include a graphic of the media (the pictures) used in the application icon. For simplicity and to avoid confusing the document with the application itself, the viewing tool is not repeated in the document icon.

<span id="page-197-0"></span>**Figure 11-10** Icons for the Preview application and a Preview document

![](images/_page_197_Picture_4.jpeg)

![](images/_page_197_Picture_5.jpeg)

Document icons are presented as if they are hovering on the desktop, with the shadow behind the document. For more information, see ["Icon Perspectives"](#page-201-3) [\(page 202\).](#page-201-3)

In cases where you want to put an identifying badge over a document icon, treat the badge as an integrated element within the document, instead of putting it over the top of the base image and breaking out of the overall document shape.

<span id="page-197-1"></span>**Figure 11-11** Incorrect and correct badging of a document icon

![](images/_page_197_Picture_9.jpeg)

Don t do this. Do this.

![](images/_page_197_Picture_11.jpeg)

### <span id="page-198-5"></span><span id="page-198-0"></span>Icons for Preferences and Plug-ins

<span id="page-198-2"></span>The files that store user preferences are identified by a light switch on the left side.

**Figure 11-12** Icons for a preferences application (System Preferences) and for a file that stores preferences (for the iTunes application)

![](images/_page_198_Picture_5.jpeg)

Plug-in icons look like stackable components, with the associated application identifier on the left side and a plug-in–specific image on the right.

<span id="page-198-3"></span>**Figure 11-13** A plug-in icon

![](images/_page_198_Picture_8.jpeg)

### <span id="page-198-4"></span><span id="page-198-1"></span>Icons for Hardware and Removable Media

Hardware icons represent devices as you most often see them: on your desk. Because these devices are also frequently handled and carried, people are familiar with them as three-dimensional objects with weight. The Aqua treatment of hardware icons reinforces their association with real objects.

Types of Icons **199**

<span id="page-199-0"></span>**Figure 11-14** Icons for external (top row) and internal hardware devices

![](images/_page_199_Picture_3.jpeg)

To help users distinguish between external devices, their icons provide a region for an identifying symbol (FireWire, SCSI, and so on).

<span id="page-199-2"></span>Removable media such as CDs, floppy disks, and PC cards are depicted the way they look when you hold them in front of you—that is, the perspective is straight on.

<span id="page-199-1"></span>**Figure 11-15** Icons for removable media

![](images/_page_199_Picture_7.jpeg)

### <span id="page-200-3"></span><span id="page-200-0"></span>Toolbar Icons

<span id="page-200-1"></span>The concept behind toolbars is that they provide access to items as if they were sitting on a shelf in front of you. Toolbars should conserve screen real estate while still being inviting and easily clickable; 32 pixels by 32 pixels is the recommended size for toolbar icons.

**Figure 11-16** Finder toolbar icons

![](images/_page_200_Picture_5.jpeg)

Each toolbar icon should be easily and quickly distinguishable from the other items in the toolbar. Toolbar icons emphasize their outline form. As shown in Figure 11-17, each Finder toolbar icon's shape is unique.

<span id="page-200-2"></span>**Figure 11-17** Toolbar icons and their dominant shapes

![](images/_page_200_Picture_8.jpeg)

Note that although each Finder toolbar icon has a unique shape, the icons harmonize together in their perspective, use of color, size, and visual weight.

Although icons designed specifically for use in a toolbar appear as if they are sitting on a shelf in front of you, if you place a very recognizable object from elsewhere in the interface in a toolbar, the object should retain its perspective. That is, don't redesign a toolbar version of a well-known interface element.

Types of Icons **201**

<span id="page-201-1"></span>**Figure 11-18** The circled icons appear elsewhere in the interface; they retain their perspective when used in a toolbar

![](images/_page_201_Picture_3.jpeg)

<span id="page-201-5"></span>For toolbars in applications, you can start with a consistent "look" when it makes sense, and introduce differences when necessary. In the Mail application toolbar, for example, the Reply, Reply All, Forward, and Bounce buttons—all for actions the user can apply to a selected received message—use a stamp as the dominant symbol. Because the Bounce button is potentially destructive (the user can no longer read the bounced message), its icon is red. The pencil is depicted in recognizable and realistic yellow.

<span id="page-201-2"></span>**Figure 11-19** The Mail toolbar

![](images/_page_201_Picture_6.jpeg)

<span id="page-201-4"></span>Creating a family of icons helps make an application recognizable and unique. Mail, for example, uses blue and white as dominant colors.

## <span id="page-201-3"></span><span id="page-201-0"></span>Icon Perspectives

The angles and shadows used for depicting various kinds of icons are intended to reflect how the objects would appear in reality. All Aqua interface elements have a common light source from directly above, not from the upper-left corner as in Mac OS 9 and earlier. The various perspectives are achieved by changing the position of the camera capturing the icon.

<span id="page-202-0"></span>Application icons look like they are sitting on a desk in front of you.

**Figure 11-20** Perspective for application icons: Sitting on a desk in front of you

![](images/_page_202_Picture_4.jpeg)

<span id="page-202-1"></span>Utility icons are depicted as if they are on a shelf in front of you. Flat objects appear as if there is a wall behind them with an appropriate shadow behind the object.

**Figure 11-21** Perspective for flat utility icons: On a shelf in front of you, with a shadow on the wall behind

![](images/_page_202_Picture_7.jpeg)

An actual three-dimensional object such as a rocket, however, would more realistically be viewed sitting on the ground; its icon shows the rocket sitting on a shelf, with its shadow below it.

<span id="page-203-1"></span>**Figure 11-22** Perspective for three-dimensional object: Sitting on a shelf in front of you, with the shadow below the object

![](images/_page_203_Picture_3.jpeg)

<span id="page-203-3"></span><span id="page-203-2"></span>For toolbar icons, the perspective is also straight-on, as if the object is on a shelf in front of you.

**Figure 11-23** Perspective for toolbar icons: Straight-on, with subtle shadow on the "floor"

![](images/_page_203_Picture_6.jpeg)

## <span id="page-203-0"></span>Icon Materials

Icons that represent actual objects should look they are made of real materials. Examine various objects to study the characteristics of plastic, glass, paper, and metal. Your icon will look more realistic if you successfully convey the item's weight and feel, as well as its appearance.

Use transparency only when it is convincing and when it helps complete the story the icon is telling. You would never see a transparent sneaker, for example, so don't use one in your icon.

<span id="page-204-1"></span>**Figure 11-24** Materials: Transparency used to convey meaning

![](images/_page_204_Picture_4.jpeg)

## <span id="page-204-0"></span>Conveying an Emotional Quality in Icons

Figure 11-25 illustrates the difference between communicating a message in a straightforward way compared with presenting the same message with an emotive quality. In an appropriate context, we would recognize the figure on the left as the symbol for men's bathroom. The figure on the right, however, tells a story even when it is viewed outside of its context.

<span id="page-204-2"></span>**Figure 11-25** Being emotive: The same message conveyed two ways

![](images/_page_204_Picture_8.jpeg)

<span id="page-204-3"></span>![](images/_page_204_Picture_9.jpeg)

## <span id="page-205-0"></span>Suggested Process for Creating Aqua Icons

<span id="page-205-1"></span>You need to provide at least the following files:

- a 128 by 128 image (for Finder icons)
- a mask that defines the image's edges, so the operating system can determine which regions are clickable

Icons that display in the Finder are viewed at different sizes: they can be magnified in the Dock, they can be previewed at full size, and users can specify a preferred size. For the best-looking icons at all sizes, you should also provide customized image files ("hints") at three other sizes: 64 x 64, 32 x 32, and 16 x 16. Although the Dock doesn't use hints (it uses a sophisticated algorithm on the 128 x 128 version), hints are important for preserving crucial details in Finder icons.

If you are creating an icon that will never change size—on a bevel button, for example—you can supply the image only at actual size.

Here are the suggested steps for creating an icon:

1. Sketch the icon.

Work out the concept and details of your design on paper, not with software. You should be ready to execute the idea by the time you open an application.

2. Create a software illustration of the icon.

Although you may want the final icon to look like a photograph, in most cases it's inadvisable to start with an actual photograph. An illustration provides much more flexibility for conveying a concept in a very small space. An illustration also gives you necessary control over details, perspective, light and shadow, texture, and so on.

3. Add detail and color.

For each enhancement you make to a larger-version icon, consider whether it is truly adding something to the icon's usability, or whether it is just adding complexity or clutter.

4. Add shadows.

Shadows give objects dimensionality and realism. They also help tie the elements of an icon together so it doesn't look like a collage. The light source should be above and slightly in front of the object. The resulting shadow should create the sense that the icon is resting on a surface.

- 5. In an image-editing program, manipulate the image to get precise effects and create the icon mask.
- 6. Convert the icon to a .icns file.

<span id="page-206-1"></span>You can complete this step with Icon Composer, included on the Mac OS X Developer Tools CD. There are also several third-party tools available for completing this step.

## <span id="page-206-0"></span>Tips for Designing Aqua Icons

Many of the suggestions listed here also apply to graphics you develop for your application, for example, to augment a label or list item.

- For great-looking Aqua icons, have a professional graphic designer create them.
- Perspective and shadows are the most important components of making good Aqua icons. Use a single light source with the light coming from above the icon.
- Use universal imagery that people will easily recognize. Avoid focusing on a secondary aspect of an element. For example, for a mail icon, a rural mailbox would be less recognizable than a postage stamp.
- Strive for simplicity. Try to use a single object that captures the icon's action or represents the control. Start with a basic shape.
- Use color judiciously to help the icon tell its story; don't add color just to make the icon more colorful. Smooth gradients typically work better than sharp delineations of color.
- Avoid using Aqua interface elements in your icons; they could be confused with the actual interface.
- Don't use replicas of Apple hardware products in your icons. These symbols are copyrighted and hardware designs change frequently.

Icons

<span id="page-207-0"></span>■ Design toolbar icons at their actual size (32 by 32). For other icons, concentrate on perfecting your icon's look at 128 by 128 and work down from there. It usually works best if you scale down elements independently and then combine them, rather than scaling the entire icon at once.

<span id="page-208-3"></span><span id="page-208-0"></span>The technique of dragging an item and dropping it on a suitable destination is called **drag and drop.**

In this chapter, an item is anything that the user can select, such as text, graphics, and icons. For convenience, this chapter assumes that the user is dragging with the mouse, but these guidelines also apply to other input devices such as pens and trackballs.

<span id="page-208-4"></span>In Aqua, the Finder provides a new focus to indicate the target for a drop.

## <span id="page-208-1"></span>Drag and Drop Design Overview

<span id="page-208-2"></span>Ideally, users should be able to drag any content from any window to any other window that accepts the content's type. If the source and destination are not visible at the same time, the user can create a **clipping** by dragging data to a Finder window; the clipping can then be dragged into another application window at another time.

Drag and drop should be considered an ease-of-use technique. Except in cases where drag and drop is so intrinsic to an application that no suitable alternative methods exist—dragging icons in the Finder, for example—there should always be another method for accomplishing a drag-and-drop task.

The basic steps of the drag-and-drop interaction model parallel a copy-and-paste sequence in which you select an item, choose Copy from the Edit menu, specify a destination, and then choose Paste. However, drag and drop is a distinct technique

<span id="page-209-9"></span><span id="page-209-2"></span>in itself, and the Drag Manager does not use the Clipboard. Users can take advantage of both the Clipboard and drag and drop without side effects from each other.

A drag-and-drop operation should provide immediate feedback at the significant points: when the data is selected, during the drag, when an appropriate destination is reached, and when the data is dropped. The data that is pasted should be target-specific. For example, if a user drags an Address Book entry to the "To" text field in Mail, only the email address is pasted, not all of the person's address information.

<span id="page-209-4"></span><span id="page-209-3"></span>You should implement Undo for any drag-and-drop operation you enable in your application. If you implement a drag-and-drop operation that is not undoable, display a confirmation dialog before implementing the drop. A confirmation dialog appears, for example, when the user attempts to drop an icon into a write-only drop box on a shared volume, because the user does not have privileges to open the drop box and undo the action.

## <span id="page-209-0"></span>Drag and Drop Semantics

### <span id="page-209-7"></span><span id="page-209-5"></span><span id="page-209-1"></span>Move Versus Copy

Your application must determine whether to move or copy a dragged item after it is dropped on a destination. The appropriate behavior depends on the context of the drag-and-drop operation, as described here.

<span id="page-209-8"></span><span id="page-209-6"></span>If the source and destination are in the same container (for example, a window or a volume), a drag-and-drop operation is interpreted as a move (that is, cut and paste). Dragging an item from one container to another initiates a copy (copy and paste). The user can perform a copy operation within the same container by pressing the Option key while dragging.

<span id="page-209-10"></span>You can't assume that a window is always a container; you must consider the underlying data structure of the contents in the window. For example, if your application allows two windows to display the same document (multiple views of the same data), a drag-and-drop operation between these two windows should result in a move.

### Drag and Drop

<span id="page-210-4"></span><span id="page-210-2"></span>The principle driving these drag-and-drop guidelines is to prevent the user from accidental data loss. Moving data across applications may result in potential data loss because an Undo command in the destination application does not trigger an Undo in the source application. Moving data within the same window (or same volume, as in the case of the Finder) does not lead to data loss.

<span id="page-210-3"></span><span id="page-210-1"></span>**Table 12-1** Common drag-and-drop operations and results

<span id="page-210-5"></span>

| Dragged item       | Destination             | Result                    |
|--------------------|-------------------------|---------------------------|
| Data in a document | The same document       | Move                      |
| Data in a document | Another document        | Copy                      |
| Data in a document | The Finder              | Copy (creates a clipping) |
| Finder icon        | An open document window | Copy                      |
| Finder icon        | The same volume         | Move                      |
| Finder icon        | Another volume          | Copy                      |

### <span id="page-210-7"></span><span id="page-210-0"></span>When to Check the Option Key State

<span id="page-210-6"></span>Your application should check whether the Option key is pressed at drop time. This behavior gives the user the flexibility of making the move-or-copy decision at a later point in the drag-and-drop sequence. Pressing the Option key during the drag-and-drop sequence should not "latch" for the remainder of the sequence.

**Note:** The Option key does not act as a toggle switch; Option-dragging between containers always initiates a copy operation. This guideline allows users to learn that Option means copy.

## <span id="page-211-0"></span>Selection Feedback

<span id="page-211-5"></span>This section covers issues that deserve special mention in the context of drag and drop. Selection feedback is discussed in more detail in ["Selecting" \(page 176\)](#page-175-1).

### <span id="page-211-8"></span><span id="page-211-1"></span>Single-Gesture Selection and Dragging

<span id="page-211-6"></span>Because dragging is defined as moving the mouse while the mouse button is held down, a mouse-down event must occur before dragging can take place. A selection may be made as a result of this mouse-down event, just before the user starts dragging. For example, the user can select and drag a folder icon in a single gesture; the user does not have to click the folder icon first, release the mouse button, and then press again to begin dragging the icon. Your application should ensure that implicit selection occurs, when appropriate, when the user starts dragging.

<span id="page-211-7"></span>Single-gesture selection and dragging is possible only when the process of selecting an item does not require dragging. Range-selection operations—such as selecting text or dragging a marquee around graphic objects—don't lend themselves to single-gesture selection and dragging because the range-selection operation itself requires dragging.

## <span id="page-211-4"></span><span id="page-211-2"></span>Background Selections

<span id="page-211-9"></span>When a window containing a highlighted selection becomes inactive, your application can maintain the selection. This feature enables users to drag previously selected data from inactive windows to the active window.

<span id="page-211-3"></span>Background selections are not required if the dragged item is discrete, such as an icon or graphical object, because implicit selection can occur when an item is dragged. However, items selected only by range-selection operations such as text or a group of icons must have a background selection to allow the user to drag these items out of inactive windows. Whenever an inactive window is made active, the background selection, if any, becomes highlighted as a normal selection.

## <span id="page-212-0"></span>Drag Feedback

<span id="page-212-4"></span>Your application should provide drag feedback as soon as the user drags an item at least three pixels. If a user holds the mouse button down on selected text for 300 milliseconds, the selected text becomes draggable, as long as the mouse remains down. Carbon and Cocoa provide mechanisms for automatically handling drag feedback. In Aqua, dragged items are transparent.

## <span id="page-212-1"></span>Destination Feedback

<span id="page-212-3"></span>If the user drags an item to a destination in your application, your application provides feedback that indicates whether it will accept that item. Destination feedback should not occur simply because your application is "drag-aware"; rather, it should depend on the destination's ability to accept the type of data contained in the dragged item. For example, a text entry field that accepts only text should not be highlighted when the dragged item is a graphic.

<span id="page-212-7"></span><span id="page-212-5"></span>The actual appearance of destination feedback depends on the type of destination. The Drag Manager provides some utilities for simple highlighting; if your application needs more complex highlighting, you must provide your own highlighting utilities.

### <span id="page-212-6"></span><span id="page-212-2"></span>Windows

The valid **destination region** of a document window is usually the window's content area minus the title bar and areas used for controls (such as scroll bars, resize controls, tool palettes, rulers, and placards). When there are multiple destination regions within a window, only one destination region is highlighted at a time.

Drag Feedback **213**

When the user drags an acceptable item from one destination region to another, your application highlights the destination region as soon as the pointer enters it, and removes the highlighting when the pointer leaves the region. You can use the Drag Manager to specify your destination regions.

If a drag-and-drop operation takes place entirely within one destination region (moving a document icon to a different location in the same folder window, for example), don't highlight the destination region, to avoid distracting the user. However, if the user drags an item completely out of a destination region and then drags the same item back to the same destination region, the destination region should be highlighted.

You can provide more specific destination feedback within a larger destination region. For example, when the user drags text from one document window to another, the inactive window should display an insertion point where the dragged text would go if the user releases the mouse button.

<span id="page-213-2"></span>In many situations, highlighting a more narrowly defined area of a window is more appropriate than highlighting the entire content region; examples are spreadsheets, text boxes, fill-in forms, and panes. In these cases, the destination region must be tailored to more precisely indicate the specific destination.

### <span id="page-213-4"></span><span id="page-213-3"></span><span id="page-213-0"></span>Text

While the user is dragging an item to a text area, an insertion indicator (a vertical bar) should appear in the text where the dragged item would be inserted if the user releases the mouse button.

## <span id="page-213-1"></span>Multiple Dragged Items

If the user drags multiple items, the destination feedback should occur only if it can accept all of the dragged items. If the destination cannot accept all of the dragged items, the user's attempt results in feedback as described in ["Feedback for an](#page-216-2)  [Invalid Drop" \(page 217\)](#page-216-2).

When the destination can accept all of the dragged items, the destination should accept them in the order specified by the source. The source application should organize the dragged items in the order in which they were selected, except in two cases. If the dragged items come from ordered views (such as View by Date or an

alphabetized list), that view's ordering takes precedence over the selection order. If both the source and destination provide a spatial ordering (such as in graphic applications), the spatial ordering takes precedence over the selection order.

### <span id="page-214-3"></span><span id="page-214-0"></span>Automatic Scrolling

When an item is being dragged, your application must determine whether to scroll the contents or allow the item to "escape" the window. If your application allows items to be dragged outside of windows, you should define an autoscrolling region. Automatically scroll a destination window only if it is also the source window and is frontmost. Don't autoscroll inactive windows.

### <span id="page-214-6"></span><span id="page-214-1"></span>Using the Trash as a Destination

The Drag Manager makes the Trash available to applications.

Dragging items to the Trash results in moving the item from the source to the Trash. For example, dragging a text selection from a word-processing application and dropping it on the Trash icon (or in the Trash window) results in the text being deleted from the application and a clipping containing that text being created inside the Trash. Note that the item is moved, although it is dragged between two containers. This exception to the rules described earlier is appropriate because the user can undo the operation by dragging the clipping out of the Trash back to its original source; it is consistent with the principle of preventing accidental data loss.

<span id="page-214-5"></span><span id="page-214-4"></span>It is important to preserve the Trash's container property; do not simply delete the source without creating a clipping or other item in the Trash.

## <span id="page-214-2"></span>Drop Feedback

When the user releases the mouse button after dragging an item to a destination, feedback should inform the user that the drag-and-drop operation was successful. While this feedback can be visual, it is primarily behavioral in nature. The behavior comes from the semantic operation indicated by the drag-and-drop sequence. Examples of this behavior are given below.

Drop Feedback **215**

### <span id="page-215-6"></span><span id="page-215-0"></span>Finder Icons

<span id="page-215-8"></span>When the user moves an item by dropping its icon on a folder icon, the dropped icon disappears and the highlighting is removed from the destination folder icon.

<span id="page-215-7"></span>If an icon represents a task, such as printing, you may want to provide progress feedback to indicate that the task is being carried out.

## <span id="page-215-1"></span>Graphics

When dropping graphics, the drop feedback is usually the movement of the actual item to the location of the mouse-up event.

### <span id="page-215-9"></span><span id="page-215-2"></span>Text

After text is dropped, it is shown highlighted at its destination.

When text is dropped in a destination that supports styled text, the dropped text should maintain its font, typeface, and size attributes. If the destination does not support styled text, the dropped text should assume the font, typeface, and size attributes specified by the destination insertion point.

Drag-and-drop operations involving text should support intelligent cut-and-paste rules, as explained in ["Intelligent Cut and Paste" \(page 185\)](#page-184-1).

### <span id="page-215-10"></span><span id="page-215-3"></span>Transferring a Selection

After a successful drag-and-drop sequence involving a single window, the selection feedback is maintained at the new location. This behavior provides an important user cue and allows the user to reposition the selection without having to make the selection again.

<span id="page-215-11"></span><span id="page-215-5"></span><span id="page-215-4"></span>If the user drags an item from an active window to an inactive window, the dragged item becomes a **background selection** at the destination; the selection in the active window remains selected. This guideline also applies in the reverse situation, where an item is dragged from an inactive window to an active window.

When content is dropped into a window in which something is selected, your application should deselect everything in the destination before the drop, rather than replacing the selection with the dragged item.

## <span id="page-216-7"></span><span id="page-216-2"></span><span id="page-216-0"></span>Feedback for an Invalid Drop

If a user attempts to drop an item on a destination that does not accept it, the item zooms from its mouse-up location back to its source location (a "zoomback"). The zoomback behavior should also occur when a drop inside a valid destination does not result in a successful operation. The Drag Manager provides this feedback when it determines that no receiver requested the sender's information.

<span id="page-216-8"></span><span id="page-216-6"></span>If the user attempts to drag multiple items to a destination that does not accept all of the items, none of the items should be accepted. In such cases you could display a dialog informing the user of the type of data the destination accepts and which items in the dragged set cannot be accepted.

## <span id="page-216-1"></span>Clippings

<span id="page-216-5"></span><span id="page-216-4"></span><span id="page-216-3"></span>When an item is dragged from an application or a Finder window to the desktop, the Finder creates a clipping that contains the data in the dragged item. If discontinuous selections are dragged from a source to the Finder, a separate clipping is created for each selected item.

Your application should provide a number of representations (such as TEXT, PICT, and native formats) to ensure flexibility with different subsequent destinations. Regardless of which representations are stored, round-trip data integrity should be preserved; a clipping dragged back into its source should be identical to the original item.

When clippings are created, each clipping is given a default name, which is a concatenation of the type of data that was dragged and the word "clipping" (plus a number, if necessary, to avoid naming conflicts). For example, dragging some text from a document to the Finder would generate a file named "text clipping." If the type is unknown, it is omitted from the clipping name.

Clippings **217**

### Drag and Drop

<span id="page-217-0"></span>The user can open clippings in the Finder and view a representation of the data in a modeless window, similar to the Clipboard window. The user cannot select, copy, or edit any of the contents in these windows.

<span id="page-218-6"></span><span id="page-218-0"></span>Mac OS X supports two user help components: Apple Help and help tags. Carbon applications can also use these facilities on Mac OS 8.6 and 9.

Apple Help enables you to display HTML files in Help Viewer, a simple browser. You can also display documents with QuickTime content and AppleScript-based automations, and provide context-sensitive assistance.

<span id="page-218-7"></span><span id="page-218-5"></span>Help tags, which replace the help balloons introduced in System 7, give your application the ability to identify its interface elements.

## <span id="page-218-1"></span>What's New in Aqua

<span id="page-218-3"></span>Apple Help debuted in Mac OS 8.5 and has evolved with each system software release. With Mac OS X, Apple Help introduces the following changes and enhancements:

- new functions for registering help books and calling Help Viewer
- support for "look-up anchor" for use with contextual help
- <span id="page-218-4"></span>■ addition of Developer Help Center for technical documentation
- <span id="page-218-2"></span>■ help packaging within applications
- all features from Mac OS 9 Apple Help, with the exception of launching Apple Guide sequences, which is no longer supported

<span id="page-219-3"></span>In addition, Apple continues to refine the design and information architecture of Mac Help, the onscreen help provided for the Mac OS and Macintosh hardware. The emphasis is on optimizing for onscreen usability, search-driven navigation, and Internet delivery.

## <span id="page-219-0"></span>Apple's Philosophy of Help

<span id="page-219-1"></span>When users refer to help, it is usually because they have reached an impasse while attempting to accomplish a task—they know what they want to do, but not how to accomplish it. When faced with an impasse, most users first try to figure it out for themselves by exploring and experimenting with the interface. If that fails, they ask someone else for assistance; if no one is available, they may consult the onscreen help.

Users come to help with a specific goal in mind, bringing their cumulative Macintosh experience and the recent and cumulative experience of using the product. In all likelihood, they are somewhat impatient and frustrated at having failed to figure out how to accomplish their goal.

To assist users in quickly locating their information and getting back to work, onscreen help should do the following:

- Focus on real-world user tasks.
- Get to the point quickly, so users can return to work.
- Be organized by task, not the layout or functionality of the software.

<span id="page-219-2"></span>In large help systems, searching is often the most efficient way to locate a particular topic, particularly when users have turned to help with a specific idea about what they are trying to accomplish. To facilitate usable search results, do the following:

- Cover one topic per page, to avoid burying some tasks.
- Title the page descriptively, using words that relate to real-world goals.
- Use Apple Help keywords to ensure synonyms and common misspellings get appropriate search results.
- Write steps and descriptions using words that appear in the interface.

Write your help so that users can quickly find the steps on the page and can follow the steps without having to repeatedly switch between the product and the Help Viewer.

- Don't repeat notes and warnings enforced by the interface. For example, if you have to click OK to confirm a setting, don't describe it in the steps—it will be apparent as the users follow the instructions.
- Tailor descriptions to the probable experience of users. For example, a user who wants to adjust kerning is likely to be familiar with selecting a typeface and font size.
- <span id="page-220-4"></span>■ Automate common tasks using AppleScript. If a task requires opening a preferences pane, provide an automation that opens it for users. If you can automate the entire task, do so.
- Emphasize trouble identification and resolution. If a step or task might be impossible because of an error condition, remind users to check for it early in your instructions. Users might already know how to accomplish a task but turn to help because of a condition or requirement they couldn't identify.

## <span id="page-220-0"></span>Help Viewer

<span id="page-220-8"></span><span id="page-220-7"></span><span id="page-220-6"></span><span id="page-220-3"></span><span id="page-220-2"></span>Use Help Viewer to display onscreen documentation. **Help Viewer** is a simple browser that displays HTML, natively displays QuickTime media, provides full-text searching of help with relevancy-ranked results, and provides for task automation using AppleScript. Additionally, Help Viewer allows you to integrate all, or a portion, of Internet-based help files, permitting you to update and improve your instructions as often as necessary.

<span id="page-220-5"></span><span id="page-220-1"></span>The collection of your HTML help files is called a **help book**. When you use Help Viewer, your help book automatically becomes accessible via the Help Center, an Apple-provided location that allows users to easily browse and search all of the help available on their system.

Help Viewer **221**

## <span id="page-221-0"></span>Providing Access to Help

<span id="page-221-6"></span>Users can access the help system in three ways:

- <span id="page-221-5"></span>■ **The Help menu.** The Help menu is the far-right item in the application region of the menu bar. It should contain a single item named "<appName> Help," which opens Help Viewer to the first page of your help content. This page can include hyperlinks that lead to other help resources, such as tutorials, websites, and troubleshooting guides.
  - Don't add additional items to the Help menu unless absolutely necessary; multiple entries that lead to essentially the same place can be confusing.
- <span id="page-221-3"></span>■ **Help buttons.** When necessary, you can use a Help button, typically placed in the lower-left corner of a dialog or window, to provide easy access to specific sections of your help. When a user clicks a Help button, send either a search term or an anchor lookup (which leads to a specific page or pages) to Help Viewer.
  - It's not necessary for every dialog and window in your application to have a Help button. If there is no contextually relevant information in the help, don't display a Help button.
- <span id="page-221-8"></span><span id="page-221-7"></span><span id="page-221-4"></span>■ **Contextual Help menu item.** If contextually appropriate help content is available for an object being pointed to, the first item in the contextual menu is Help.

## <span id="page-221-1"></span>Help Tags

<span id="page-221-2"></span>Help tags are short messages that appear when the user leaves the pointer hovering over an interface element for a few seconds. When the pointer leaves the object, the tag vanishes. Use help tags to assist users in identifying the purpose of interface elements. Help tags are designed to be a replacement for help balloons. You can define an object's help tag in Interface Builder for Carbon and Cocoa applications.

The text of the help tags should

- name an object only if the name is relevant to its function and does not have a text label
- briefly describe what the object does
- be state-independent—help tags always display the same wording, even when an object is dimmed

For example, the help tag for a button labeled "Forward" in an email program might read "Send the selected message to someone else." This provides more detail than the button label, but does not repeat it, and it explains that a message must be selected to enable the button.

It is not necessary for every object have a help tag. Don't provide them for common interface elements, menu items, or items that are self-explanatory or obvious.

If necessary, Carbon developers can implement expanded help tags—text that replaces the original help tag and that further explains the control's function. Users display an expanded help tag by pressing the Command key. Not every tag needs an expanded state.

**Figure 13-1** A help tag and an expanded help tag

![](images/_page_222_Picture_9.jpeg)

<span id="page-222-1"></span>![](images/_page_222_Picture_10.jpeg)

Help tags should always appear in the same place, regardless of the pointer location. The default position for help tags in Carbon applications is below the control, centered horizontally (if necessary, this position can be changed on a per-tag basis).

## <span id="page-222-0"></span>Help Tag Guidelines

Here are some guidelines to help you create effective tag messages.

Help Tags **223**

- Use the fewest words possible. Try to keep your tags to a maximum of 60 to 75 characters. Since help tags are always on, it is important to keep your tag text unobtrusive—that is, *short*—and useful. Present one concept per tag and make sure the concept is directly related to the item. Localization lengthens the text by 20 to 30 percent, which is another good reason to keep the tag short.
- Describe what the user will accomplish. The tag should say what the user wants to know most—what task the user can accomplish by using the item. If absolutely necessary, you can give more information after describing what will be accomplished.
- Create tags that are applicable to all situations. Help tags are not contextually sensitive; the same text appears when an item is selected, dimmed, and so on. By describing what the item accomplishes, you may help the user understand the current state of the control.
- Use help tags to provide functional information for controls that are unique to your application. Don't tag window controls, scroll bars, and other parts of the standard Mac OS X interface.
- Don't put the item's name in the tag unless the name helps the user and isn't available onscreen. If an item is referred to by name in the documentation and in the tag, make sure the names match.
- You can use a sentence fragment beginning with a verb, for example, "Restores default settings." You can also omit articles to limit the size of the tag. If the tag text is a complete sentence, end it with a period.
- Describe only the item the user points to.
- Use hints sparingly.
- If you implement an expanded tag to add another layer of information, don't repeat the text in the original tag. An expanded tag should do one of the following:
  - More fully explain or describe the results of the action described in the small help tag.

*Help tag:* Shuffle the play order.

*Expanded tag:* Plays the current list of songs in random order.

■ Explain when or why the user would do the action described in the small tag.

<span id="page-223-0"></span>*Help tag:* Create folder on player.

*Expanded tag:* Use folders to organize music on the player.

## <span id="page-224-0"></span>Setup Assistants

<span id="page-224-2"></span>For products with complex setup procedures, a **setup assistant,** a small application that guides users through the setup options, can be helpful.

You can open a setup assistant automatically when appropriate—when the system detects a new hardware device or the first time the user opens your application, for example. Ideally, the user should use the assistant only once. Store the assistant in your application's Utilities folder.

<span id="page-224-3"></span>For an icon, use the setup assistant icon with an application badge superimposed in the lower-right corner, as shown in Figure 13-2.

<span id="page-224-1"></span>**Figure 13-2** The icon for AirPort Setup Assistant

![](images/_page_224_Picture_7.jpeg)

Figure 13-3 shows the layout for a sample setup assistant window. Notice that the text is flush left within the inset area, and controls are indented.

Setup Assistants **225**

<span id="page-225-0"></span>**Figure 13-3** A typical setup assistant pane

![](images/_page_225_Picture_3.jpeg)

Keep the following guidelines in mind when designing a setup assistant:

- While the assistant is active, display only the application menu, containing About and Quit items, and the Edit menu, containing standard items to assist users in entering text. Don't provide a Help menu (or a help button); the setup assistant *is* help.
- Provide Go Back and Continue buttons for navigation.
- The assistant window title bar should contain a dimmed close button, an available minimize button, and a dimmed zoom button.
- Title the first pane "Introduction." This pane should explain the purpose of subsequent panes.
- Title the last pane "Conclusion." This pane should tell users what changes were made to their system and how to modify these settings. This pane should have a default Done button and a dimmed Go Back button.
- In most cases, it's best to ask only one question per pane.

### Help

- Provide relevant feedback when appropriate. If needed, you can display a progress bar to the left of the Go Back button (the left edge aligned with the text box).
- <span id="page-226-0"></span>■ Don't fill the entire screen; users should be able to access other parts of their system while the assistant is open.

Setup Assistants **227**

<span id="page-228-3"></span><span id="page-228-0"></span>Although Mac OS X uses graphics as a primary means of user-computer interaction, text is still very prevalent throughout the interface for such things as button names, pop-up menu labels, dialog messages, and onscreen help. Using text consistently and clearly is a critical component of interface design.

Your product team should include a skilled writer who is responsible for reviewing all user-visible onscreen text as well as creating the instructional documentation.

## <span id="page-228-4"></span><span id="page-228-1"></span>Style

<span id="page-228-2"></span>The *Apple Publications Style Guide (APSG)* defines style and usage issues, and it is the key reference for how Apple uses language. This document is available at [http://](http://developer.apple.com/techpubs/faq.html) [developer.apple.com/techpubs/faq.html](http://developer.apple.com/techpubs/faq.html).

For information about specific Mac OS X interface terms, see ["Mac OS X](#page-248-0)  [Terminology Guidelines" \(page 249\)](#page-248-0).

For issues that aren't covered in the *APSG* or the Mac OS X terminology appendix, Apple recommends three other works: *The American Heritage Dictionary, The Chicago Manual of Style,* and *Words Into Type*. In cases where these books give conflicting rules, *The Chicago Manual of Style* takes precedence for questions of usage and the *American Heritage Dictionary* for questions of spelling.

Style **229**

## <span id="page-229-0"></span>Terminology

### <span id="page-229-7"></span><span id="page-229-6"></span><span id="page-229-4"></span><span id="page-229-1"></span>Developer Terms and User Terms

Don't use technical jargon or programming terms in interface elements or user documentation. Table 14-1 shows a few examples; for a more complete list, see the *Apple Publications Style Guide* (available at [http://developer.apple.com/techpubs/](http://developer.apple.com/techpubs/faq.html) [faq.html](http://developer.apple.com/techpubs/faq.html)).

<span id="page-229-3"></span>**Table 14-1** Translating developer terms into user terms

| Developer term    | User term equivalent                              |
|-------------------|---------------------------------------------------|
| Data browser      | Scrolling list or multicolumn list                |
| Dirty document    | Document with unsaved changes                     |
| Focus ring        | Highlighted area; area ready to accept user input |
| User-visible text | Onscreen text                                     |
| Mouse-up event    | Mouse click                                       |
| Reboot            | Restart                                           |
| Byte length       | Number of characters                              |
|                   |                                                   |

### <span id="page-229-5"></span><span id="page-229-2"></span>Labels for Interface Elements

Make labels for interface elements easy to understand and in the user's language. Try to be as specific as possible in any element that requires the user to make a choice, such as radio buttons, checkboxes, and push buttons. It's important to be concise, but don't sacrifice clarity for space.

### <span id="page-230-7"></span><span id="page-230-3"></span><span id="page-230-0"></span>Capitalization of Interface Elements

**Title style** means that you capitalize every word except

- articles (*a, an, the*)
- coordinating conjunctions (*and, or*)
- prepositions of three or fewer letters, except when the preposition is part of a verb phrase, as in Starting Up the Computer.

In title style, always capitalize the first and last word, even if it is an article, a conjunction, or a preposition of three or fewer letters.

<span id="page-230-6"></span>**Sentence style** means that the first word is capitalized, and the rest of the words are lowercase, unless they are proper nouns or proper adjectives. Use periods in dialogs only after complete sentences.

<span id="page-230-1"></span>**Table 14-2** Proper capitalization of onscreen elements

<span id="page-230-5"></span><span id="page-230-4"></span><span id="page-230-2"></span>

| Element      | Capitalization<br>style | Examples                                                                                  |
|--------------|-------------------------|-------------------------------------------------------------------------------------------|
| Menu titles  | Title                   | See the "Highlight color" pop-up<br>menu in General preferences.                          |
| Menu items   | Title                   | Save as Draft<br>Save As<br>Log Out<br>Make Alias<br>Go To<br>Go to Page<br>Outgoing Mail |
| Push buttons | Title                   | Add to Favorites<br>Don't Save                                                            |

Terminology **231**

Language

**Table 14-2** Proper capitalization of onscreen elements (continued)

<span id="page-231-3"></span>

| Element                                                                            | Capitalization<br>style | Examples                                                                                                |
|------------------------------------------------------------------------------------|-------------------------|---------------------------------------------------------------------------------------------------------|
| Labels that are not full sentences<br>(for example, group box or list<br>headings) | Title                   | Mouse Speed<br>Total Connection Time<br>Account Type                                                    |
| Labels that are full sentences (for<br>example, radio button or<br>checkbox text)  | Sentence                | Enable polling for remote mail<br>Cache DNS information every<br>minutes.<br>Show displays in menu bar. |
| Dialog messages                                                                    | Sentence                | Are you sure you want to quit?                                                                          |

### <span id="page-231-4"></span><span id="page-231-0"></span>Using Contractions in the Interface

In cases where space is at a premium, such as in pop-up menus, contractions may be used, as long as the contracted words are not critical to the meaning of the phrase. For example, a menu could contain the following items:

Don't allow printing Don't allow modifying Don't allow copying

In each case, the contraction does not contain the operative word for the item. But in Sherlock, for example, menu items enabling users to choose between text that "contains" and "does not contain" are communicated more clearly without the use of contractions.

## <span id="page-231-1"></span>Writing Good Alert Messages

<span id="page-231-2"></span>A good alert message states clearly what caused the alert to appear and what the user can do about it. Express everything in the user's vocabulary. Here's an example of an alert message that provides little useful information:

<span id="page-232-0"></span>**Figure 14-1** A poorly written alert message

![](images/_page_232_Picture_3.jpeg)

You could improve this message by describing the problem in the user's vocabulary:

<span id="page-232-1"></span>**Figure 14-2** An improved alert message

![](images/_page_232_Picture_6.jpeg)

<span id="page-232-2"></span>To really make the alert useful, provide a suggestion about what the user can do to get out of the current situation:

<span id="page-233-0"></span>**Figure 14-3** A well-written alert message

![](images/_page_233_Picture_3.jpeg)

<span id="page-233-1"></span>For information about when to use alerts, see ["Types of Dialogs and When to Use](#page-91-0)  [Them" \(page 92\).](#page-91-0)

# <span id="page-234-3"></span><span id="page-234-0"></span>15 File Location

Mac OS X creates a suite of directories for each new user account. This structure is provided to assist users in organizing related types of files, provide a default location for task-specific applications (such as iMovie), and facilitate transferring files to and from iDisks.

<span id="page-234-2"></span>This chapter contains guidelines for where to place application-support files and user-created files. For more information about the file system layout, see Inside Mac OS X: System Overview.

## <span id="page-234-1"></span>Predefined User Domain Directories

<span id="page-234-4"></span>There are eight predefined top-level user directories. Users can move files (and folders) in and out of these directories, all of which can be located with the Find command. With the exception of subdirectories in the user's home directory (Desktop and Library), users can also move or delete these directories.

The **Library** directory contains system or application-support files, such as plug-ins, document templates, user preferences, and nonsystem fonts. Like the Library directory at the root of the Mac OS X startup disk, this directory is not intended to be browsed by users. You may choose to have your application provide a separate interface for accessing and managing the contents of this directory.

Three of the predefined directories support basic system functionality:

### File Location

- **Desktop:** Contains all files visible on the desktop when the user logs in. By default, the contents aren't visible to other accounts. This directory is the default location for files downloaded with a Web browser (the user can change the location in Internet preferences).
- <span id="page-235-10"></span><span id="page-235-6"></span><span id="page-235-3"></span>■ **Public:** Allows the user to share files with local and remote users. By default, the contents are visible to other user accounts. This directory contains a drop box, where others can put files for the owner that aren't visible to other users.
- <span id="page-235-14"></span><span id="page-235-12"></span><span id="page-235-11"></span>■ **Sites:** Allows users to host a website. When the user turns on Web Sharing (in Sharing preferences), other users can access Web pages in this folder. A sample Web page is provided in this directory.

The remaining directories are intended to provide default locations for storing files. They are not intended to contain files whose primary access is through the application. For example, AppleWorks templates and iTunes music databases should go in the Library directory. The provided directories are the following:

- <span id="page-235-2"></span>■ **Documents:** The default for storing user-created files not better served by the other directories. Examples include AppleWorks text or spreadsheet documents and TextEdit documents. Don't put application support files here; put them in the Library directory.
- <span id="page-235-8"></span>■ **Movies:** The default for storing moving images created by the user or exchanged with other users. Examples include QuickTime Player files, iMovie projects, and imported digital video sequences.
- <span id="page-235-9"></span><span id="page-235-7"></span>■ **Music:** The default for storing music, sound, or MIDI files created by the user or exchanged with other users. Applications that generate music or sound-related files should use this directory as the default storage location. Examples include iTunes user playlists and converted MP3 files.
- <span id="page-235-5"></span><span id="page-235-4"></span>■ **Pictures:** The default for storing still images created by the user or exchanged with other users. Examples include AppleWorks graphics documents and images downloaded from a digital camera.

<span id="page-235-13"></span><span id="page-235-1"></span><span id="page-235-0"></span>When a user saves a file to a destination other than the default directory, your application should keep the user's selection as the default location for saving files.

# <span id="page-236-0"></span>A Checklist for Creating Aqua Applications

<span id="page-236-2"></span>This checklist is designed to help guide you in the process of making a great Aqua application. Use it to remind yourself of important interface-related issues.

Consider the questions in the checklist as you review your software. Answering every question with a "yes" will ensure that your product conforms to the Aqua human interface guidelines. Even if you can't answer "yes" to every question, this checklist can help your product maintain the spirit of the guidelines and principles.

<span id="page-236-3"></span>Although business realities (such as product schedules) often force you to make design tradeoffs, remember that, for many users and product reviewers, the extent to which you adopt Aqua is the most visible means of measuring how "Mac-like" your product is.

## <span id="page-236-1"></span>General Considerations

- Does the application have the overall Mac OS X "look," including high-quality icons, controls, anti-aliased text, windows, and menus?
- Does the application have the Mac OS X "feel," including window minimization, live scrolling, live window dragging, and sheets?
- If a metaphor is being used, is it suitable for the application? Does the metaphor match a "real" visual and behavioral representation?
- Does the application always provide some indication that an activity is being carried out in response to a command?

### **APPENDIX A**

### Checklist for Creating Aqua Applications

- Is suitable feedback provided during task processing? Is the completion of a processing task indicated somehow? Is the duration of the task indicated?
- Is the user always able to find an object or action on the screen? In other words, does your interface follow the see-and-point principle of design?
- Are the operations consistent with the standard elements of the Mac OS X interface—that is, if a user is familiar with the Macintosh, will your application seem like familiar territory?
- Do document printouts exactly replicate what the user sees on the screen? In other words, is the application WYSIWYG (what you see is what you get)?
- Is an explanation offered if a particular action cannot be carried out? Are alternatives offered?
- Are there warnings about risky actions? Are there enough warnings without being too many? Are users allowed to back away gracefully from risky territory?
- Does the application feel stable?
- If an operation can be interrupted, do you provide a Cancel or Stop button? Can Escape or Command-period be used to cancel or stop these operations?
- Is your application forgiving and explorable by supporting Undo?
- Do you avoid assigning new behaviors to existing interface elements?
- Do you make all changes clearly visible?
- Do you interpret users' responses consistently?
- Do you respect all of the accessibility features in Mac OS X, such as keyboard navigation and focus?
- Do you rely on controls provided by the system rather than inventing your own?
- Do you call the system alert sound when you want to make an alert sound?
- If your application has modes, is there a clear visual indication of the current mode? Does the visual indication of the mode appear near the object most affected by the mode? Are there enough landmarks to remind the user what area of the application he or she is in? For example, many graphics applications change the pointer to an eraser in erase mode.
- Have you made a clear, consistent distinction between basic and advanced features?

- Is each mode absolutely necessary? Do the modes within the application properly track the user's own modes? Do users consistently avoid the kind of errors caused by the program being in a mode other than what the user wants or expects? Making a mode visually apparent is no guarantee that the user will track it: Test the application on users and find out what sorts of mistakes they are making. If the errors are caused by modes, find ways to communicate the modes more clearly, or eliminate them.
- Can the user save a document or quit an application at any time, unless he or she is in a modal dialog box?
- Are the widest possible range of user activities available at any time? The user should spend most of his or her time being able to interact with the application not waiting for it to complete a process.
- Has all user-visible text been reviewed by a professional writer?
- <span id="page-238-2"></span><span id="page-238-1"></span>■ Does all user-visible text use "curly" apostrophes and quotation marks rather than straight ones?

## <span id="page-238-0"></span>Graphic Design

- Do you have high-quality Aqua-style icons?
- Do the graphics resemble items that users are familiar with? Did you leave out insignificant detail (which unnecessarily complicates a graphic)?
- Do windows, dialogs, and palettes look "clean" and free from clutter?
- Does the user have control over the design of the workspace (location and sizing of windows, toolbar customization), allowing him or her to individualize it?
- Is the information in windows organized so the most important information can be read first?
- Do you use a consistent light source, one that always comes from the center top of the screen?
- Do you use white space and graphics to break up long pieces of text?

### <span id="page-239-1"></span>Checklist for Creating Aqua Applications

## <span id="page-239-0"></span>Menus

- Are the Apple, application, File, Edit, and Window menus present, with at least the standard items?
- Does the application support Undo, Cut, Copy, and Paste, and are these items in the Edit menu?
- Does your application menu contain About, Preferences, Hide, and Quit?
- Do the unique menus of the application have names that are appropriate? Are the names sufficiently different from the standard system menu names? Can the user understand and remember their meaning?
- Are frequently used menu items available at the top level rather than in a submenu or a dialog? If not, can the user change their location?
- Are unavailable items dimmed (rather than being omitted)? Are dimmed items unselectable? If all items in a menu are unavailable, is the menu title dimmed? Can the user still pull down the menu and see the dimmed names of the operations?
- Are toggled menu items unambiguously named?
- Are menu titles and items in caps/lowercase unless there is a compelling reason to have a different style, such as an ALL CAPS item in a Style menu?
- Do menu items have an ellipsis character (…) if more information is required from the user before completing the command?
- Are the menu items truly menu items? Menu items should not be used as text, section titles, or status indicators.
- In a hierarchical menu, does the title of the submenu have a right-pointing triangle? Are submenus used only for lists of related items?
- Can the user see all the commands, items, and submenu titles in a menu without scrolling? Scrolling should be necessary only for menus that users have added to or for menus that spill over because the user has selected a large system font.
- If the application is text oriented, can the user change the font and style with menu commands or the system Font dialog?

### <span id="page-240-2"></span>Checklist for Creating Aqua Applications

## <span id="page-240-0"></span>Pop-Up Menus

- While the menu is open, is the current value checked?
- Are pop-up menus used to allow the user to choose only one of a set of several choices? Pop-up menus should not be used for choosing more than one item from a set of several choices.
- <span id="page-240-3"></span>■ Do you avoid using menu items that contain verbs (commands) in pop-up menus?

## <span id="page-240-1"></span>Windows

- Do the standard window size and position take into account the dimensions of the screen?
- Is the standard state of a window best suited to working on the document (such as no wider than the page width), and not necessarily as large as the full screen?
- Does your application sensibly open new windows in either the standard or the user state?
- Can each resizable window be made as large as the smaller of either the maximum document size or the maximum size of the displays, including multiple monitor displays?
- Is the default position of a window contained on a single screen?
- Is each additional window opened below and to the right of its predecessor?
- If a user drags a window from one monitor to another monitor, does your application open subsequent windows on the second monitor?
- Do you use the lowercase letters "untitled," without additional punctuation, in a new window title? Do you add a number to the second and subsequent new windows, but not to the first? Do you avoid using blank titles?
- Do document titles display or hide filename extensions appropriately?

Pop-Up Menus **241**

### **APPENDIX A**

### Checklist for Creating Aqua Applications

- Do document windows with unsaved changes display a dot in the close button?
- Before closing a window, do you check to see if the user has changed its size or position? Do you save window positions, and then reopen windows in the size and position in which the user left them?
- Before reopening a window, do you make sure that the size and position are reasonable for the user's current monitor or monitors, which may not be the same as the monitor on which the document was last open?
- When zooming from the user state to the standard state, do you check if the size of the standard state would fit completely on the screen without moving the upper-left corner? If so, is the upper-left corner anchored? If not, is the window moved to an appropriate default location?
- <span id="page-241-1"></span>■ Do you appropriately display controls and selected items in inactive windows?

## <span id="page-241-0"></span>Scrolling

- Does the window use either the standard scroll bar mechanism or the hand for scrolling? If it uses the hand, does the pointer either always become a hand in the window or appear highlighted in a tool palette?
- Does clicking a scroll arrow cause the document to move a distance of one unit in the chosen direction? (The unit should be appropriate and meaningful for the application.)
- Does clicking in the gray area move the document by a windowful (or to the pointer location, if the user has selected that option)?
- Are the scroll bars inactive when the entire document fits in the window?
- Are the scrolling keys on the keyboard (Page Up, Page Down, Home, End) supported? Note that these keys do not move the insertion point and do not affect the selection.
- Does the scroller indicate the approximate position of the visible part of the document in comparison to the whole document?

### <span id="page-242-3"></span>Checklist for Creating Aqua Applications

## <span id="page-242-0"></span>Utility Windows

- Do your utility windows use the right window type (kFloatingWindowClass or NSPanel)?
- If a tool palette is present, is the selected symbol (icon, pattern, character, or drawing) highlighted?
- Do palettes provide tracking feedback when the mouse button is down? Does any change in selection in palettes occur only when the mouse button is released?
- If you use any small controls in a utility window, are all the controls in the window the small versions (that is, you haven't mixed standard size and small controls in the same window)?

## <span id="page-242-2"></span><span id="page-242-1"></span>Dialogs

- Are questions in dialogs posed in a straightforward and positive way—for example, "Do you want to erase everything on the disk named "Macintosh HD?" rather than "Do you not want to alter the contents of this disk?"
- Do you use sheets for document-specific dialogs?
- Are dialogs designed with a centered look (rather than flush left)?
- Are dialogs horizontally centered either on the screen or over the active window if the window is on a large screen or on a screen other than the one the menu bar appears on?
- Do you use modal dialogs only when necessary? If a movable modal dialog is displayed, can the application run in the background? Can the system Help menu be used when a modal dialog is displayed?
- If there is an active text input field in a modal dialog, can the Cut, Copy, Paste, and Undo menu commands in the Edit menu be used?

Utility Windows **243**

### **APPENDIX A**

### Checklist for Creating Aqua Applications

- Do keyboard equivalents of the standard Edit menu commands operate correctly in a modal dialog containing editable text items?
- Do you use the new data browser control for lists?
- Can type selection be used in scrolling lists? Can the arrow keys be used to move the selection by one item in the direction of the arrow?
- Does the active area of a dialog (the "focus") have an indicator if there is more than one possible focus? (Focus areas are those that accept keyboard input.)
- Does pressing the Tab key cycle through the available elements? Does Shift-Tab cycle in the reverse direction?
- When appropriate, are buttons named with a verb that describes the action that it performs, such as Erase, rather than OK?
- Do you provide a Cancel button wherever possible, especially in progress dialogs? Does pressing Escape or Command-period indicate Cancel? (Pressing Escape should never cause the user to lose information.)
- If an operation can be halted midstream, with possible side effects, is the button named Stop instead of Cancel?
- Do the Return and Enter keys map to the default button, which is usually the button with the safest result or the most likely response?
- Do default buttons have color and pulse?
- Are buttons wide enough to accommodate their text names?
- Are buttons placed in functional and consistent locations, both within your application and across all applications that you develop? Is the action button placed in the lower-right corner with the Cancel button to its left or above (for Western readers)?
- Are hidden filename extensions supported? Does the application display a file's display name instead of its filename, and does the Save dialog support filename extension hiding?
- Do Save dialogs place a default name in the Save As text field, and is the name (but not its filename extension) selected?
- When a dialog refers to a document or an application, do you use the name of the document or application in the message text?
- Has room been left to allow the dialog to grow during localization? Most languages require more characters than English to convey equivalent messages.

### **APPENDIX A**

### Checklist for Creating Aqua Applications

■ Are the bounding rectangles of interface elements (for example, radio buttons and checkboxes) the same size? When the alignment of dialog elements is reversed, they should align on the opposite side.

## <span id="page-244-2"></span><span id="page-244-0"></span>Alerts

- Do you use the new standard alert functions for displaying alerts?
- Do you display your application icon in all dialogs? Do you also show the caution icon in potentially data-damaging alerts?
- Does the alert have an informative title and text that not only tell the user what is wrong, but also offer suggestions as to what to do to correct it? The best alert messages answer the following questions: What happened? Why did it happen? What can I do about it?
- <span id="page-244-3"></span>■ Are all your alerts necessary? You can prevent many user errors with good or preventative interface design. For example, if the application cannot handle an 80-character filename, don't display an 80-character field in which to enter it.

## <span id="page-244-1"></span>The Mouse

- If the user initiates an action by pressing the mouse button, does the action take place only when the button is released (except for drags)?
- Are there ways other than double-clicking to perform a given action? Double-clicking should never be the only way to do something; it should be a shortcut only.

Alerts **245**

<span id="page-245-2"></span>Checklist for Creating Aqua Applications

## <span id="page-245-0"></span>Keyboard Equivalents

- Are Apple-reserved keyboard equivalents used properly? Even if your application doesn't support one of these menu commands, it shouldn't use these keyboard equivalents for another function.
- Do you avoid using Command–Space bar and Command–modifier key–Space bar in your application, since they are reserved for use by international systems?
- Do keyboard equivalents appear where appropriate? Are the keyboard equivalents case-independent? (This second rule does not apply if the product uses both cases in the keyboard equivalents and enables the user to predict which case to use.)

## <span id="page-245-3"></span><span id="page-245-1"></span>Text

- Can arrow keys be used in all text boxes (including in dialogs)? Can the Shift key be used with the arrow keys to extend the selection (including in dialogs)?
- If text is selected, does pressing an arrow key cause the insertion point to go to the corresponding end of the range and deselect it?
- Are discontinuous selections made with the Command key modifier (for lists and arrays)? The Shift key is used for graphics selections and continuous text extensions.
- Do you use Command–arrow key and Option–arrow key for moving the insertion point in larger semantic units? (Note that when multiple script systems are available, Command–Left Arrow and Command–Right Arrow are intercepted by the system and used for changing the keyboard layout.)
- Does the active font size in a menu have a checkmark next to it?
- Do you avoid making assumptions about font sizes? For example, the system font may have a different size in other countries.

### **APPENDIX A**

### Checklist for Creating Aqua Applications

## <span id="page-246-3"></span><span id="page-246-0"></span>Icons

- Do your icons represent objects that users are familiar with and that are universally recognizable?
- Do you use a common theme for icons associated with your application?
- Do you avoid using replicas of Apple hardware (which change often) in your icons?
- Do your icons fit in with the Aqua style—that is, high-quality, realistic, emotive?
- Are icon shadows realistic? Do you use a single center-top light source?
- <span id="page-246-2"></span>■ Do all your icons use the appropriate perspective for their types?

## <span id="page-246-1"></span>User Documentation

- Is the instructional suite written for the right audience?
- Do you provide onscreen HTML help and a Help command in the Help menu?
- Does your documentation focus on real-world user tasks and troubleshooting?
- When appropriate, do your dialogs have help buttons that open relevant help text?
- Does your help automate common tasks using AppleScript?
- If any part of the documentation refers the user to another document, is the reference more appropriate than including the information right there?

Icons **247**

<span id="page-247-1"></span>Checklist for Creating Aqua Applications

## <span id="page-247-0"></span>Help Tags

- Do you provide help tags to help users identify interface elements?
- Are your help tags very brief? Do they describe what the user will accomplish by using the object?
- Do expanded help tags for a file display the filename extension, even if the user has chosen to hide it on that file?

<span id="page-248-1"></span><span id="page-248-0"></span>This appendix describes usage guidelines for terms found in Mac OS X. For ease of use, it contains some terms from the *Apple Publications Style Guide*. For any item that contradicts an *APSG* entry, use the guideline provided here.

For terms not included here, or for more information, see the *APSG* [\(http://](http://developer.apple.com/techpubs/faq.html) [developer.apple.com/techpubs/faq.html](http://developer.apple.com/techpubs/faq.html)) and the *American Heritage Dictionary*.

Apple has standard translations for some of these terms in other languages. Check <http://developer.apple.com/intl/localization.html>.

Apple reserves the right to change terms and guidelines at any time.

**abbreviations and acronyms:** Spell out the following on first use (on a page or in a document):

ISP (Internet service provider) FTP (File Transfer Protocol)

You don't have to spell out *CD-ROM, HTML,* or *MIME*.

**abort:** Don't use; use **cancel**.

**Address Book:** Two words. An application, separate from Mail.

**administrator:** Use to refer to people who can do such tasks as create users and groups, assign privileges to files and folders, and so on. Don't use **Owner**. You can say, for example, "You need to log in with an administrator password" or "Only administrator users can make changes." Don't shorten to "admin user."

**analog-to-digital (adj.):** Note hyphens.

**Apple key:** Don't use; the key with the cloverleaf and the Apple logo is "the Command key."

**application:** It is not necessary to say "application program" on first use. (This entry is different from the current APSG.) "Application" is OK to use alone.

**application menu:** The menu to the right of the Apple menu. Refer to it as "the [application name] application menu" ("the Mail application menu," "the Grab application menu").

**application names:** Unless the official product name contains an internal cap, twoword application names should contain spaces, even if the filename in the file system appears without a space. Examples of correctly spelled names:

Address Book

Disk Utility

Help Viewer

Image Capture

Key Caps

Keychain Access

NetInfo Manager

Network Utility

Print Center

Process Viewer

Script Editor

Setup Assistant

System Preferences

TextEdit

WorldText

In general, don't use "the" with application names.

*Correct:* Open QuickTime Player.

*Incorrect:* Open the QuickTime Player.

*Correct:* Open Print Center.

*Correct:* Open the Print Center application.

*Incorrect:* Open the Print Center.

**the Applications folder:** There is only one, which is displayed when you click the Applications button in a Finder window.

**Aqua:** Uppercase (an Apple trademark). Use mainly as an adjective ("the Aqua user interface").

#### **APPENDIX B**

Mac OS X Terminology Guidelines

**attach:** Don't use to mean **connect** (as in "Connect your USB device to your computer").

**boot:** Don't use for *start up* (except in technical documentation).

**box:** Don't use "dialog box" anymore; OK to say "dialog."

**bus-powered, self-powered:** Try to avoid when indicating whether devices draw power from a power cord or from another USB device. When possible, describe the device, don't give it a label: "A device that plugs into an electrical outlet" (instead of "a self-powered device"); "a device that gets its power from another USB device" (instead of "a bus-powered device").

**button states:** In a dialog, the default button has color and pulses, but avoid references that say "blue"; call it "the default button." Window buttons "have color" or "don't have color"; don't refer to buttons as "clear."

**canceled/canceling:** Note our style is one "l."

**Carbon application:** Refers to an application written and compiled using the Carbon API specification interfaces (Universal Interfaces 3.3.2 or later). Don't say "Carbonized"; instead say something like "update your application for Carbon." The term "Carbon" should be used only in developer documentation.

A Carbon application executes as a native process in Mac OS X if it is compiled as either a Mach-O or CFM/PEF binary, and can be a single file binary or application package. A Carbon application executes in Mac OS 8.1 to Mac OS 9.x with CarbonLib installed if it is compiled as a CFM-executable binary, as either a singlefile binary or an application package.

**CD-ROM disc:** Don't shorten to "a CD-ROM." It's either "a CD-ROM disc" or "a CD."

**chain:** OK to use when you mean a series of USB devices connected together. See **hierarchy**.

### **Classic:**

1. A Classic application is one originally created for Mac OS 9 (or earlier) that has not been rewritten for Carbon. More specifically, a Classic application is one written and compiled to the Mac OS Universal Interfaces prior to versions including the Carbon API specification interfaces (version 3.3.1 or earlier). Classic applications are single-file binaries containing both executable code and Resource Manager code components in the Preferred Executable Format (PEF) used by the Code Fragment Manager. In Mac OS X, Classic applications execute in the **Classic environment**.

2. A pane in System Preferences for automatically starting up the Classic environment.

**Classic application/Classic environment:** Don't refer to "the Classic application" (Classic.app); instead say, for example, "When you open a Classic application, the Classic environment starts up."

**Classic Mac OS:** Avoid; instead say "Mac OS 9 and earlier" or whatever is applicable. ("Classic" describes applications, not the operating system.)

**Clipboard:** The correct term in user documentation; don't use "pasteboard" or "scrap" in user documentation. In developer documentation, it's OK to use "pasteboard" when discussing the NSPasteboard class, but point out that users view the contents of the pasteboard in the Clipboard.

**close button:** The leftmost (red) button of the three window controls at the left of the title bar.

**Cocoa application:** Refers to an application written and compiled using the Cocoa API frameworks. The term "Cocoa" should be used only in developer documentation.

Cocoa applications written in Objective-C and C are compiled into Mach-O binaries and application packages, and execute as native processes in Mac OS X. They cannot execute in Mac OS 9.x or earlier. Cocoa applications written in Java execute only in the Mac OS X Java VM environment.

**column-view button:** The rightmost button in the view control.

**connect:** Use to refer to the general act of hooking devices together. (Don't use "attach.") You can connect USB devices to a computer; you can connect computers to an Ethernet network. Use "plug in" to refer to the specific action of plugging a connector into a port.

*Correct:* Connect the USB device to a power source.

*Correct:* Plug the square end of the USB cable into the USB device.

**Console:** An application that lets you see technical messages from Mac OS X and Mac OS X applications. Don't say "the Console"; "the Console application" is OK.

**Darwin:** An operating system that includes some, but not all, of the components of Mac OS X. Darwin comprises the kernel plus the BSD libraries and commands essential to the BSD Commands application environment. The term "Darwin" doesn't appear in the Mac OS X interface.

**Date & Time:** A pane in System Preferences.

#### **APPENDIX B**

Mac OS X Terminology Guidelines

**dialog:** Use instead of "dialog box."

**directory:** In user documentation, don't use directory when you can say folder.

**disable:** Avoid in user documentation; say *dimmed* or *turned off* (or simply *off*).

**disclosure button:** The triangle that reveals more options when clicked (not "the detail button"). You can also call it "the disclosure triangle."

**Disk First Aid:** Has been replaced by Disk Utility. (But Disk First Aid may be included on the Mac OS X CD, in the Mac OS 9 section.)

**Disk Utility:** Two words.

**Dock:** Don't use as a verb. Items are "in the Dock," not "on the Dock."

*Correct:* Click an icon in the Dock.

*Correct:* Click the Mail application icon in the Dock.

*Correct:* Click a minimized window in the Dock.

*Correct:* To put a window in the Dock, click the minimize button.

*Correct:* When an item is in the Dock… *Incorrect:* You can dock any window. *Incorrect:* When an item is docked ….

**drawer:** A window that slides out from a parent window when you click a button or choose a command, such as the Mailbox button in Mail ("the Mailboxes drawer").

**enable:** Avoid in user documentation; say available or turned on (or simply on) or selected.

**Favorites button:** In the Finder toolbar.

**favorites toolbar:** Use to refer to the user-customizable area at the top of the System Preferences window.

**filename:** One word. **file server:** Two words. **file sharing:** Two words. **file system:** Two words.

**FireWire:** Apple's version of high-speed serial data link technology. IEEE 1394 is a synonym. Don't use i.LINK.

**folders:** When referring to folders on a computer used by more than one person, you need to distinguish only the folders that are not accessible to all users. For example, the top-level (global) applications folder is "the Applications folder." An individual user's applications folder is "your Applications folder" or "a person's Applications folder."

**Grab:** A screen-capture application that comes with Mac OS X.

**Help Viewer:** Two words.

**help tags:** Lowercase. Use instead of "Tool Tips" to refer to the instructional text that appears when the pointer hovers over an interface element in Mac OS X.

**hierarchy:** Avoid this term when you mean a series of USB devices connected to one another (and to a computer) in a branching structure using hubs. Simply describe, if possible: "You can connect many USB devices to one computer using a series of hubs," or similar language.

**home folder:** Always lowercase ("Each user gets his or her own home folder"); there is nothing actually called "the Home folder" (it's named with the user's name).

**HomePage:** When you're referring to the iTool available at mac.com, it's one word with an internal cap.

**hot-pluggable:** Try to avoid in user documentation.

**hub:** FireWire hub or USB hub. See also **bus-powered, self-powered.**

**icon-view button:** The leftmost button in the view control.

**IEEE 1394:** Synonym for **FireWire**.

**i.LINK:** Don't use. Use **FireWire.** i.LINK is Sony's version.

**Image Capture:** Two words.

**Internet service provider (ISP):** Spell out the first time this term appears on a help page or in a document. After that, it's OK to use the abbreviation.

**Keychain Access:** The application name is two words. You use the application to create keychains (lowercase).

**Language:** One of the tabs in the International pane of System Preferences.

**log in (v.):** You log in to a computer or server (not log on). You log out, not off.

#### **APPENDIX B**

Mac OS X Terminology Guidelines

**login items:** Items that open when you log in. In user documentation, it's preferable to use descriptive language (for example, "items that start up automatically") instead of this term.

**Login Items:** One of the tabs in the Login pane of System Preferences.

**login screen:** The dialog that appears when a new user logs in to Mac OS X.

**Mac:** Avoid when referring generally to a Macintosh computer (it could be confused with more specific names such as "Power Mac" or "iMac"). Use "computer." You can, however, use "Mac" judiciously as an adjective ("the Mac desktop").

**Mac Help:** The onscreen help for the Mac OS and hardware. The help system itself is Apple Help, but you shouldn't have to use that term in user documentation.

**Mac OS Extended, Mac OS Standard:** Disk formats.

**Mac OS 9:** Always use the full name; don't shorten to "OS 9" or "9." Note spacing between each "word." Don't say "Mac OS 8/9"; instead say "Mac OS 8 and 9."

**Mac OS X:** Always say "Mac OS X"; don't shorten to "OS X" or "X." Note spacing.

**Mail:** An application that comes with Mac OS X. Address Book is a separate application.

**mailbox:** One word. In Mail, a mailbox is essentially a folder, which can contain messages (received email) and other mailboxes.

**Mailbox:** The button you click in the Mail application to see the Mailboxes drawer (which slides out on the left or right).

**mailboxes drawer:** In the Mail application, when you click the Mailbox button, the mailboxes drawer slides out. It displays your mailboxes.

**mass storage (adj.):** No hyphen (as in "mass storage device").

**maximize:** Don't use. Instead, say something like, "To make an item in the Dock active, click it."

**menu bar:** Two words.

**MIME format:** An email format (as opposed to plain text format). You don't have to spell it out.

**minimize button:** The middle (yellow) button of the three window controls at the left of the title bar. You click this button to put a window in the Dock.

**minimized:** OK to use to describe a window in the Dock: "Windows in the Dock are minimized."

**Mouse:** A pane in System Preferences.

**Multiple Users:** Two words, capped. An application that comes with Mac OS X.

**name server:** Two words.

**Network:** A pane in System Preferences and an icon you see when you click the Computer button in a Finder window.

**network time server:** Not capped, but "Network Time" (the tab in the Date & Time pane of System Preferences) is. So is Network Time Synchronization.

**non-USB devices:** Use to refer to devices that don't use USB.

**Owner:** Don't use. See **administrator**.

**pane:** Use to refer to different views within a window (views that can be changed with a tab, a pop-up menu, a button, or by selecting an item, or views that change automatically, as in Installer). In most cases in user documentation, you can avoid using "pane" by describing how to get to a particular place: "Click System Preferences, click Network, click AppleTalk. . . ."

Examples of how to use "pane":

Type your name in the Login Window pane of Login preferences.

Choose an item from the Configure pop-up menu in the TCP/IP pane of Network preferences.

You can set a document's access privileges in the Privileges pane of the file's Info window.

When you click Network in System Preferences, the TCP/IP pane appears. To display the AppleTalk pane, click the AppleTalk tab.

Click the Workgroups tab, then click the Options tab and select "Check for email when members log in."

You choose a workgroup storage volume and set options for the volume in the Volumes pane of the Workgroups pane.

Make sure "Play audio CDs" is selected in the "Group members may" section of the Privileges pane of the Workgroups pane.

You can specify an RGB default in the Document Profiles pane of ColorSync preferences.

Note that each of the system preferences panes can be shortened to, for example, "Network preferences." See also **preferences.**

**panel:** Don't use; see **pane** and **dialog.**

**pasteboard:** Don't use in user documentation. OK to use in developer documentation that discusses the NSPasteboard class, but point out that users view the contents of the pasteboard in the Clipboard.

**pathname:** Most user documentation does not need to refer to specific pathnames ("TextEdit is in the Applications folder on your hard disk"). But when necessary if a user has to type a pathname in a dialog, for example—you can refer to it as "the path" or "the pathname."

**plug in (v.):** Use only when referring to the specific act of plugging a connector into a port or outlet. For example, a power cord plugs into an electrical outlet; you can plug a USB connector into a USB port. See **connect.**

**preferences:** Mac OS X has two types of preferences:

- System Preferences: The general preferences application (it has an icon in the default Dock).
- application preferences: Use the application name, capped ("Mail Preferences").

It's OK to call the things you set in preferences "settings" ("You can change settings with System Preferences").

*Correct:* Click System Preferences (in the Dock) and click Sound.

*Correct:* Use the Sound pane of System Preferences to choose an alert sound.

*Correct:* Open System Preferences, click Network, and click the AppleTalk tab.

*Correct:* In Mail Preferences, click Accounts.

You can shorten the name of each of the system preferences "modules" to "<Name> preferences," as in "Startup Disk preferences."

**Preview:** An application that comes with Mac OS X.

**Print Center:** Two words, capped. Because it's an application, it's correct to say "Open Print Center" (not "the Print Center").

**resize control:** The area in the lower-right corner of a window that you drag to resize the window.

**screen shot:** Two words. Don't use "screen dump."

**scroll bar:** The whole control is "the scroll bar"; the former "scroll box" is the "scroller." Note that "scroll bar" is two words.

**scroll box:** Call what used to be called the "scroll box" the *scroller* (in Aqua it's no longer a box).

**Setup Assistant:** The application you use to set up your computer. Don't call it "the Mac OS Setup Assistant."

**sheet:** Refers to a modal dialog attached to a specific document window (when you choose Print, the Print sheet appears). In user documentation, call them "dialogs" ("sheet" is mainly for marketing and developer purposes).

**Sherlock:** You don't have to say "Sherlock 2."

**slider:** The widget you drag to set a value on a continuum (a range of values). The whole control is called "the slider control."

**Startup Disk:** A pane in System Preferences (not "System Disk"). If you need to distinguish between the Mac OS 9 version and the Mac OS X version, you can refer to them as "the Startup Disk pane of Mac OS X System Preferences" and "the Classic Startup Disk control panel" or "the Startup Disk control panel included with Mac OS 9."

**system:** Usually "computer" is preferable to "system," as in "The computer requires a folder named 'Applications' in this location."

**System Preferences:** The user-modifiable set of preferences at the top is the "favorites toolbar." When you click a preferences button, the "[button name] pane" appears (for example, "the Network pane"). See also **preferences**.

**tab:** In a dialog, the tab itself is called the "<tabname> tab," but the content you see when you click a tab is the "pane." Don't say "under the <tabname> tab." Examples:

You can specify your home page in the Web pane of Internet preferences.

To set up automatic login, click Login, then click the Login Window tab.

You disconnect from the network time server in the Network Time pane of Date & Time preferences.

**Terminal:** An application for using the command-line interface. Don't say "the Terminal"; "the Terminal application" is OK.

**TextEdit:** One word with an internal cap. A word-processing application that comes with Mac OS X.

**toolbar:** An area containing buttons, such as in Finder windows and the Mail application. Don't call them "shortcuts."

**Tool Tips:** Don't use. Use **help tags**.

**Type A connector:** A type of USB connector. Use once and describe what it looks like ("rectangular").

#### **APPENDIX B**

Mac OS X Terminology Guidelines

**Type B connector:** A type of USB connector. Use once and describe what it looks like ("square").

**UNIX:** Don't use when referring to the Mac OS X architecture. The correct term to use instead depends on the context. Darwin ("With the Terminal application, you can enter Darwin system commands") and "BSD utilities" are possible alternatives.

**UNIX File System (UFS):** One of the file formats available in Disk Utility.

**USB:** Abbreviation for "Universal Serial Bus." Provide spelled-out term only once; otherwise, use simply "USB."

**USB adapter:** Use to refer to a device that lets you connect non-USB devices to USB ports.

**user name:** Two words.

**view control:** The three-button unit you use to change your view of Finder windows. The view control comprises the icon-view button, the list-view button, and the column-view button.

**window controls:** Standard controls for windows include the close button, the minimize button, the zoom button, and the resize control.

**workspace:** Don't use as a synonym for desktop or Finder.

<span id="page-258-0"></span>**zoom button:** The rightmost (green) button of the three window controls at the left of the title bar. Clicking this button toggles between the standard window size and the user-resized size.

#### **APPENDIX B**

Mac OS X Terminology Guidelines

# <span id="page-260-0"></span>C Document Revision History

This document has had the revisions described in Table C-1 (page 261).

<span id="page-260-1"></span>**Table C-1** Document revision history

| Date        | Notes                                                                                                                                                                                                                                                                                                                     |
|-------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1 Oct. 2001 | Updated for Mac OS X 10.1.                                                                                                                                                                                                                                                                                                |
|             | Added information about filename extension hiding, Dock menus<br>and notification, setup assistants, new focus ring specifications,<br>accessibility guidelines, full keyboard access, customizing Print<br>dialogs, window positioning on multiple monitors, proxy icons.<br>Various other editorial changes throughout. |
| 21 May 2001 | Updated for WWDC.                                                                                                                                                                                                                                                                                                         |
|             | Changes made to many illustrations.                                                                                                                                                                                                                                                                                       |
|             | Slight engineering comments and changes throughout.                                                                                                                                                                                                                                                                       |
|             | Icons chapter expanded.                                                                                                                                                                                                                                                                                                   |
|             | File Location chapter added.                                                                                                                                                                                                                                                                                              |
|             | "What's New in Aqua" chapter appended to Intro chapter.                                                                                                                                                                                                                                                                   |
|             | "Layout Guidelines" broken out from "Controls" chapter.                                                                                                                                                                                                                                                                   |
|             | Other additions include "Additional Considerations" section in<br>principles chapter; windows with different panes.                                                                                                                                                                                                       |
| 11 Dec 2000 | Updated for Jan 2001 Macworld; now called Inside Mac OS X: Aqua<br>Human Interface Guidelines.                                                                                                                                                                                                                            |
|             | Document divided into chapters. TOC added.                                                                                                                                                                                                                                                                                |

### **APPENDIX C**

### Document Revision History

**Table C-1** Document revision history (continued)

| Date        | Notes                                                                                                                                                                                                       |
|-------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|             | Major content added to entire document. Added many screen<br>shots.                                                                                                                                         |
|             | Added Human Interface principles chapter.                                                                                                                                                                   |
|             | Added Help chapter.                                                                                                                                                                                         |
|             | Added Language chapter.                                                                                                                                                                                     |
|             | Added Drag and Drop chapter.                                                                                                                                                                                |
|             | Added Checklist appendix.                                                                                                                                                                                   |
|             | Added Mac OS X terminology appendix.                                                                                                                                                                        |
|             | Added index.                                                                                                                                                                                                |
|             | Content revisions include click-through, icon creation process,<br>combo boxes, sheets, Save-Close-Quit behavior, keyboard equiva<br>lents, About boxes, pop-up bevel buttons, and pop-up icon but<br>tons. |
| 8 Sep 2000  | Updated for Mac OS X Public Beta Release.                                                                                                                                                                   |
|             | Added section on working with the Appearance Manager.                                                                                                                                                       |
|             | Added section on designing alerts.                                                                                                                                                                          |
|             | Added section on sheets.                                                                                                                                                                                    |
|             | Added section on drawers.                                                                                                                                                                                   |
|             | Added section on list and column view.                                                                                                                                                                      |
|             | Added material on small controls.                                                                                                                                                                           |
|             | Added examples of font usage.                                                                                                                                                                               |
|             | Clarified description of tab control usage.                                                                                                                                                                 |
| 19 Apr 2000 | Updated for Mac OS X Developer Preview 4 and retitled Adopting<br>the Aqua Interface.                                                                                                                       |
|             | Changed content and art to reflect new control metrics.                                                                                                                                                     |
|             | Added section on icon design.                                                                                                                                                                               |

### **APPENDIX C**

### Document Revision History

**Table C-1** Document revision history (continued)

| Date        | Notes                                         |
|-------------|-----------------------------------------------|
|             | Added section on window layering.             |
|             | Added section on menu layout.                 |
|             | Added material on using ellipses in menus.    |
| 20 Jan 2000 | Document published as Aqua Layout Guidelines. |

### **APPENDIX C**

Document Revision History

# <span id="page-264-0"></span>16 Glossary

**About window** A modeless window that displays an application's version and copyright information.

**accumulating attribute group** A set of attribute choices in which the user can select multiple items, such as Bold and Italic. See also **mutually exclusive attribute group.**

**active end** The location at which the user releases the mouse button when selecting a range of objects.

**active window** The frontmost window, which accepts user input.

**addition model** A model for extending a continuous selection using Shift-click, in which new text is added to a selection. See also **fixed-point model.**

**alert** A dialog that appears when the system or an application needs to communicate information to the user. Alerts provide messages about error conditions and warn users about potentially hazardous situations or actions.

**anchor point** The location at which the user presses the mouse button when selecting a range of objects.

**Apple Help** The component that enables applications to display HTML files in Help Viewer, a simple browser.

**Apple menu** A menu that provides items that are available to users at all times, regardless of which application is active. It is the leftmost menu in the menu bar.

**application font** The font used as the default for user-created content. It is 13-point Lucida Grande Regular.

**application menu** A menu that contains items that apply to the application as a whole, rather than to a specific document or other window. The application menu is immediately to the right of the Apple menu.

**application-modal dialog** A dialog that prevents the user from doing anything else within the owner application. See also **document-modal dialog; sheet.**

**arrow keys** The four keys on Apple keyboards (up, down, left, right) used to move the insertion point or change the selection. They can also be used with the Shift key to extend or shrink a selection.

**auto-repeat** The feature that enables users to produce numerous instances of the same character by holding down its key rather than pressing it over and over. Users can make adjustments to this feature in Keyboard preferences.

**background selection** A selection in an inactive window. In Aqua, such selections are in the secondary highlight color.

**bevel button** A button with a beveled edge that gives the button a three-dimensional appearance.

**bullet** In a Window menu, a bullet indicates that the document has unsaved changes.

**button** See **bevel button; icon button; push button; radio button.**

**character key** A keyboard key that sends a character to the computer. Character keys include letters, numbers, punctuation, the Space bar, and nonprinting characters such as Tab and Return.

**checkbox** A control for an option that must be either on or off.

![](images/_page_265_Figure_6.jpeg)

**checkmark** In the **Window menu,** a checkmark appears next to the active document's name. In other menus, checkmarks can be used to indicate that the setting applies to the entire selection. Checkmarks can be used for **mutually exclusive attribute groups** or **accumulating attribute groups**.

**Clipboard** A storage location for data the user cuts or copies from a document. The Clipboard is available to all applications and its contents don't change when the user switches between applications.

**clipping** Data dragged from an application to the Finder desktop.

**close button** A window control (the red one in the upper left) that users can click to close the window.

**combination box** A text entry field combined with a pop-up menu or a drop-down scrolling list. Combo boxes are useful for displaying a list of likely choices while still allowing the user to type in an item not in the list.

| Names: | Dave | ŧ |
|--------|------|---|
|--------|------|---|

**contextual menu** A menu that appears when the user presses the Control key and clicks an interface item. A contextual menu provides convenient access to often-used commands associated with the item.

**continuous selection** A selection that includes everything between the anchor point and the active end.

**control** A graphic object that causes instant actions or visible results when the user manipulates the object with the mouse. Standard controls include **buttons, scroll bars, checkboxes, sliders, and pop-up menus.**

**dash** In a menu, a dash indicates that an attribute applies to only part of the selection. For example, if a highlighted selection contains text with different styles applied to it, a dash appears next to each style name in the menu.

**data browser** A control that provides a standardized look for column browsers (such as seen in the column view of a Finder

window or in an Open dialog) and scrolling lists (such as seen in the list view of a Finder window).

**default keyboard access mode** The mode in which tabbing and other keystrokes move keyboard focus only between fields that receive keyboard input, such as text entry fields and scrolling lists. See also **full keyboard access mode.**

**destination region** The part of a document that can accept data dragged to it. In a document window, the destination region is usually the content area minus the title bar and areas used for controls such as scroll bars and rulers.

**dialog** A window designed to elicit a response from the user. See also **alert.**

**diamond** In a Window menu, a diamond means that the document has been minimized into the Dock.

**disclosure triangle** A control that allows the display, or disclosure, of information that elaborates on the primary information in a window. Disclosure triangles are used in the Finder's list view; clicking a triangle displays a folder's contents.

**discontinuous selection** A selection in which unselected objects are between selected objects.

**display name** The name of a file as it appears to the user. The display name reflects the user's preference for hiding or showing the filename extension.

**document-modal dialog** A dialog that prevents the user from doing anything else in the document until dismissing the dialog. All sheets are document modal and all Aqua document-modal dialogs should be sheets. See also **application-modal dialog; sheet.**

**document window** A window containing file-based data that users create and store. See also **utility window.**

**drag and drop** The technique of dragging an item, such as a graphic or selected text, and dropping it on a suitable destination, such as another document.

**drawer** A child window that slides out from a parent window, and which the user can open or close (show or hide) while the parent window is open. Drawers contain controls that are fairly frequently accessed but don't need to be visible at all times.

**dynamic menu item** A menu command that changes when the user presses a modifier key. For example, in the File menu (in the Finder), if the user presses the Option key, the Close Window command changes to Close All. See also **toggled menu item.**

**Edit menu** A menu that provides commands for changing, or editing, the contents of documents. It contains commands such as Cut, Copy, and Paste.

**emphasized system font** The bold version of the system font. It is used for the application name in an About window and the message text in an alert.

**File menu** A menu that contains commands that provide housekeeping tasks, such as Save As, for files.

**fixed-point model** A model for extending a continuous selection using Shift-click, in which the user can extend the selection on either side of the insertion point. See also **addition model.**

**focus ring** Highlighting around the onscreen area that is ready to accept user input.

![](images/_page_267_Picture_4.jpeg)

**full keyboard access mode** The mode in which tabbing and other keystrokes move keyboard focus to more interface elements than is possible in **default keyboard access mode.**

**function key** One of the keys F1 through F15 on Apple desktop computer keyboards, plus the Help, Home, Page Up, Page Down, Del, and End keys.

**group box** In a dialog, a visual indication that certain controls belong together. In Aqua, this indication is typically accomplished with blank space rather than lines.

**help book** The collection of HTML files that provide onscreen help for a particular product.

**Help Center** A window where users can access any help book installed on their system.

**Help Viewer** The simple browser used to display Apple Help HTML files.

**help tag** A brief text explanation that appears when the user leaves the pointer hovering over an interface element for a few seconds.

![](images/_page_267_Picture_12.jpeg)

**hierarchical menu** A menu that includes a menu item from which a **submenu** descends. Submenus offer additional menu item choices without taking up more space in the menu bar. Hierarchical menus are indicated with a triangle indicator.

![](images/_page_267_Picture_14.jpeg)

**hot spot** The portion of the pointer that must be positioned over a screen object for mouse clicks to have an effect on the object.

**hot zone** The area of an onscreen object that the pointer's hot spot must be within for mouse clicks to have an effect.

**icon button** A button that does not have a rectangular edge around it; the clickable region is the graphic (for example, the toolbar buttons in Finder windows).

**image well** A rectangular, recessed area that displays an icon or picture and that serves as a drag-and-drop target.

**insertion point** The point at which data will be inserted in response to a user's typing or pasting.

**Interface Builder** An application that helps you easily create application menus, windows, dialogs, palettes, and other standard Aqua interface elements.

**label font** The font used for labels with controls such as sliders and icon bevel buttons. It is 10-point Lucida Grande Regular.

**minimize button** A window control (the middle yellow one at the top left) that the user clicks to put a window into the Dock.

**modeless dialog** A dialog that does not require the user to dismiss it before interacting with anything else onscreen. The "find and replace" feature in many word processors is an example of a modeless dialog.

**modifier key** A key the user can hold down to alter the meaning of another key being pressed simultaneously or to alter the meaning of a mouse action. The Option and Command () keys are examples of modifier keys.

**mutually exclusive attribute group** A set of attribute choices in which the user can select only one item, such as font size. See also **accumulating attribute group.**

**pane** An area of changeable content in a dialog or other window. Panes usually change as the result of the user clicking a tab or a button, or choosing an item from a pop-up menu. In some cases, panes change as a process takes place, such as while the Installer application is running.

**placard** A control that displays information. Typically placards are used in document windows as a way to quickly modify the view of the contents—for example, to change the current page or the magnification.

![](images/_page_268_Picture_11.jpeg)

**pointer** The onscreen representation of the mouse's location. The pointer commonly looks like an arrow, but can also assume such shapes as a pencil, a cross, or a paintbrush, depending on the application and the user's selection.

**pop-down menu** A menu that contains commands and appears in a window rather than in the menu bar. Use of this control is limited to cases where the window is shared among multiple applications and the menu contains commands that affect the window's contents. A closed pop-down menu always displays the same text, which is the menu title. Pop-down menus have a single, downward-pointing triangle.

**pop-up menu** A menu that, when closed, displays the current choice and can be opened to present a list of mutually exclusive choices in a dialog or window. Pop-up menus have a double triangle indicator.

![](images/_page_269_Picture_2.jpeg)

**progress indicator** A control that lets the user know that a task is in progress.

![](images/_page_269_Picture_4.jpeg)

**proxy icon** An icon in a document title bar that users can manipulate as if they were manipulating the corresponding file-system object. Users can Command-click the proxy icon to display a pop-up menu illustrating the document path.

**push button** A rounded rectangle with a text label on it, which the user clicks to perform an instantaneous action, such as saving a document, completing operations defined by a dialog, or acknowledging an error message.

![](images/_page_269_Picture_7.jpeg)

**radio button** A control for one of a set of mutually exclusive, but related, choices.

![](images/_page_269_Picture_9.jpeg)

**relevance control** A control that indicates the relative ranking of search results—the longer the bar, the more relevant the item is to the search criteria.

![](images/_page_269_Picture_11.jpeg)

**scroll bar** A control for viewing areas of a document or a list that is larger than can fit in the current window. Only the active window can be scrolled. A window can have a horizontal scroll bar, a vertical scroll bar, both, or neither.

**scroller** The part of a **scroll bar** that the user drags to view other parts of a document. The scroller size reflects how much of the document is visible; the smaller the scroller, the less of the content the user can see at that time. The scroller represents the relative location, in the whole document, of the portion that can be seen in the window.

**scrolling list** A list in a dialog that uses **scroll bars** to reveal its contents.

**scrolling menu** A menu that contains more items than are visible onscreen. Scrolling menus have triangle symbols that indicate the presence of hidden menu items.

**setup assistant** A small application that guides users through the setup options for a hardware device or software component.

**sheet** A dialog attached to a specific window, ensuring that the user never loses track of which window the dialog belongs to. A Print dialog is an example of a sheet. See also **document-modal dialog.**

**Shift-click** To click while the Shift key is down. This combination is used to select multiple objects or to extend a selection.

**slider control** A control enabling users to choose among a continuous range of allowable values. Slider controls can be horizontal or vertical and can display incremental tick marks.

**small system font** The font used for informative text in alerts, headers in lists, help tags, and text in the small versions of many controls. It is 11-point Lucida Grande Regular.

**standard state** A new window's initial size and position (determined by the application). See also **user state; zoom button.**

**static text field** Text in a dialog that users can't modify.

**submenu** A menu that descends from another menu. The title of the submenu is a menu item in the parent menu. See also **hierarchical menu.**

**system font** The font used for text in menus and in modeless dialogs, and for titles of document windows. It is 13-point Lucida Grande Regular.

**tab control** A control that looks like a file folder tab and that provides a convenient way to present dialog information in a multipage format.

![](images/_page_270_Picture_9.jpeg)

**text input field** A rectangular area in which the user enters text or modifies existing text. Also called an editable text field, it supports keyboard focus and password entry.

**toggled menu item** A menu item or a set of two menu items that change between two states (for example, Turn Grid On and Turn Grid Off).

**type-ahead** Queuing of keystrokes for processing later. It occurs when the user types faster than the computer can handle or when the computer is unable to process the keystrokes.

**user state** A window's user-defined size and position. See also **standard state; zoom button.**

**utility window** A window that floats above other windows and provides tools or controls that users can work with while documents are open. See also **document window.**

**View menu** A menu that provides commands that affect what users see in a window. In the Finder, for example, the View menu contains commands for displaying windows as columns, icons, or lists.

**Window menu** A menu that contains commands for managing document windows. The menu lists an application's open document windows, including minimized windows, in the order in which they were opened.

**word wrap** The automatic continuation of text from the end of one line to the beginning of the next without breaking in the middle of a word.

**zoom button** A control that toggles a window between its **standard state** and its **user state.**

## <span id="page-272-0"></span>Index

| A                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | application-wide commands (application menu)                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| About command (application menu) 55<br>About windows 88–89<br>accessibility, as design principle 36–38<br>actions in menus 46<br>active windows<br>appearance of controls 78<br>background selections in 212<br>dragging to 212, 216<br>Add to Favorites button 101, 104<br>alert dialogs 91, 95, 245<br>alert message text, writing 232<br>anti-aliased text 190<br>Appearance Manager<br>and disclosure triangles 141<br>simulating controls for combination boxes with<br>124<br>using, for Aqua compliance 22<br>Apple Developer Connection 21 | 55<br>Apply button 116<br>applying guidelines 20<br>Arrange in Front command (Window menu) 61<br>arrow keys 162–166<br>appropriate uses for 162<br>behaviors of 164<br>extending text selection with 165<br>and keyboard navigation 170–172<br>moving the insertion point with 163<br>with Shift key 165<br>assistance. See help systems<br>attributes in menus 46–47<br>audience, knowledge of 33<br>automatic scrolling 83, 215<br>automatic typing. See type-ahead<br>automation, of user tasks 221<br>auto-repeat 176 |
| Apple Guide 219<br>Apple Help 219–221<br>Apple Help Viewer 221                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | B                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| Apple key. See Command key<br>Apple menu 52<br>Apple Publications Style Guide (APSG) 229<br>AppleScript and task automation 221<br>application fonts 189<br>application icons 194–197<br>adding permanently to the Dock 42<br>in alert dialogs 96<br>classifying 192<br>in the Dock 40, 41, 84<br>notification behavior of 40<br>Application Kit 93, 115<br>application menu 53–55<br>Application menu (Mac OS 9) 23<br>application-modal dialogs 92, 93–96<br>application-support files 235                                                       | background selections 212, 216<br>Backspace key. See Delete key<br>Balloon Help. See help tags<br>benefits of applying Aqua guidelines 20<br>bevel buttons 126–130<br>as pop-up menus 128<br>specifications 126<br>Bold command (Format menu) 173<br>boldface fonts 190<br>boxes<br>About 88<br>checkboxes 118–119<br>combination 123–125, 137<br>group 144–147                                                                                                                                                           |

#### **INDEX**

| Bring All to Front command (Window menu) 61,  | checkmarks in menus 50, 63                     |  |
|-----------------------------------------------|------------------------------------------------|--|
| 109<br>bullets in menus 64<br>buttons         | Choose dialogs 110–112                         |  |
|                                               | Clear command (Edit menu). See Delete          |  |
|                                               | command                                        |  |
| See also window controls                      | Clear key 160                                  |  |
| Add to Favorites 101, 104                     | clicking 157, 178                              |  |
| bevel 126–130                                 | click-through 78–81                            |  |
| Cancel 118                                    | Clipboard 58–59, 210                           |  |
| default 118                                   | clippings in drag-and-drop operations 209, 217 |  |
| Help 222                                      | close button 69, 88                            |  |
| pop-up bevel 128                              | Close command (File menu) 57, 173              |  |
| pop-up icon 128                               | Close dialogs 101                              |  |
| push 116–117, 231                             | cloverleaf symbol. See Command key             |  |
| radio 118                                     | Cocoa                                          |  |
| Review Changes 109                            | guidelines for interface elements 115          |  |
|                                               | tools for applying Aqua guidelines 21          |  |
|                                               | color coding 37                                |  |
|                                               | colors, assumptions about 22                   |  |
| C                                             | column view lists 138                          |  |
|                                               | combination boxes 123–125, 137                 |  |
| Cancel button 118                             | Command key 162                                |  |
| capitalization, of interface elements 231     | command pop-down menus 123                     |  |
| Caps Lock key 161                             | Command-A 59, 173                              |  |
| Carbon, tools for applying Aqua guidelines 21 | Command-B 173                                  |  |
| caution icons 97                              | Command-C 59, 173                              |  |
| character keys 159–161                        |                                                |  |
| characters in menus 63–65                     | Command-click 180                              |  |
| checkboxes 118–119                            | Command–Down Arrow 164                         |  |
| checklists for creating applications 237–248  | Command-F 173                                  |  |
| alert dialogs 245                             | Command-G 173                                  |  |
| dialogs 243                                   | Command-H 173                                  |  |
| documentation 247                             | Command-I 173                                  |  |
| general considerations 237–239                | Command-key equivalents 172–176                |  |
| graphic design 239                            | Command–Left Arrow 164, 165, 174               |  |
|                                               | Command-M 173                                  |  |
| help tags 248                                 | Command–modifier key–Space bar 174             |  |
| icons 247                                     | Command-N 173                                  |  |
| keyboard equivalents 246                      | Command-O 99, 173                              |  |
| menus 240                                     | Command–Option–Space bar 174                   |  |
| mouse events 245                              | Command-P 173                                  |  |
| pop-up menus 241                              | Command-Q 173                                  |  |
| scrolling 242                                 | Command–Right Arrow 164, 165, 174              |  |
| text 246                                      | Command-S 173                                  |  |
| user documentation 247                        |                                                |  |
| utility windows 243                           |                                                |  |

windows [241](#page-240-3)

#### **INDEX**

| commands, menu                               | of user experience 20                       |
|----------------------------------------------|---------------------------------------------|
| About (application menu) 55                  | containers for drag-and-drop operations 210 |
| application-wide items (application menu) 55 | contextual menus 62, 222                    |
| Arrange in Front (Window menu) 61            | Control key 162                             |
| Bold (Format menu) 173                       | Control Manager 22, 115                     |
| Bring All to Front (Window menu) 61, 109     | Control-F1 key combination 170              |
| Clear (Edit menu) 59                         | Control-F2 key combination 171              |
| Close (File menu) 57, 173                    | Control-F3 key combination 171              |
| Copy (Edit menu) 59, 173                     | Control-F4 key combination 171              |
| Cut (Edit menu) 59, 173                      | Control-F5 key combination 171              |
| Delete (Edit menu) 59                        | Control-F6 key combination 171              |
| Find (Edit menu) 60, 173                     | controls 115–141                            |
| Find Again (Edit menu) 173                   | appearance of 116–141                       |
| Hide (application menu) 55, 173              | behavior of 116–141                         |
| Italic (Format menu) 173                     | bevel buttons 126–130                       |
| Minimize (Window menu) 173                   | checkboxes 118–119                          |
| New (File menu) 56, 173                      | click-through behavior of 78                |
| Open (File menu) 56, 99, 173                 | close button 69, 88                         |
| Open Font dialog (Format menu) 173           | disclosure triangles 141                    |
| Open Recent (File menu) 56, 99               | grouping in dialogs 144–147                 |
| Page Setup (File menu) 57                    | image wells 140                             |
| Paste (Edit menu) 59, 173                    | layout guidelines for 143–150               |
| Print (File menu) 57, 173                    | minimize button 69, 84                      |
| Quit (application menu) 55, 173              | pop-up bevel buttons 128                    |
| Redo (Edit menu)) 58                         | pop-up icon buttons 128                     |
| Save (File menu) 57, 173                     | pop-up menus 120–122                        |
| Save As (File menu) 57                       | progress indicators 135                     |
| Select All (Edit menu) 59, 173               | push buttons 116–117, 231                   |
| Services (application menu) 55               | radio buttons 118                           |
| Underline (Format menu) 173                  | resize control 69                           |
| Undo (Edit menu) 58, 173, 210                | scroll bars 81–83                           |
| Undo/Redo (Edit menu) 59                     | scrolling lists 140                         |
| Zoom (Window menu) 61                        | sliders 83, 131                             |
| Command–Space bar 174                        | small versions of 153–154                   |
| Command-T 173                                | tabs 84, 132–135, 150                       |
| Command-U 173                                | using in utility windows 153–154            |
| Command–Up Arrow 164                         | window controls 68, 69–70, 81–84, 88        |
| Command-V 59, 173                            | zoom button 69, 77                          |
| Command-W 173                                | copy and paste 210                          |
| Command-X 59, 173                            | Copy command (Edit menu) 59, 173            |
| Command-Z 59, 173                            | copy operations with drag and drop 210      |
| compatibility, as design principle 33        | cultural considerations 34                  |
| confirmation dialogs 210                     | cut and paste 185, 210                      |
| consistency                                  | Cut command (Edit menu) 59, 173             |
| as design principle 29                       |                                             |

| D                                             | confirmation 210                            |
|-----------------------------------------------|---------------------------------------------|
|                                               | document modal 93–95                        |
| dashes                                        | error checking in 98                        |
| in checkboxes 119                             | expanded Save 103–105                       |
| in menus 63                                   | file extension hiding in 91, 101            |
| data browser 138                              | grouping items in 144–147                   |
| data loss, preventing in drag-and-drop        | icons in 92, 96                             |
| operations 211                                | laying out 143                              |
| default button 118                            | localizing 35                               |
| default directories 235–236                   | minimal Save 102–103                        |
| default keyboard access mode 170              | modal 92                                    |
| default location for saving documents 103,    | modeless 88, 92, 189                        |
| 235–236                                       | Open 99                                     |
| default titles for new documents 71           | Page Setup 112–114                          |
| Delete (Backspace) key 160                    | pop-up menus in 120                         |
| Delete command (Edit menu) 59                 | positioning controls in 143–153             |
| design principles 20, 27–38                   | Print 57, 112–114                           |
| aesthetic integrity 31                        | Quit 101, 106–109                           |
| consistency 29                                | save 101–109                                |
| direct manipulation 28                        | sheets 92, 93–95                            |
| feedback and dialog 30                        | text in 189                                 |
| forgiveness 31                                | types and usage of 92–96                    |
| modelessness 32                               | using tabs in 150                           |
| perceived stability 31                        | writing text for 232–233                    |
| see-and-point 28                              | diamonds in menus 64                        |
| use of metaphors 27                           | direct manipulation, as design principle 28 |
| user control 30                               | directories, user domain 235–236            |
| WYSIWYG 29                                    | disabilities 36–38                          |
| Desktop directory 235                         | disclosure triangles 103, 141               |
| desktop, dragging to 217                      | Dock 39–42                                  |
| destination feedback, for drag-and-drop       | activating windows from 41                  |
| operations 213–215                            | animating icons in 40                       |
| destinations for drag-and-drop operations 210 | application icons in 40, 41, 84             |
| Developer Help Center 219                     | icon badging in 40                          |
| developer resources 19                        | icon genres and 192                         |
| developer terms, terminology for 230          | icon menus 40                               |
| dialogs 91–114                                | icon notification behavior in 39            |
| alert 91, 95, 245                             | and positioning of windows 73               |
| application modal 92, 93–96                   | document updates 19                         |
| behavior of 98–114                            | document windows                            |
| changes from Mac OS 9 91                      | defined 67                                  |
| changes in, accepting 98                      | opening 70                                  |
| checklist for creating 243                    | unsaved changes in 70                       |
| Choose 110–112                                | untitled 71                                 |
| Close 101                                     | documentation, checklist for creating 247   |

| document-modal dialogs (sheets) 93–95       | F                                             |
|---------------------------------------------|-----------------------------------------------|
| Documents directory 236                     |                                               |
| documents, storing 236                      | feedback and dialog, as design principle 30   |
| double-clicking 157, 181                    | feedback for drag-and-drop operations 212–217 |
| Down Arrow key 164                          | drag 213                                      |
| drag feedback 213                           | drop 215–217                                  |
| Drag Manager 210, 213                       | for invalid drops 217                         |
| drag-and-drop operations 209–218            | selection 212                                 |
| clippings in 217                            | file extension hiding 23                      |
| common operations and results 211           | in dialogs 91, 101                            |
| copying data in 210                         | and windows 68, 72                            |
| destination feedback for 213–215            | file location 235–236                         |
| drag feedback for 213                       | File menu 55–57                               |
| drop feedback for 215–217                   | Find Again command (Edit menu) 173            |
| feedback for 212–217                        | Find command (Edit menu) 60, 173              |
| Finder and 211, 216                         | Finder                                        |
| moving data in 210                          | as destination for drag-and-drop operations   |
|                                             |                                               |
| overview of 209                             | 211, 216                                      |
| preventing data loss with 211               | drag-and-drop clippings in 217                |
| windows and 210, 212, 213–214               | progress feedback for drag and drop 216       |
| dragging 158, 178                           | Finder icons                                  |
| See also drag-and-drop operations           | See also icons                                |
| drawers 85–87                               | in drag-and-drop operations 216               |
| Drop Box (Public directory) 236             | drop feedback for 216                         |
| drop feedback 215–217                       | floating windows. See utility windows         |
| dynamic menu items 48                       | focus, keyboard 168–172                       |
| See also toggled menu items                 | Font menu 65                                  |
|                                             | fonts, standard 189–190                       |
|                                             | foreign languages 34–36                       |
|                                             | forgiveness, as design principle 31           |
| E                                           | Forward Delete (Del) key 160, 167–168         |
|                                             | full keyboard access mode 170                 |
| Edit menu 58–59                             | function keys 167–168                         |
| editable text fields. See text input fields |                                               |
| editing text 184–186                        |                                               |
| ellipsis character                          |                                               |
| in menus 64                                 | G                                             |
| in scrolling lists 137                      |                                               |
| emphasized system fonts 190                 | global compatibility, as design principle 33  |
| End key 167–168                             | graphic design in applications, checklist for |
| Enter key 159                               | creating 239                                  |
| error checking in dialogs 98                | graphics files, storing 236                   |
| error messages. See alert dialogs           | group boxes 144–147                           |
| Escape (Esc) key 161, 170                   | grouping items                                |
| expanded Save dialog 103–105                | in dialogs 144–147                            |
|                                             | in menus 46, 63                               |

| H                                                | checklist for creating 247                         |
|--------------------------------------------------|----------------------------------------------------|
|                                                  | conveying with emotional qualities 205             |
| hardware, icons for 199                          | design tips for 207                                |
| headings, text in 189                            | in dialogs 92, 96                                  |
| hearing disabilities 37                          | in Dock 39–42                                      |
| help balloons. See help tags                     | families of 192                                    |
| Help button 222                                  | Finder, in drag-and-drop operations 216            |
| Help Center 221                                  | genres of 192                                      |
| Help key 167–168                                 | non-application 197–200                            |
| Help menu 61, 222                                | notification behavior of 40                        |
| help systems 219–227                             | perspective for 202–204                            |
| accessing 222                                    | as pop-up menus 128                                |
| Apple Help 219–221                               | proxy 70                                           |
| Apple's philosophy of 220                        | for setup assistants 225                           |
| changes from Mac OS 9 219                        | steps to create 206                                |
| help tags 189, 222–224, 248                      | in toolbars 201                                    |
| Help Viewer 221                                  | types of 194–202                                   |
| searching within 220                             | image wells 140                                    |
| setup assistants 225–227                         | images, storing 236                                |
| help tags 222–224                                | inactive windows                                   |
| checklist for creating 248                       | clicking in 78–81                                  |
| text in 189                                      | controls in 78                                     |
| Help Viewer 221                                  | dragging from 212, 216                             |
| Hide command (application menu) 55               | dragging to 214                                    |
| hierarchical menus 50                            | insertion indicator for dragged text 214           |
| highlighting                                     | insertion points 163, 166, 214                     |
| in destination regions 213                       | intelligent cut and paste 185                      |
| Finder icons in drag and drop 216                | Interface Builder 21                               |
| of selections 176–184                            | interface design principles. See design principles |
| text in drag-and-drop operations 216             | interface elements                                 |
| Home key 167–168                                 | capitalization of 231                              |
| hot spots 156                                    | changes in Aqua 115                                |
| HTML, displaying in Help Viewer 221              | creating your own 21                               |
| human interface design principles. See design    | default alignment of 143                           |
| principles                                       | guidelines for Carbon developers 115               |
|                                                  |                                                    |
| human interface elements. See interface elements | guidelines for Cocoa developers 115                |
|                                                  | help tags and 219                                  |
|                                                  | labels for 230                                     |
| I                                                | localizing 34                                      |
|                                                  | terminology for 230                                |
| icons 191–208                                    | international considerations 33, 35, 174           |
| application icons. See application icons         | Internet preferences 236                           |
| caution 97                                       | invalid drops, feedback for 217                    |
| changes from Mac OS 9 191                        | Italic command (Format menu) 173                   |
|                                                  |                                                    |

| J                                          | laying out dialogs 143–150                   |
|--------------------------------------------|----------------------------------------------|
|                                            | Left Arrow key 164                           |
| Java tools for applying Aqua guidelines 21 | Library directory 235                        |
|                                            | lists 137, 140                               |
|                                            | localization of interface elements 34        |
| K                                          |                                              |
| keyboard equivalents 172–176               | M                                            |
| checklist for creating 246                 |                                              |
| creating your own 174                      | Mac Help 220                                 |
| for international systems 174              | Macintosh Human Interface Guidelines 19      |
| reserved 173                               | MDEF (standard system menu definition        |
| keyboard focus 168–172                     | procedure) 48                                |
| keyboard navigation 168                    | menu bars 51–61                              |
| keyboards 158–176                          | menu elements 45–47                          |
| keys                                       | menu items 46–50                             |
| arrow 162–166, 170–172                     | See also commands, menu                      |
| character 159–161                          | capitalization of 46, 231                    |
| function 167–168                           | dynamic 48                                   |
| modifier 159, 161–162                      | grouping of 46–47                            |
| kMenuAttrAutoDisable attribute 52          | naming of 46                                 |
| kUtilityWindowClass utility window 67      | text styles in 65                            |
|                                            | toggled 49                                   |
|                                            | Menu Manager 52                              |
|                                            | menu titles 45, 231                          |
| L                                          | menus 43–65                                  |
| label font 190                             | Apple 52                                     |
| labels                                     | application 53–55                            |
| capitalization of 232                      | attribute groups in 46–47                    |
| for checkboxes 118                         | behavior of 48–51                            |
| for combo boxes 123                        | changes from Mac OS 9 43                     |
| for pop-up menus 120                       | checklist for creating 240                   |
| for push buttons 116                       | checkmarks in 50, 63<br>command pop-down 123 |
| for radio buttons 118                      | contextual 62, 222                           |
| for tabs 133                               | dashes in 63                                 |
| terminology for 230                        | Edit 58–59                                   |
| language 229–234                           | File 55–57                                   |
| alert messages, writing 232                | Font 65                                      |
| design principles for 34                   | grouping items in 47                         |
| style and usage 229, 249–259               | Help 61, 222                                 |
| terminology in the interface 230–232       | hierarchical 50                              |
| translation considerations 35              | nonstandard characters in 63–65              |
| layering of windows 60, 68, 109            | pop-up 120–122, 241                          |

| menus (continued)                                                                                                                                                                                                                                                                                                                                                                               | O                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| pull-down 51–61<br>scrolling 48<br>separators in 47<br>sticky 51<br>Style 65<br>symbols in 63<br>text styles in 63–65<br>View 60<br>Window 60<br>metaphors, use of as design principle 27<br>MIDI files, storing 236<br>minimal Save dialog 102–103<br>minimize button 69, 84                                                                                                                   | online documentation. See help systems<br>onscreen elements. See interface elements<br>onscreen help. See help systems<br>Open command (File menu) 56, 99<br>Open dialogs 99<br>Open Font dialog command (Format menu) 173<br>Open Recent command (File menu) 56, 99<br>Option key<br>drag-and-drop operations and 210–211<br>uses of 161<br>Option–Arrow key combinations 164                                                                                              |
| modal dialogs 92<br>modeless dialogs 88, 92, 189<br>modelessness, as design principle 32                                                                                                                                                                                                                                                                                                        | P                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| modifier keys 159, 161–162<br>monitors and window size 75<br>mouse devices 156–158<br>mouse events, checklist for handling 245<br>Mouse Keys 38<br>mouse-down events<br>Option key modifier with 211<br>single-gesture selection and dragging and 212<br>move operations with drag and drop 210<br>Movies directory 236<br>moving windows 77<br>Music directory 236<br>music files, storing 236 | Page Down key 83, 167–168<br>Page Setup command (File menu) 57<br>Page Setup dialog 112–114<br>Page Up key 83, 167–168<br>palettes. See utility windows<br>panes 84, 112–114, 132–135<br>passwords, entering 187<br>Paste command (Edit menu) 59, 173<br>pasteboard. See Clipboard<br>PDEs (printing dialog extensions) 112<br>perceived stability, as design principle 31<br>physical disabilities 38<br>Pictures directory 236<br>placards 126<br>plug-ins, icons for 199 |
| N                                                                                                                                                                                                                                                                                                                                                                                               | pointers 156<br>pointing devices 156                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| Navigation Services 100<br>New command (File menu) 56<br>NSDrawer class 85<br>NSUtilityWindowMask style mask 67                                                                                                                                                                                                                                                                                 | pop-up bevel buttons 128<br>pop-up icon buttons 128<br>pop-up menus 120–122, 125, 241<br>See also combination boxes<br>preferences, icons for 199<br>pressing the mouse button 157<br>principles of human interface design. See design<br>principles<br>Print command (File menu) 57, 173                                                                                                                                                                                   |

Print dialog [57,](#page-56-5) [112–](#page-111-3)[114](#page-113-1)

| printing dialog extensions (PDEs) 112          | S                                         |
|------------------------------------------------|-------------------------------------------|
| programming tools for applying Aqua guidelines |                                           |
| 20                                             | Save a Copy command, avoiding 57          |
| Programming With the Appearance Manager 21     | Save As command (File menu) 57            |
| progress bars 135                              | Save command (File menu) 57, 173          |
| progress feedback for drag-and-drop operations | save dialogs 101–109                      |
| 216                                            | scroll arrows 81                          |
| progress indicators 135                        | scroll bars 81–83                         |
| proxy icons 70                                 | See also sliders                          |
| Public directory 236                           | scroll tracks 81                          |
| pull-down menus 43–65                          | scrollers 81                              |
| behavior of 48–50                              | scrolling lists                           |
| elements of 45                                 | defined 137                               |
| push buttons 116–117                           | specifications for 140                    |
| capitalization of labels 231                   | versus pop-up menus 125                   |
| specifications for 117                         | versus sliders 137                        |
| stacking 117                                   | scrolling menus 48                        |
|                                                | scrolling windows 81–84                   |
|                                                | automatically 83                          |
|                                                | checklist for proper behavior 242         |
| Q                                              | by position 82                            |
|                                                | by unit 82                                |
| QuickTime, and Apple Help 221                  | by windowful 83                           |
| Quit command (application menu) 55             | see-and-point, as design principle 28     |
| quit operations, dialogs for 106–109           | Select All command (Edit menu) 59, 173    |
|                                                | selecting 176–183                         |
|                                                | in arrays 183                             |
|                                                | changing selections 165, 179–180          |
| R                                              | by clicking 178                           |
|                                                |                                           |
| radio buttons 118                              | by dragging 178                           |
| range-selection for drag-and-drop operations   | graphics 183                              |
| 212                                            | in tables 183                             |
| recessed buttons. See image wells              | in text 181–183                           |
| Redo command (Edit menu) 58                    | word boundaries and 182                   |
| region-dependent information, storing 36       | selection feedback, and dragging 212, 216 |
| relevance control 136                          | sentence style capitalization 231         |
| removable media, icons for 199                 | separators, menu 47                       |
| replace document dialog 109                    | Services command (application menu) 55    |
| resize control 69                              | setFloatingPanel function 67              |
| resources for storing region-dependent         | setup assistants 225–227                  |
| information 36                                 | Sharing preferences 236                   |
| Return key 160                                 | sheets (document-modal dialogs) 93–95     |
| Review Changes button 109                      | Shift key 161, 165                        |
| Right Arrow key 164                            | Shift–Command–arrow key combinations 166  |
|                                                | Shift–Option–arrow key combinations 165   |

### **INDEX**

| Shift-Tab key 170                         | text editing 184–186                               |
|-------------------------------------------|----------------------------------------------------|
| single-gesture selection and dragging 212 | deleting 184                                       |
| Sites directory 236                       | inserting 184                                      |
| sliders 83, 131                           | intelligent cut and paste 185                      |
| See also scroll bars                      | and keyboard focus 168                             |
| small versions of controls 116, 153–154   | for localization 35                                |
| smart cut and paste 185                   | replacing selections 185                           |
| sound files, storing 236                  | in text entry fields 186                           |
| Space bar 159, 170                        | using Shift and arrow keys 165                     |
| standard fonts 189–190                    | text input fields 137, 186                         |
| standard pull-down menus 51–61            | See also combination boxes                         |
| standard state of a window 77             | text styles in menus 63–65                         |
|                                           |                                                    |
| standard system menu definition procedure | text-to-speech converters 35                       |
| (MDEF) 48                                 | tick marks in slider controls 131                  |
| static text fields 137                    | title bars 69                                      |
| Sticky Keys 38                            | title style capitalization 231                     |
| sticky menus 51                           | titles for menus 45                                |
| strings and word boundaries 181           | toggled menu items 49                              |
| style and usage of language 229, 249–259  | See also dynamic menu items                        |
| Style menu 65                             | tool palettes. See utility windows                 |
| styled text in menus 63–65                | toolbars                                           |
| submenus. See hierarchical menus          | commands for 60                                    |
| symbols in menus 63                       | customizing 60                                     |
| system fonts 189                          | icons in 201                                       |
|                                           | tools for applying Aqua guidelines 20              |
|                                           | Trash icon 39                                      |
| T                                         | Trash, as drag-and-drop destination 215            |
|                                           | triangles, disclosure 141                          |
| tab controls 84, 132–135, 150             | triple-clicking 182                                |
| Tab key 159, 170                          | type-ahead 176                                     |
| tables, selecting text in 183             |                                                    |
| target audience, knowledge of 33          |                                                    |
| terminology 230–232, 249–259              | U                                                  |
| text                                      |                                                    |
| See also fonts; labels                    | Underline command (Format menu) 173                |
| in alerts 95                              | Undo/Redo command (Edit menu) 59, 173, 210         |
| anti-aliasing 190                         | Unicode 35                                         |
| checklist for working with 246            | universal accessibility, as design principle 36–38 |
|                                           |                                                    |
| design principles for displaying 35       | unsaved changes, handling on Close or Quit 105     |
| destination feedback in 214               | Up Arrow key 164                                   |
| drop feedback in 216                      | updates to this book 19                            |
| global support of 35                      | user control, as design principle 30               |
| in labels 190                             | user documentation, checklist for creating 247     |
|                                           | user domain directories 235–236                    |

#### **INDEX**

| user help. See help systems               | automatic scrolling in 83, 215                  |
|-------------------------------------------|-------------------------------------------------|
| user input 155–186                        | behavior 69–85                                  |
| editing text 184–186                      | changes from Mac OS 9 68                        |
| keyboards 158–176                         | checklist for 241                               |
| mouse devices 156–158                     | closing 76                                      |
| non-Roman script systems 165              | controls for 68, 69–70, 81–84, 88               |
| pointing devices 156                      | displaying on multiple monitors 75              |
| selecting 176–183                         | document 67                                     |
|                                           |                                                 |
| user state of a window 77                 | as drag-and-drop destinations 210, 212,         |
| user terms, terminology for 230           | 213–214, 216                                    |
| user-created files, default locations 236 | expanding 42, 84                                |
| user-friendly language 230                | inactive 78                                     |
| utility windows                           | layering of 60, 68, 109                         |
| checklist for creating 243                | minimizing 84                                   |
| defined 67                                | modeless 88–89                                  |
| guidelines for 87                         | moving 77                                       |
| using small controls in 153–154           | naming 71–72                                    |
|                                           | opening 70                                      |
|                                           | positioning of 73                               |
|                                           | resizing 77                                     |
| V                                         | scrolling 81–84                                 |
|                                           | special 85–89                                   |
| video files, storing 236                  | standard state 77                               |
| View menu 60                              | titles for 71                                   |
| visual disabilities 37                    | user state 78                                   |
|                                           | utility. See utility windows                    |
|                                           | zooming 77                                      |
|                                           |                                                 |
| W, X, Y                                   | words, selecting 181                            |
|                                           | worldwide compatibility, as design principle 33 |
| Web Sharing 236                           | WYSIWYG, as design principle 29                 |
| window controls                           |                                                 |
| close button 69, 88                       |                                                 |
| minimize button 69, 84                    |                                                 |
| proxy icons 70                            | Z                                               |
| scroll bars 81–83                         |                                                 |
| zoom button 69, 78                        | zoom button 69, 78                              |
| Window Manager 21                         | Zoom command (Window menu) 61                   |
| Window menu 60                            | zoomback behavior 217                           |
| window shade feature. See minimize button |                                                 |
|                                           |                                                 |
| windows 67–89                             |                                                 |
| See also alert dialogs; dialogs           |                                                 |
| activating from the Dock 41               |                                                 |
| active 78                                 |                                                 |
| appearance 69–85                          |                                                 |
|                                           |                                                 |