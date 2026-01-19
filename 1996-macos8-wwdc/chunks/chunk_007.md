<!-- Chunk 7 | Source: 1996 Human Interface Guidelines for Mac OS 8 (WWDC Release).pdf | Est. Tokens: 844 -->
The Mac OS 8 Toolbox now provides support for several controls that you previously had to implement. Note that all controls now have a focused state that indicates which control will receive keyboard input for keyboard navigation.  
#### Bevel Buttons 0  
Bevel buttons appear in toolbars and in windows to provide access to features. Bevel buttons won't necessarily have a bevel in every theme. You can put icons, pictures, and text on bevel buttons. Bevel buttons have several states. They appear in the available, pressed, on, mixed, and disabled states. Note that the on state combines the appearance of a pressed button with an unselected icon so that the user can visually identify the icon. Figure 10 shows an example of a bevel button with a 32-by-32 pixel icon.  
**Figure 10** Bevel button  
![](images/_page_13_Picture_6.jpeg)  
You can put black-and-white icons on bevel buttons. In this case the icons maintain their black and white look and state transitions.  
When you have an icon or a picture on a bevel button, you should leave at least one pixel of space between the image and the border of the button. To determine this space, consider how the image looks with more or less space around it. Too much space makes the image look like it is floating in a sea of gray. Too little space makes it look cramped.  
Generally you should center any image or text on the button face. There are times when the image may need an extra pixel or two of space to visually  
<span id="page-14-0"></span>balance the image. If the image appears to lean one way or another, you can create a visual balance by placing the image slightly off center.  
#### Disclosure Triangle 0  
The disclosure triangle used in Finder windows to allow users to expand containers, such as folders, without opening them is now provided by the Mac OS 8 Toolbox. Figure 11 shows the disclosure triangle. You can use it as means of progressive disclosure to reveal more information in a list view. See the chapter, "Controls," in *Macintosh Human Interface Guidelines* for a further description.  
**Figure 11** Disclosure triangle  
![](images/_page_14_Picture_5.jpeg)  
#### Little Arrows 0  
The Mac OS 8 Toolbox provides the little arrows control that you use to increment or decrement values in a series. Figure 12 shows the little arrows control. See the chapter, "Controls," in *Macintosh Human Interface Guidelines* for a further description.  
**Figure 12** Little arrows  
![](images/_page_14_Picture_9.jpeg)  
Controls **15**  
#### <span id="page-15-0"></span>Sliders 0  
Sliders are now provided by the Mac OS 8 Toolbox. A slider is a control that displays a range of values, magnitude, or position of something in the system or an application. You can use a pointed indicator or a rectangular indicator. Figure 13 shows a horizontal slider and a vertical slider without labels or tick marks.  
**Figure 13** Slider  
![](images/_page_15_Picture_4.jpeg)  
If it makes sense for your slider, you can include tick marks that indicate values in the range. The Appearance Manager provides tick marks as a primitive. You need to handle the tracking and feedback for the tick marks. Figure 14 shows an example of the tick marks.  
**Figure 14** Tick marks  
![](images/_page_15_Picture_7.jpeg)  
See the chapter, "Controls," in *Macintosh Human Interface Guidelines* for a further description.