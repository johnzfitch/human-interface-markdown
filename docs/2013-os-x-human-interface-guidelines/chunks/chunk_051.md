<!-- Chunk 51 | Source: 2013 OS X Human Interface Guidelines.pdf | Est. Tokens: 1420 -->
OS X providesseveralstandard pointersthat provide well-defined feedback to users. It'simportant to use these pointers correctly because users already know what they mean.  
**Use standard pointers according to their intended purpose.** OS X users are accustomed to the meaning of the pointers shown in Table 3-1. If you change the meaning of a standard pointer, users aren't able to predict the results of their actions.  
<span id="page-55-1"></span>**Table 3-1** Standard pointers in OS X  
| Pointer            | Meaning                                                                                                                                                                                                                           |
|--------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Arrow              | The<br>user<br>can<br>activate<br>the<br>control<br>or<br>switch<br>to<br>the<br>area.                                                                                                                                            |
| Contextual<br>menu | A<br>contextual<br>menu<br>is<br>available<br>for<br>an<br>item.<br>Shown<br>when<br>the<br>user<br>presses<br>the<br>Control<br>key<br>while<br>the<br>pointer<br>is<br>over<br>an<br>object<br>with<br>a<br>contextual<br>menu. |
| Alias              | The<br>drag<br>destination<br>will<br>have<br>an<br>alias<br>for<br>the<br>original<br>object<br>(the<br>original<br>object<br>will<br>not<br>moved).                                                                             |
| Poof               | The<br>proxy<br>object<br>being<br>dragged<br>will<br>go<br>away,<br>without<br>deleting<br>the<br>original<br>object,<br>when<br>the<br>user<br>releases<br>the<br>drag.<br>Used<br>only<br>for<br>proxy<br>objects.             |
| Copy               | The<br>drag<br>destination<br>will<br>have<br>a<br>copy<br>of<br>the<br>original<br>object<br>(the<br>original<br>object<br>is<br>not<br>moved).                                                                                  |  
| Pointer                  | Meaning                                                                                                          |
|--------------------------|------------------------------------------------------------------------------------------------------------------|
| Not<br>allowed           | An<br>invalid<br>drag<br>destination.                                                                            |
| I beam                   | Selection<br>and<br>insertion<br>of<br>text<br>is<br>available.                                                  |
| Crosshair                | Precise<br>rectangular<br>selection<br>is<br>available.                                                          |
| Pointing<br>hand         | The<br>content<br>is<br>a<br>URL<br>link.                                                                        |
| Open<br>hand             | The<br>item<br>can<br>be<br>manipulated<br>within<br>its<br>containing<br>view.                                  |
| Closed<br>hand           | Pushing,<br>sliding,<br>or<br>adjusting<br>an<br>object<br>within<br>a<br>containing<br>view<br>is<br>occurring. |
| Move<br>left             | The<br>object<br>can<br>only<br>be<br>moved<br>or<br>resized<br>to<br>the<br>left.                               |
| Move<br>right            | The<br>object<br>can<br>only<br>be<br>moved<br>or<br>resized<br>to<br>the<br>right.                              |
| Move<br>left or<br>right | The<br>object<br>can<br>be<br>moved<br>or<br>resized<br>to<br>the<br>left<br>or<br>the<br>right.                 |
| Move<br>up               | The<br>object<br>can<br>only<br>be<br>moved<br>or<br>resized<br>upward.                                          |  
| Pointer               | Meaning                                                                           |
|-----------------------|-----------------------------------------------------------------------------------|
| Move<br>down          | The<br>object<br>can<br>only<br>be<br>moved<br>or<br>resized<br>downward.         |
| Move<br>up or<br>down | The<br>object<br>can<br>be<br>moved<br>or<br>resized<br>upward<br>or<br>downward. |  
The spinning wait cursor (shown below) is also standard, but it is displayed automatically by the window server when an app can't handle all of the events it receives. In general, if an app does not respond for about 2 to 4 seconds, the spinning wait cursor appears. If the app continues to be unresponsive, users often react by force-quitting it.  
![](images/_page_57_Picture_3.jpeg)  
**Create a custom pointer cautiously.** Before you design a custom pointer for your app (especially a custom version of a standard pointer), be sure the new pointer actually improves the usability of your app and doesn't confuse users. If you've determined that you need a custom pointer, follow these guidelines as you design it:  
- Your design needs to make clear where the hot spot of the pointer is (briefly, a pointer's **hot spot** is the part of the pointer that must be positioned over an onscreen object before clicking has an effect).
- <span id="page-57-0"></span>● If your custom pointer is a version of a standard pointer, you also need to create custom versions of related pointers. For example, if you create a custom version of the arrow pointer you also need to create custom versions of the related arrow pointers, such as copy, move, alias, and poof.