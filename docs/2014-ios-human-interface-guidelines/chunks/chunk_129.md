<!-- Chunk 129 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 433 -->
A **slider** allows users to make adjustments to a value or process throughout a range of allowed values (shown here with custom images on the left and the right).  
![](images/_page_191_Picture_3.jpeg)  
**API Note:** To learn more about defining a slider in your code, see "Sliders".  
#### A slider:  
- Consists of a horizontal track and a thumb (a circular control that users can slide)
- Can include optional images that convey the meaning of the right and left values
- Fills the portion of the track between the minimum value (typically on the left) and the thumb  
Use a slider to give users fine-grained control over values they can choose or over the operation of the current process.  
**If it adds value, create custom appearances for a slider.** For example, you can:  
- Define the appearance of the thumb, so that users can see at a glance whether the slider is active
- Supply images to appear at both ends of the slider to help users understand what the slider does Typically, these custom images correspond to the minimum and maximum values of the value range that the slider controls. A slider that controls image size, for example, could display a very small image at the minimum end and a very large image at the maximum end.
- Define a different appearance for the track, depending on which side of the thumb it is on and which state the control is in  
<span id="page-191-1"></span>**Don't use a slider to display a volume control.** If you need to display a volume slider, use the system provided volume slider available when you use the MPVolumeView class. Note that when the currently active audio output device doesn't support volume control, the volume slider is replaced by the appropriate device name.