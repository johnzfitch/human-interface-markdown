<!-- Chunk 262 | Source: 2001 Aqua Human Interface Guidelines.pdf | Est. Tokens: 483 -->
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