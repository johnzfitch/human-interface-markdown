<!-- Chunk 54 | Source: 1996 Newton 2.0 User Interface Guidelines.pdf | Est. Tokens: 1376 -->
When an application begins an operation that takes more than a few seconds to complete, the application should display a message describing its busy status. The application can display the status message in a view that's already displayed, or it can display the message in a **status slip.** Figure 2-19 shows a typical status slip.  
**Figure 2-19** A status slip reports on a lengthy operation  
![](images/_page_63_Picture_5.jpeg)  
A status slip contains some or all of the following items:  
- An icon visually identifies the application or the operation in progress.
- A title names the application or the operation in progress.
- A message provides additional information about the operation in progress (for example, "Searching Names...", "Connecting to desktop", and so on).
- A progress indicator shows that the system is busy, and may show elapsing progress.
- A Stop or Cancel button allows a user to halt the ongoing operation.
- A Close box allows a user to put away the status slip without halting the ongoing operation.  
<span id="page-64-0"></span>A status slip does not take the place of the Newton busy cursor, which appears automatically at the top center of the screen when the system temporarily cannot respond to user input (see ["Automatic Busy Cursor" on](#page-243-0)  [page 8-2](#page-243-0)). Your application should display a status slip when it begins an operation that takes more than a few seconds to complete.  
#### Title and Message 2  
Either the title or the message text in a status slip should begin with a gerund, such as *preparing* or *sorting*, and end with three periods (. . .), not a single period, a hyphen, a dash, or an ellipsis character (…). For example, when searching more than one application, the built-in Find service displays "Find" on the first line and a message similar to "Searching in Names..." (the message is continuously updated with the name of the application currently being searched). Other applications use the title and message text differently. When receiving e-mail, for example, the first line could display the current phase of the operation and the second line could display specific information being used in that phase. [Figure 2-20](#page-65-0) illustrates.  
The title should be in the bold style of the system font, and the message should be in the plain style of the system font. The icon size should correspond to the title height. On an Apple MessagePad, use 9-point text for the title and 9-point text for the message.  
Auxiliary Views **2-21**  
**Figure 2-20** A sequence of status messages traces the steps of an operation  
<span id="page-65-0"></span>![](images/_page_65_Figure_3.jpeg)  
#### Progress Indicator 2  
The progress indicator, if present in a status slip, can take different forms. It can be a simple "barber pole" gauge, which animates a set of diagonal stripes while the operation progresses but does not indicate how much of the operation has been completed. Alternatively, if it's possible to quantify the progress of the operation that's underway, then a status slip should include a progress gauge that indicates relative completeness of the current operation as a shaded portion of the entire gauge. [Figure 2-21](#page-66-0) shows two examples of progress gauges.  
<span id="page-66-0"></span>**Figure 2-21** A gauge in a status slip measures elapsing progress  
![](images/_page_66_Picture_3.jpeg)  
![](images/_page_66_Picture_4.jpeg)  
#### Close, Stop, or Cancel 2  
A status slip usually has a large Close box and a Stop button or Cancel button. Tapping the Stop button or Cancel button halts the operation that's in progress. If halting the operation takes more than a few seconds, the application should change the status message to "Stopping..." or "Canceling..." while halting is in progress.  
Make an effort to choose the button—Stop or Cancel—that most accurately describes the action that will occur. *Stop* suggests halting an operation that has already begun. In contrast, *Cancel* suggests a user has decided to take a different tack—without any action having taken place.  
Tapping a status slip's Close box closes the status slip but does not stop the operation it was monitoring. To alert the user that an operation is in progress, the application registers the operation with the system's Notify service, causing the Notify button to blink at the top of the screen (see ["Notify Button](#page-243-0)  [and Picker" on page 8-2\)](#page-243-0). The user can open the status slip by tapping the Notify button and choosing the operation from the Notify picker that pops up. If an application completes an ongoing operation while the status slip is closed, the application must unregister the operation so the Notify service will remove it from the Notify picker.  
Close boxes and text buttons are covered in [Chapter 3, "Controls."](#page-94-0)  
Auxiliary Views **2-23**  
#### <span id="page-67-0"></span>User Decision 2  
Besides reporting on the progress of an ongoing operation, a status slip can report a condition that requires a user to choose one of two alternatives. This type of status slip contains an icon, a message of up to three lines, and two text buttons. This type of status slip does not have a progress indicator, Stop button, Cancel button, or Close box. Figure 2-22 shows an example of a status slip that demands a user decision.  
**Figure 2-22** A status slip can report a condition that demands a user decision  
![](images/_page_67_Picture_5.jpeg)