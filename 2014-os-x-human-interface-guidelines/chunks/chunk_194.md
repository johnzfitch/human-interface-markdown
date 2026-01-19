<!-- Chunk 194 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 1255 -->
OS X provides many template images intended for use primarily in toolbar controls. Because these images require the presence of a bounding box (which issupplied by the control), they are not as useful forstandalone buttons or free-standing toolbar icons. Instead,see [System-Provided](#page-331-0) Imagesfor Use as Standalone Buttons (page 332) for images you can use as standalone buttons, and see [System-Provided](#page-333-0) Images for Use as Toolbar [Items](#page-333-0) (page 334) for images you can use as free-standing toolbar icons.  
<span id="page-329-1"></span>As with all system-provided images, avoid using the template images to represent actions other than those they are designed for. Table 74-1 shows the standard template images available in OS X, along with the actions they represent and their names.  
**Table 74-1** Template images that represent common tasks  
| Image | Meaning                     | Constant name                |
|-------|-----------------------------|------------------------------|
|       | View<br>in<br>Quick<br>Look | NSImageNameQuickLookTemplate |
|       | Connect<br>via<br>Bluetooth | NSImageNameBluetoothTemplate |  
| Image | Meaning                                                                                               | Constant name                   |
|-------|-------------------------------------------------------------------------------------------------------|---------------------------------|
|       | View<br>in<br>a<br>slide<br>show                                                                      | NSImageNameSlideshowTemplate    |
|       | Action<br>pop-up<br>menu                                                                              | NSImageNameActionTemplate       |
|       | Create<br>smart<br>item                                                                               | NSImageNameSmartBadgeTemplate   |
|       | Share<br>menu                                                                                         | NSImageNameShareTemplate        |
|       | View<br>objects<br>as<br>icons                                                                        | NSImageNameIconViewTemplate     |
|       | View<br>objects<br>in<br>a<br>list                                                                    | NSImageNameListViewTemplate     |
|       | View<br>objects<br>in<br>columns                                                                      | NSImageNameColumnViewTemplate   |
|       | View<br>objects<br>in<br>a<br>Cover<br>Flow<br>mode<br>*                                              | NSImageNameFlowViewTemplate     |
|       | View<br>the<br>path<br>of<br>the<br>object                                                            | NSImageNamePathTemplate         |
|       | Unlock<br>the<br>object<br>(this<br>image<br>indicates<br>the<br>object<br>is<br>currently<br>locked) | NSImageNameLockLockedTemplate   |
|       | Lock<br>the<br>object<br>(this<br>image<br>indicates<br>the<br>object<br>is<br>currently<br>unlocked) | NSImageNameLockUnlockedTemplate |
|       | Go<br>to<br>the<br>right<br>or<br>go<br>forward                                                       | NSImageNameGoRightTemplate      |
|       | Go<br>to<br>the<br>left<br>or<br>go<br>back                                                           | NSImageNameGoLeftTemplate       |  
| Image | Meaning                                                              | Constant name                          |
|-------|----------------------------------------------------------------------|----------------------------------------|
|       | Add<br>an<br>item<br>(to<br>a<br>list,<br>for<br>example)            | NSImageNameAddTemplate                 |
|       | Remove<br>an<br>item<br>(from<br>a<br>list,<br>for<br>example)       | NSImageNameRemoveTemplate              |
|       | Enter<br>full-screen<br>mode<br>(deprecated<br>)                     | NSImageNameEnterFull<br>ScreenTemplate |
|       | Exit<br>full-screen<br>mode<br>(deprecated<br>)                      | NSImageNameExitFullScreenTemplate      |
|       | Stop<br>progress<br>on<br>the<br>current<br>process                  | NSImageNameStopProgressTemplate        |
|       | Refresh<br>the<br>current<br>view<br>or<br>restart<br>the<br>process | NSImageNameRefreshTemplate             |  
<sup>\*</sup>OS X does not provide programming interfaces that support adding a custom cover flow experience to your app.  
**Note:** The NSImageNameEnterFullScreenTemplate and  
NSImageNameExitFullScreenTemplate images are deprecated. If windows in your app can go full screen, be sure to use the appropriate full-screen programming interfaces so that the correct button gets added to the title bar. For an overview of these programming interfaces,see Implementing the Full-Screen Experience in *Mac App Programming Guide* . To learn more about how to support the experience of a full-screen window, see [Full-Screen](#page-133-0) Windows (page 134).