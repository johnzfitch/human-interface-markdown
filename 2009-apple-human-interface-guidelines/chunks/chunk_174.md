<!-- Chunk 174 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 956 -->
Mac OS X v10.5 and later provides many small, black images intended for use primarily in rectangular-style toolbar controls. These images, some of which are shown in [Figure](#page-154-1) 11-27 (page 155), are known as template images in Application Kit, because they are expected to receive additional processing by an NSButtonCell object before being displayed. The additional processing can, for example, make such an image look different when its control is pressed. Because these images require the presence of a bounding box (which is supplied by the control), they are not as useful for standalone buttons or free-standing toolbar icons. Instead, see ["System-Provided](#page-156-0) Images for Use as Standalone Buttons" (page 157) for images you can use as standalone buttons, and see ["System-Provided](#page-157-0) Images for Use as Toolbar Items" (page 158) for images you can use as free-standing toolbar icons.  
<span id="page-155-1"></span>As with all system-provided images, you should avoid using the template images to represent actions other than those they are designed for. Table 11-1 shows the standard template images available in Mac OS X v10.5 and later, along with the actions they represent and their names.  
**Table 11-1** Template images that represent common tasks  
| Image | Meaning                           | Constant name                   |
|-------|-----------------------------------|---------------------------------|
|       | View in Quick Look                | NSImageNameQuickLookTemplate    |
|       | Connect via Bluetooth             | NSImageNameBluetoothTemplate    |
|       | Open iChat Theater                | NSImageNameIChatTheaterTemplate |
|       | View in a slide show              | NSImageNameSlideshowTemplate    |
|       | Action pop-up menu                | NSImageNameActionTemplate       |
|       | Create smart item                 | NSImageNameSmartBadgeTemplate   |
|       | View objects as icons             | NSImageNameIconViewTemplate     |
|       | View objects in a list            | NSImageNameListViewTemplate     |
|       | View objects in columns           | NSImageNameColumnViewTemplate   |
|       | View objects in a Cover Flow mode | NSImageNameFlowViewTemplate     |
|       | View the path of the object       | NSImageNamePathTemplate         |  
| Image | Meaning                                                                    | Constant name                      |
|-------|----------------------------------------------------------------------------|------------------------------------|
|       | Unlock the object (this image indicates the object<br>is currently locked) | NSImageNameLockLockedTemplate      |
|       | Lock the object (this image indicates the object is<br>currently unlocked) | NSImageNameLockUnlockedTemplate    |
|       | Go to the right or go forward                                              | NSImageNameGoRightTemplate         |
|       | Go to the left or go back                                                  | NSImageNameGoLeftTemplate          |
|       | Add an item (to a list, for example)                                       | NSImageNameAddTemplate             |
|       | Remove an item (from a list, for example)                                  | NSImageNameRemoveTemplate          |
|       | Enter full-screen mode                                                     | NSImageNameEnterFullScreenTemplate |
|       | Exit full-screen mode                                                      | NSImageNameExitFullScreenTemplate  |
|       | Stop progress on the current process                                       | NSImageNameStopProgressTemplate    |
|       | Refresh the current view or restart the process                            | NSImageNameRefreshTemplate         |