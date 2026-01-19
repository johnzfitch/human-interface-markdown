<!-- Chunk 96 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 800 -->
For products with complex setup procedures, a setup assistant can be helpful. A setup assistant is a small application that guides users through the setup options. You store setup assistants in a location where your application can find them, such as inside your application bundle.  
<span id="page-87-3"></span><span id="page-87-1"></span>Your application should open a setup assistant automatically whenever appropriate—when the system detects a new hardware device or the first time the user opens your application, for example. Ideally, the user should use the assistant only once.  
The assistant application's icon should be a combination of the setup assistant icon with your application's icon superimposed as a badge in the lower-right corner, as shown in Figure 7-1.  
**Figure 7-1** Examples of assistant icons  
![](images/_page_87_Picture_14.jpeg)  
![](images/_page_87_Picture_15.jpeg)  
![](images/_page_87_Picture_16.jpeg)  
Figure 7-2 shows the layout for a sample setup assistant window.  
<span id="page-88-0"></span>**Figure 7-2** A setup assistant window  
![](images/_page_88_Picture_3.jpeg)  
Keep the following guidelines in mind when designing a setup assistant:  
- While the assistant is active, display only the application menu (containing About and Quit items) and the Edit menu (containing standard items to assist users in entering text). Don't provide a Help menu (or a Help button); the setup assistant *is* help.
- Provide Go Back and Continue buttons for navigation.
- The assistant window title bar should contain a dimmed close button, an available minimize button, and a dimmed zoom button.
- Title the first pane "Introduction." This pane should explain the purpose of subsequent panes.
- Title the last pane "Conclusion." This pane should tell users what changes were made to their system and how to modify those settings. This pane should have a default Done button and a dimmed Go Back button.
- In most cases, it's best to ask only one question per pane.
- Whenever appropriate, use selection controls that do not support the empty selection to avoid having to ask for the same information more than once.
- Avoid displaying an asterisk or custom icon next to each required text field. Instead, check for empty text fields when the user clicks Continue. If there are any, return to the current pane and display the asterisk or other marker next to the empty text fields.
- As much as possible, use system applications and services to provide intelligent default choices to the user. For example, you should use Bonjour to determine an appropriate IP address.  
- Limit the total number of questionsto the minimum required to get the job done. The bestsetup assistant gets users up and running as soon as possible, allowing the main application to present the user with opportunities to refine preferences and settings.
- Provide relevant feedback when appropriate. If needed, you can display a progress bar next to the Go Back button (aligning the progress bar's left edge with the left edge of the pane).
- <span id="page-89-2"></span>● Don't fill the entire screen; users should be able to access other parts of their system while the assistant is open.