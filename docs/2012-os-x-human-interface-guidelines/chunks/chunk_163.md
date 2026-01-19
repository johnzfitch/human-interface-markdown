<!-- Chunk 163 | Source: 2012 OS X Human Interface Guidelines.pdf | Est. Tokens: 1388 -->
OS X provides many small, black imagesintended for use primarily in toolbar controls. These images are known astemplate imagesin AppKit, because they are expected to receive additional processing by an NSButtonCell object before being displayed. The additional processing can, for example, make such an image look different when its control is pressed. Because these images require the presence of a bounding box (which is supplied by the control), they are not as useful for standalone buttons or free-standing toolbar icons. Instead, see ["System-Provided](#page-322-0) Images for Use as Standalone Buttons" (page 323) for images you can use as standalone buttons, and see ["System-Provided](#page-323-0) Images for Use as Toolbar Items" (page 324) for images you can use as free-standing toolbar icons.  
As with all system-provided images, you should avoid using the template images to represent actions other than those they are designed for. Table B-1 shows the standard template images available in OS X, along with the actions they represent and their names.  
<span id="page-321-0"></span>**Table B-1** Template images that represent common tasks  
| Image | Meaning                                                                                               | Constant name                      |
|-------|-------------------------------------------------------------------------------------------------------|------------------------------------|
|       | View<br>in<br>Quick<br>Look                                                                           | NSImageNameQuickLookTemplate       |
|       | Connect<br>via<br>Bluetooth                                                                           | NSImageNameBluetoothTemplate       |
|       | Open<br>iChat<br>Theater                                                                              | NSImageNameIChatTheaterTemplate    |
|       | View<br>in<br>a<br>slide<br>show                                                                      | NSImageNameSlideshowTemplate       |
|       | Action<br>pop-up<br>menu                                                                              | NSImageNameActionTemplate          |
|       | Create<br>smart<br>item                                                                               | NSImageNameSmartBadgeTemplate      |
|       | Share<br>menu                                                                                         | NSImageNameShareTemplate           |
|       | View<br>objects<br>as<br>icons                                                                        | NSImageNameIconViewTemplate        |
|       | View<br>objects<br>in<br>a<br>list                                                                    | NSImageNameListViewTemplate        |
|       | View<br>objects<br>in<br>columns                                                                      | NSImageNameColumnViewTemplate      |
|       | View<br>objects<br>in<br>a<br>Cover<br>Flow<br>mode<br>*                                              | NSImageNameFlowViewTemplate        |
|       | View<br>the<br>path<br>of<br>the<br>object                                                            | NSImageNamePathTemplate            |
|       | Unlock<br>the<br>object<br>(this<br>image<br>indicates<br>the<br>object<br>is<br>currently<br>locked) | NSImageNameLockLockedTemplate      |
|       | Lock<br>the<br>object<br>(this<br>image<br>indicates<br>the<br>object<br>is<br>currently<br>unlocked) | NSImageNameLockUnlockedTemplate    |
|       | Go<br>to<br>the<br>right<br>or<br>go<br>forward                                                       | NSImageNameGoRightTemplate         |
|       | Go<br>to<br>the<br>left<br>or<br>go<br>back                                                           | NSImageNameGoLeftTemplate          |
|       | Add<br>an<br>item<br>(to<br>a<br>list,<br>for<br>example)                                             | NSImageNameAddTemplate             |
|       | Remove<br>an<br>item<br>(from<br>a<br>list,<br>for<br>example)                                        | NSImageNameRemoveTemplate          |
|       | Enter<br>full-screen<br>mode<br>(deprecated<br>)                                                      | NSImageNameEnterFullScreenTemplate |
|       | Exit<br>full-screen<br>mode<br>(deprecated<br>)                                                       | NSImageNameExitFullScreenTemplate  |  
| Image | Meaning                                                              | Constant name                   |
|-------|----------------------------------------------------------------------|---------------------------------|
|       | Stop<br>progress<br>on<br>the<br>current<br>process                  | NSImageNameStopProgressTemplate |
|       | Refresh<br>the<br>current<br>view<br>or<br>restart<br>the<br>process | NSImageNameRefreshTemplate      |  
\*OS X does not provide programming interfaces that support adding a custom cover flow experience to your app.  
**Note:** The NSImageNameEnterFullScreenTemplate and  
NSImageNameExitFullScreenTemplate images are deprecated. If windows in your app can go full screen, be sure to use the appropriate full-screen programming interfaces so that the correct button gets added to the title bar. For an overview of these programming interfaces,see "Implementing the Full-Screen Experience". To learn more about how to support the experience of a full-screen window, see "Going Full [Screen"](#page-175-0) (page 176).