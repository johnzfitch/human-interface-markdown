<!-- Chunk 91 | Source: 2001 Aqua Human Interface Guidelines (Preliminary).pdf | Est. Tokens: 477 -->
**Progress indicators**, also called **progress bars**, are used to inform the user about the status of lengthy operations. There are two types:  
- <span id="page-106-5"></span>■ **Determinate:** Use when the full length of an operation can be determined. The bar moves from left to right, and the user can see how much of the process has been completed. You might use a determinate progress indicator to show the progress of a file conversion.
- <span id="page-106-6"></span>■ **Indeterminate:** Use when the duration of a process can't be determined. This indicator displays a spinning striped cylinder to indicate an ongoing process. You might use an indeterminate progress indicator to let the user know that the application is attempting a dialup communication connection, for example, when there's no way to accurately determine how long it will take to complete.  
#### <span id="page-107-1"></span>Controls and Layout Guidelines  
**Figure 7-24** Progress bars  
![](images/_page_107_Picture_3.jpeg)  
If an indeterminate process reaches a point where its duration can be determined, switch to a determinate progress indicator.  
When the process being performed can be interrupted, the progress dialog should contain a Cancel button (and support the Escape key). If interrupting the process will result in possible side effects, the button should say Stop instead of Cancel.  
The progress bar should fill in completely before it is dismissed.  
In Mac OS X, the kernel environment detects when your application doesn't respond to events for 2 seconds and automatically displays the color wheel cursor. Avoid using Command-period to stop operations; checking for Command-period makes the system think your application is responding to events rather than being busy.  
**Note:** In Mac OS X, don't use a progress bar to display relevance; use the new relevance control instead (available in Carbon).