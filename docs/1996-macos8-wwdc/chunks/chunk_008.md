<!-- Chunk 8 | Source: 1996 Human Interface Guidelines for Mac OS 8 (WWDC Release).pdf | Est. Tokens: 852 -->
The Appearance Manager includes visual elements that you can use to organize information in dialog boxes and palettes. These elements are called primitives. Unlike controls, they have no behavior associated with them.  
#### Group Boxes 0  
The Appearance Manager now provides primitives that you use to draw boxes around content within a dialog box. There are two levels of group boxes; primary group boxes and secondary group boxes.  
#### Primary Group Boxes 0  
You use a primary group box to organize visually related items in a dialog box or window. You should use a group box where you have a set of two or more related controls. Don't include a group box for just one control because adding too many elements to a dialog box creates visual clutter that makes it hard for people to discriminate the key elements. Figure 15 shows an appearance for primary group boxes in an active dialog box.  
<span id="page-17-0"></span>**Figure 15** Primary group boxes in an active dialog box  
![](images/_page_17_Picture_2.jpeg)  
[Figure 16](#page-18-0) shows an appearance for primary group boxes in an inactive dialog box.  
<span id="page-18-0"></span>**Figure 16** Primary group boxes in an inactive dialog box  
![](images/_page_18_Picture_2.jpeg)  
You can use a control such as a pop-up menu or a checkbox as a title for the setting in a group box. If you use a pop-up menu as a master control, it changes the settings that appear in the group box as the user changes the choice in the menu. If you use a check box for a master control, it enables the settings contained in the group box when the check box is checked.  
You must implement the control as a separate entity from the group box itself. For information on implementing a group box with a control as its title, see "Introduction to the Mac OS 8 Toolbox" chapter in the document *Human Interface Toolbox*.  
#### <span id="page-19-0"></span>Secondary Group Boxes 0  
You use a secondary group box to organize visually related items within a primary group box. The secondary group box appearance gives it a subordinate appearance related to the primary group box. The appearance aids in the perception of the organizational hierarchy. Figure 17 shows an appearance of secondary group boxes in an active dialog box.  
**Figure 17** Secondary group boxes in an active dialog box  
![](images/_page_19_Picture_4.jpeg)  
<span id="page-20-0"></span>Figure 18 shows an appearance for secondary group boxes in an inactive dialog box.  
**Figure 18** Secondary group boxes in an inactive dialog box  
![](images/_page_20_Picture_3.jpeg)  
As with the primary group box, you can use a control such as a pop-up or checkbox as a title for the setting in a group box. The same rules apply to the case of the secondary group box.  
#### <span id="page-21-0"></span>Separators 0  
You use vertical and horizontal separators in dialog boxes to visually distinguish areas with separate settings. Figure 19 shows an example of a control panel with a vertical separator and two horizontal separators that serve to group related settings without the complexity of group boxes.  
**Figure 19** Separators in a dialog box  
![](images/_page_21_Picture_4.jpeg)  
You can use a vertical separator or a horizontal separator or both. The appearance of the separators is shown in [Figure 20](#page-22-0).  
<span id="page-22-0"></span>![](images/_page_22_Picture_1.jpeg)