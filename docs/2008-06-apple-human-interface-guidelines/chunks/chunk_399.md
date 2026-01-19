<!-- Chunk 399 | Source: 2008-06 Apple Human Interface Guidelines.pdf | Est. Tokens: 649 -->
A **determinate progress bar** shows users that a process is occurring and gives them a rough idea of when it will finish. For example, Figure 15-55 shows the progress indicator Software Update displays when it is checking for new software.  
<span id="page-302-0"></span>**Figure 15-55** A determinate progress bar provides feedback on a process with a known duration  
![](images/_page_302_Picture_3.jpeg)  
#### <span id="page-302-1"></span>**Determinate Progress Bar Usage**  
Use a determinate progress bar when the full length of an operation can be determined and you can tell the user how much of the process has been completed. For example, you could use a determinate progress bar to show the progress of a file conversion.  
You should ensure that a determinate progress bar in your application accurately associates progress with time. A progress bar that becomes 90 percent complete in 5 seconds but takes 5 minutes for the remaining 10 percent, for example, would be annoying and lead users to think that something is wrong.  
#### **Determinate Progress Bar Contents and Labeling**  
In a determinate progress bar, the "fill" moves from left to right and should fill in completely before it is dismissed. The fill is provided automatically, but you can determine the minimum and maximum values that should be represented.  
If necessary, you can provide a complete or partial sentence that appears as a label with a determinate progress bar in a dialog. You can do this so users understand the context in which the process is occurring. Such a label should have sentence-style capitalization (see ["Capitalization](#page-130-1) of Interface Element Labels and [Text"](#page-130-1) (page 131) for more information on this style).  
#### **Determinate Progress Bar Specifications**  
Determinate progressindicators are available in regular and smallsizes. The height of a determinate progress indicator is fixed for each size, but you can specify the length. Figure 15-56 shows a regular-size determinate progress bar as it looks when active and inactive.  
<span id="page-303-0"></span>**Figure 15-56** The active and inactive appearance of a determinate progress bar  
![](images/_page_303_Picture_3.jpeg)  
#### **Determinate Progress Bar Implementation**  
Determinate progress bars are available in Interface Builder. In the Attributes pane of the inspector, select Bar for the style and deselect the Indeterminate checkbox. To create a determinate progress bar using Application Kit programming interfaces, use the NSProgressIndicator class with style NSProgressIndicatorBarStyle.