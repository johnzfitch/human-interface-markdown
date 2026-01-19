<!-- Chunk 263 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 1710 -->
<span id="page-304-1"></span>A **slider** lets users choose from a continuousrange of allowable values. For example, Energy Saver preferences (shown in Figure 15-48) provides two sliders that allow users to specify when the computer and the display should sleep.  
**Figure 15-48** Sliders allow users to choose from a continuous range of values  
![](images/_page_304_Picture_7.jpeg)  
Sliders can be linear (as shown in Figure 15-48) or circular, as shown in Figure 15-49. Typically, users can spin circular sliders in either direction and through the point between the beginning and ending values.  
<span id="page-305-0"></span>**Figure 15-49** A circular slider  
![](images/_page_305_Picture_3.jpeg)  
#### Slider Usage  
Sliders support live feedback (live dragging), so they're especially useful when you want users to be able to see the effects of moving a slider in real time. For example, users can watch the size of Dock icons change as they move the Dock Size slider in Dock preferences.  
To decide whether a slider should be linear or circular (and, if linear, whether it should be horizontal or vertical), examine the user's mental model of the task your application performs and try to meet their expectations of similar real-world controls. (You can learn more about the user's mental model in ["Reflect](#page-38-3) the User's Mental [Model"](#page-38-3) (page 39).) For example, the circular slider in Figure 15-49 allows users to choose the angle of the drop shadow displayed for an object. The circular slider not only displays the full range of values (0 to 360 degrees) in a compact way, it also mirrors the placement of the drop shadow itself as it is displayed on different sides of the object.  
On the other hand, a linear slider is appropriate in Energy Saver preferences (shown in [Figure](#page-304-1) 15-48 (page 305)) because the values range from very small (the screen saver should start after 3 minutes) to very large (the screen saver should never start) and do not increase at consistent intervals. In this case, a linear slider brings to mind a number line that stretches from the origin to infinity.  
You can display tick marks with both linear and circular sliders. In general, you should display tick marks when it's important for users to understand the scale of the measurements or when users need to be able to select specific values. If, on the other hand, users don't need to be aware of the specific values the slider passesthrough (asin the Dock size and magnification preferences, for example), you might choose to display a slider without tick marks.  
#### Slider Contents and Labeling  
The movable part of a linear slider is called the thumb. The thumb can be either directional or round. The directional thumb is especially useful for sliders with tick marks, because the point of the thumb helps show users the current value (see [Figure](#page-304-1) 15-48 (page 305) for examples of directional slider thumbs). However, you <span id="page-306-2"></span>can also display a directional-thumb slider without tick marks. The round thumb is recommended for sliders that don't display tick marks, because the rounded lower edge of the thumb does not appear to point to a specific value. (If you use Interface Builder to create a slider, note that specifying any nonzero number of tick marks automatically changes a round thumb to a directional one.) Figure 15-50 shows an example of slider with a round thumb.  
<span id="page-306-0"></span>**Figure 15-50** A linear slider without tick marks should display a round thumb  
![](images/_page_306_Picture_4.jpeg)  
A circular slider displays a small circular dimple that provides the same functionality as the thumb of a linear slider: Users drag the dimple clockwise or counter-clockwise to change the values.  
<span id="page-306-1"></span>If you want to display tick marks with a slider, be sure to label at least the starting and ending values. You can do this using numbers or words, depending on what the values represent. If each tick mark represents an equal fraction of the entire range, it may not be necessary to label each one. However, if users can't deduce the value of each tick mark from its position in the range, you probably should label each one to prevent confusion. For example, it's important to label some of the interior tick marks in Energy Saver preferences (shown in [Figure](#page-304-1) 15-48 (page 305)), because the intervals do not all represent an equal amount of time. In addition, it's a good idea to set the context for a slider with an introductory label so users know what they're changing. Figure 15-51 shows both types of sliders, with and without tick marks.  
**Figure 15-51** Examples of different types of sliders  
![](images/_page_306_Picture_8.jpeg)  
#### Slider Control Specifications  
**Control sizes**: Linear sliders are available in regular, small, and mini sizes. Circular sliders are available in regular and small sizes. The dimensions of sliders are fixed for each size and type, but the inclusion of tick marks changes the effective size of the control. These measurements are stated below to help you with your layout.  
Height of horizontally positioned linear sliders:  
- Regular size, directional thumb: 19 pixels without tick marks, 25 pixels with tick marks.
- Regular size, round thumb: 15 pixels.
- Small, directional thumb: 14 pixels without tick marks, 19 pixels with tick marks.
- Small, round thumb: 12 pixels.
- Mini, directional thumb: 11 pixels without tick marks, 17 pixels with tick marks.
- Mini, round thumb: 10 pixels.  
Width of vertically positioned linear sliders:  
- Regular size, directional thumb: 18 pixels without tick marks, 24 pixels with tick marks.
- Regular size, round thumb: 15 pixels.
- Small, directional thumb: 14 pixels without tick marks, 19 pixels with tick marks.
- Small, round thumb: 11 pixels.
- Mini, directional thumb: 11 pixels without tick marks, 17 pixels with tick marks.
- Mini, round thumb: 10 pixels.  
Diameter of circular sliders:  
- Regular size with tick marks: 32 pixels.
- Regular size without tick marks: 24 pixels.
- Small with tick marks: 22 pixels.
- Small without tick marks: 18 pixels.  
**Label spacing and fonts**: For the labels that describe the range of values, use the following font sizes:  
- Regular size: Label font.
- Small: Label font.
- Mini: 9-point label font.  
**Control spacing**: When you display multiple linear sliders, leave the following amounts of space between them:  
- Regular size: At least 12 pixels.
- <span id="page-308-3"></span>● Small: At least 10 pixels.
- Mini: At least 8 pixels.  
#### Slider Control Implementation  
<span id="page-308-0"></span>Sliders are available in Interface Builder. To create one using Application Kit programming interfaces, use the NSSlider class.