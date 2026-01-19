<!-- Chunk 267 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 2636 -->
**Progress indicators** inform users about the status of lengthy operations. (For guidelines on when to provide such information, see "Feedback and [Communication"](#page-41-1) (page 42).)  
Progressindicators often appear in a dialog that describesthe progress of a process. When the process being performed can be interrupted, the progress dialog should contain a Cancel button (and support the Esc key). If interrupting the process will result in possible side effects, the button should say Stop instead of Cancel. To learn more about dialogs in general, see ["Dialogs"](#page-234-0) (page 235). To supply a Cancel (or Stop) button, you use a push button; for more information about this control, see "Push [Buttons"](#page-264-1) (page 265).  
Be sure to locate progress indicators in consistent locations in your windows and dialogs. For example, the Mail application displays the asynchronous progress indicator in the far right of the To field as it finds and displays email addressesthat match what the user types. Choosing a consistent location for progressindicators allows users to quickly check a familiar place for the status of an operation. See ["Consistency"](#page-42-0) (page 43) for more information on the importance of providing consistency in your application.  
There are three types of progress indicators, each of which is suitable for a specific situation:  
- Determinate progress bar
- Indeterminate progress bar
- <span id="page-310-1"></span>● Asynchronous progress indicator  
#### Determinate Progress Bars  
A **determinate progress bar** shows users that a process is occurring and gives them a rough idea of when it will finish. For example, Figure 15-55 shows the progress indicator Software Update displays when it is checking for new software.  
<span id="page-311-0"></span>**Figure 15-55** A determinate progress bar provides feedback on a process with a known duration  
![](images/_page_311_Picture_3.jpeg)  
#### <span id="page-311-1"></span>**Determinate Progress Bar Usage**  
Use a determinate progress bar when the full length of an operation can be determined and you can tell the user how much of the process has been completed. For example, you could use a determinate progress bar to show the progress of a file conversion.  
You should ensure that a determinate progress bar in your application accurately associates progress with time. A progress bar that becomes 90 percent complete in 5 seconds but takes 5 minutes for the remaining 10 percent, for example, would be annoying and lead users to think that something is wrong.  
#### **Determinate Progress Bar Contents and Labeling**  
In a determinate progress bar, the "fill" moves from left to right and should fill in completely before it is dismissed. The fill is provided automatically, but you can determine the minimum and maximum values that should be represented.  
If necessary, you can provide a complete or partial sentence that appears as a label with a determinate progress bar in a dialog. You can do this so users understand the context in which the process is occurring. Such a label should have sentence-style capitalization (see ["Capitalization](#page-135-0) of Interface Element Labels and [Text"](#page-135-0) (page 136) for more information on this style).  
#### **Determinate Progress Bar Specifications**  
Determinate progressindicators are available in regular and smallsizes. The height of a determinate progress indicator is fixed for each size, but you can specify the length. Figure 15-56 shows a regular-size determinate progress bar as it looks when active and inactive.  
<span id="page-312-0"></span>**Figure 15-56** The active and inactive appearance of a determinate progress bar  
![](images/_page_312_Picture_3.jpeg)  
#### **Determinate Progress Bar Implementation**  
Determinate progress bars are available in Interface Builder. In the Attributes pane of the inspector, select Bar for the style and deselect the Indeterminate checkbox. To create a determinate progress bar using Application Kit programming interfaces, use the NSProgressIndicator class with style NSProgressIndicatorBarStyle.  
#### <span id="page-312-2"></span>Indeterminate Progress Bars  
<span id="page-312-1"></span>An **indeterminate progress bar** shows users that processing is occurring, but does not give any indication of when it will finish. For example, Keynote displays an indeterminate progress bar as it begins opening a file, as shown in Figure 15-57.  
**Figure 15-57** An indeterminate progress bar provides feedback on a process of unknown duration  
![](images/_page_312_Picture_9.jpeg)  
#### <span id="page-312-3"></span>**Indeterminate Progress Bar Usage**  
Use an indeterminate progress bar when the duration of a process can't be determined. For example, if your application attemptsto make a dial-up communication connection, you have no way to accurately determine how long it will take, so you can use an indeterminate progress indicator to let users know that processing is ongoing. If an indeterminate process reaches a point where its duration can be determined, switch to a determinate progress bar (see ["Determinate](#page-310-1) Progress Bars" (page 311) for more on determinate progress bars).  
Indeterminate progress bars work best in a dialog or window that focuses on the occurring process. For example, the indeterminate progress bar Keynote displays is in a dialog that is focused solely on the opening of the file (this dialog is shown in Figure 15-57). If you need to provide an indication of an indeterminate process that's associated with a part of a window, such as a control, or if space is limited, consider using an asynchronous progress indicator instead. (See ["Asynchronous](#page-313-1) Progress Indicators" (page 314) for more information on asynchronous progress indicators.)  
#### **Indeterminate Progress Bar Contents and Labeling**  
An indeterminate progress bar displays a spinning striped cylinder to indicate an ongoing process. Mac OS X provides this appearance automatically.  
If necessary, you can provide a complete or partial sentence that appears as a label with an indeterminate progress bar in a dialog. You can do this so users know what process is occurring. Such a label should have sentence-style capitalization (see ["Capitalization](#page-135-0) of Interface Element Labels and Text" (page 136) for more information on this style). Also, you can end the label with an ellipsis (...) to emphasize the ongoing nature of the processing.  
#### **Indeterminate Progress Bar Specifications**  
<span id="page-313-0"></span>Indeterminate progress bars are available in regular and small sizes. The height of an indeterminate progress bar is fixed for each size, but you can specify the length. Figure 15-58 shows both regular-size and small indeterminate progress bars as they look when active and inactive.  
**Figure 15-58** The active and inactive appearance of an indeterminate progress bar  
![](images/_page_313_Picture_8.jpeg)  
#### **Indeterminate Progress Bar Implementation**  
<span id="page-313-1"></span>Indeterminate progress bars are available in Interface Builder. In the Attributes pane of the inspector, select Bar for the style and be sure the Indeterminate checkbox is selected. To create an indeterminate progress bar using Application Kit programming interfaces, use the NSProgressIndicator class with style NSProgressIndicatorBarStyle.  
#### <span id="page-313-2"></span>Asynchronous Progress Indicators  
An **asynchronous progress indicator**shows usersthat processing is occurring but does not give any indication of when the process will finish. For example, Mail briefly displays an asynchronous progress indicator in the To: field of a New Message window while it performs a search on the name the user types, asshown in Figure 15-59.  
<span id="page-314-0"></span>**Figure 15-59** An asynchronous progress indicator provides feedback on a process  
![](images/_page_314_Picture_3.jpeg)  
#### **Asynchronous Progress Indicator Usage**  
Use an asynchronous progress indicator when space is very constrained, such as in a text field or near a control. Because this indicator is small and unobtrusive, it is especially useful for asynchronous events that take place in the background, such as retrieving messages from a server.  
Don't use the asynchronous progress indicator in operations that start out indeterminate but could become determinate, because the determinate progressindicator is a differentshape and takes up much more space. If the process might change from indeterminate to determinate, use an indeterminate progress bar instead of an asynchronous progress indicator, because it is the same shape and size as the determinate progress bar. (See ["Indeterminate](#page-312-2) Progress Bars" (page 313) for more information about indeterminate progress bars.)  
#### **Asynchronous Progress Indicator Contents and Labeling**  
Because an asynchronous progress indicator typically appears when the user initiates a process, a label may not be necessary. If you decide to provide a label that appears with the indicator, create a complete or partial sentence that briefly describes the process that is occurring.  
If you decide to provide a label that appears with an asynchronous progress indicator, be sure to use sentence-style capitalization (see ["Capitalization](#page-135-0) of Interface Element Labels and Text" (page 136) for more information on this style). Also, you can end the label with an ellipsis (...) to emphasize the ongoing nature of the processing.  
#### <span id="page-314-1"></span>**Asynchronous Progress Indicator Specifications**  
The appearance of the asynchronous progress indicator is provided automatically, but you can choose the size that fits best in your window layout. Asynchronous progress indicators are available in regular, small, and mini sizes. Figure 15-60 shows a regular-size asynchronous progress indicator.  
**Figure 15-60** A regular-size asynchronous progress indicator  
![](images/_page_314_Picture_13.jpeg)  
#### **Asynchronous Progress Indicator Implementation**  
<span id="page-315-5"></span>Asynchronous progress indicators are available in Interface Builder. In the Attributes pane of the inspector, select Spinning for the style and be sure the Indeterminate checkbox is selected. To create an asynchronous progressindicator using Application Kit programming interfaces, use the NSProgressIndicator class with style NSProgressIndicatorSpinningStyle.