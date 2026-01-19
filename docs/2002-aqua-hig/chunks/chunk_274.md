<!-- Chunk 274 | Source: 2002 Aqua Human Interface Guidelines.pdf | Est. Tokens: 575 -->
For products with complex setup procedures, a **setup assistant,** a small application that guides users through the setup options, can be helpful.  
You can open a setup assistant automatically when appropriate—when the system detects a new hardware device or the first time the user opens your application, for example. Ideally, the user should use the assistant only once. Store the assistant in your application's Utilities folder.  
<span id="page-240-4"></span>For an icon, use the setup assistant icon with an application badge superimposed in the lower-right corner, as shown in Figure 14-2.  
<span id="page-240-1"></span>**Figure 14-2** The icon for AirPort Setup Assistant  
![](images/_page_240_Picture_11.jpeg)  
Setup Assistants **241**  
<span id="page-241-0"></span>Figure 14-3 shows the layout for a sample setup assistant window. Notice that the text is flush left within the inset area, and controls are indented.  
**Figure 14-3** A typical setup assistant pane  
![](images/_page_241_Picture_4.jpeg)  
Keep the following guidelines in mind when designing a setup assistant:  
- While the assistant is active, display only the application menu, containing About and Quit items, and the Edit menu, containing standard items to assist users in entering text. Don't provide a Help menu (or a help button); the setup assistant *is* help.
- Provide Go Back and Continue buttons for navigation.
- The assistant window title bar should contain a dimmed close button, an available minimize button, and a dimmed zoom button.
- Title the first pane "Introduction." This pane should explain the purpose of subsequent panes.  
#### **CHAPTER 14**  
#### User Help and Assistants  
- Title the last pane "Conclusion." This pane should tell users what changes were made to their system and how to modify these settings. This pane should have a default Done button and a dimmed Go Back button.
- In most cases, it's best to ask only one question per pane.
- Provide relevant feedback when appropriate. If needed, you can display a progress bar to the left of the Go Back button (the left edge aligned with the text box).
- <span id="page-242-0"></span>■ Don't fill the entire screen; users should be able to access other parts of their system while the assistant is open.  
Setup Assistants **243**