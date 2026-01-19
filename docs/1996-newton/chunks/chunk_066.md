<!-- Chunk 66 | Source: 1996 Newton 2.0 User Interface Guidelines.pdf | Est. Tokens: 395 -->
Your application determines the size of its views. It should base its view sizes on the screen size of the Newton device on which it is running, since Newton screens can come in a wide range of sizes. For example, a container view that fills the screen on an Apple MessagePad 120 (which measures 240 × 320 pixels) will not fill the screen on a MessagePad 100 (which measures 240 × 336 pixels). The same image would be too tall to fit on a screen of a MessagePad 120 that a user has rotated to the wide orientation (320 × 240 pixels). An application can dynamically determine the screen size, and based on that information can calculate appropriate view sizes. An application may also need to adjust view layouts according to the aspect ratio of the screen. [Figure 2-27](#page-78-0) shows how the built-in Calculator adjusts its size and layout when a user rotates the display.  
<span id="page-78-0"></span>**Figure 2-27** Dynamically adjust a view's position, size, and layout to fit the screen  
![](images/_page_78_Picture_3.jpeg)  
Regular orientation on a MessagePad 120  
An application may grow or shrink one of its views in response to user actions, but users should not be allowed to change view size directly. Do not allow users to resize a view by dragging a corner of it. Figure 2-28 shows how the Filing slip changes size after a user creates a new folder.  
**Figure 2-28** A view may change size in response to user actions  
![](images/_page_78_Figure_7.jpeg)  
1. Before creating a new folder  
2. After a user creates the Quotes folder  
How Views Work **2-35**