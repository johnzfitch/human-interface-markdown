<!-- Chunk 192 | Source: 2006-10 Apple Human Interface Guidelines.pdf | Est. Tokens: 2115 -->
<span id="page-142-2"></span>Table 11-1 shows the standard cursors and explains when to use each. The "API information" column gives the constants to implement them in Carbon or Cocoa.  
**Table 11-1** Standard cursors in Mac OS X  
| Cursor             | Use                                                                                                                                                                        | API information                                                    |
|--------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------|
| Arrow              | Menu bar, desktop, scroll bar, resize control, title bar,<br>close button, zoom button, minimize button, other<br>controls.                                                | Carbon: kThemeArrowCursor<br>Cocoa:arrowCursor                     |
| Contextual<br>menu | Indicates the user can open a contextual menu for an<br>item. Shown when the user presses the Control key<br>while the cursor is over an object with a contextual<br>menu. | Carbon:kThemeContextual<br>MenuArrowCursor<br>Cocoa: Not available |
| Alias              | Indicates the drag destination will have an alias for<br>the original object (the original object will not be<br>moved).                                                   | Carbon:kThemeAliasArrow<br>Cursor<br>Cocoa: Not available          |  
Standard Cursors **143**  
| Cursor           | Use                                                                                                                                                                 | API information                                                 |
|------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------|
| Poof             | Indicates that the proxy object being dragged will go<br>away, without deleting the original object, if the<br>mouse button is released. Used onlyfor proxyobjects. | Carbon:kThemePoofCursor<br>Cocoa:disappearingItemCursor         |
| Copy             | Indicates that the drag destination will have a copy<br>of the original object (the original object will not be<br>moved).                                          | Carbon:kThemeCopyArrowCursor<br>Cocoa: Not available            |
| Not<br>allowed   | Indicates an invalid drag destination.                                                                                                                              | Carbon:kThemeNotAllowed<br>Cursor<br>Cocoa: Not available       |
| I beam           | Selecting and inserting text.                                                                                                                                       | Carbon:kThemeIBeamCursor<br>Cocoa:IBeamCursor                   |
| Crosshair        | Precise rectangular selection, especially useful for<br>graphics objects.                                                                                           | Carbon:kThemeCrossCursor<br>Cocoa:crosshairCursor               |
| Pointing<br>hand | URL links.                                                                                                                                                          | Carbon:kThemePointing<br>HandCursor<br>Cocoa:pointingHandCursor |
| Open<br>hand     | Indicates that an item can be manipulated within its<br>containing view.                                                                                            | Carbon:kThemeOpenHandCursor<br>Cocoa:openHandCursor             |
| Closed<br>hand   | Pushing, sliding, or adjusting an object within a<br>containing view.                                                                                               | Carbon:kThemeClosed<br>HandCursor<br>Cocoa:closedHandCursor     |
| Move<br>left     | Moving or resizing an object, usually a pane splitter,<br>to the left. Use when the user can move the object<br>only in the indicated direction.                    | Carbon:kThemeResize<br>LeftCursor<br>Cocoa:resizeLeftCursor     |
| Move<br>right    | Moving or resizing an object, usually a pane splitter,<br>to the right. Use when the user can move the object<br>only in the indicated direction.                   | Carbon:kThemeResize<br>RightCursor<br>Cocoa:resizeRightCursor   |  
| Cursor          | Use                                                                                                       | API information                        |
|-----------------|-----------------------------------------------------------------------------------------------------------|----------------------------------------|
| Move<br>left or | Moving or resizing an object, usually a pane splitter,<br>to the left or the right.                       | Carbon:kThemeResizeLeft<br>RightCursor |
| right           |                                                                                                           | Cocoa:resizeLeftRightCursor            |
| Move            | Moving or resizing an object, usually a pane splitter,                                                    | Carbon:kThemeResizeUpCursor            |
| up              | upward. Use when the user can move the object only<br>in the indicated direction.                         | Cocoa:resizeUpCursor                   |
| Move<br>down    | Moving or resizing an object, usually a pane splitter,<br>downward. Use when the user can move the object | Carbon:kThemeResize<br>DownCursor      |
|                 | only in the indicated direction.                                                                          | Cocoa:resizeDownCursor                 |
| Move<br>up or   | Moving or resizing an object, usually a pane splitter,<br>either upward or downward.                      | Carbon:kThemeResizeUp<br>DownCursor    |
| down            |                                                                                                           | Cocoa:resizeUpDownCursor               |
|                 |                                                                                                           |                                        |
|                 |                                                                                                           |                                        |  
Manyof the progress indicator cursors from Mac OS 9 are still supported in Mac OS X, butyou should not use them for new development. Figure 11-1 shows cursors you shouldn't use in Mac OS X.  
Standard Cursors **145 2006-10-03 | © 1992, 2001-2003, 2006 Apple Computer, Inc. All Rights Reserved.**  
<span id="page-145-0"></span>**Figure 11-1** Mac OS 9 cursors that you shouldn't use on Mac OS X  
![](images/_page_145_Picture_3.jpeg)  
<span id="page-145-3"></span><span id="page-145-1"></span>Instead of using a Mac OS 9 cursor, consider using a progress indicator. The use of an asynchronous progress indicator is shown in Figure 11-2. One benefit of this is that it can be seen whether the application is in the foreground orthe background. You could also displaya progress bar. See ["Progress](#page-260-0) [Indicators"](#page-260-0) (page 261) for more information on using these controls.  
**Figure 11-2** Use of an asynchronous progress indicator  
![](images/_page_145_Picture_6.jpeg)  
<span id="page-145-2"></span>The spinning wait cursor (see Figure 11-3) is displayed automatically by the window server when an application cannot handle all of the events it receives. If an application does not respond for longer than 2 seconds, the spinningwait cursor appears. You should tryto avoid situations in your application in which the spinning wait cursor will be displayed. The Spin Control application provided with Xcode can help you eliminate code that is causing this cursor.  
**Figure 11-3** Spinning wait cursor  
![](images/_page_145_Picture_9.jpeg)  
Cursors  
**Carbon:** Use the Carbon Events Manager instead of the WaitNextEvent model. Avoid polling the mouse button or keyboard. See Appearance.h for functions related to cursors.  
**Cocoa:** Use NSCursor methods to display cursors.