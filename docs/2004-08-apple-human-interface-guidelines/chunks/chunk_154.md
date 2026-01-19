<!-- Chunk 154 | Source: 2004-08 Apple Human Interface Guidelines.pdf | Est. Tokens: 361 -->
Mac OS X includes standard windows for users to select fonts or colors. If you need a way for users to set fonts or colors, use these standard windows instead of making your own. In this way, users don't have to learn a new way to accomplish a familiar task.  
By implementing these windows, you get the correct utility window behavior. These windows are discussed in *Apple Software Design Guidelines*.  
<span id="page-132-5"></span><span id="page-132-3"></span><span id="page-132-2"></span><span id="page-132-0"></span>A **dialog** is a window designed to elicit a response from the user. Many dialogs—the Print dialog, for example—permit the user to provide many responses at one time.  
**Alerts** are dialogs that appear when the system or an application needs to communicate information to the user. Alerts provide messages about error conditions or warn users about potentially hazardous situations or actions.  
For information about using the keyboard to interact with dialogs, see ["Keyboard Focus and](#page-30-0) [Navigation"](#page-30-0) (page 31).  
For specific design information on how to lay out dialogs, see ["Layout Examples"](#page-202-3) (page 203).  
**Carbon:** For implementation information, see *Handling Carbon Windows and Controls* and *Dialog Manager Reference* in Carbon User Experience Documentation.  
**Cocoa:** See *Dialogs and Special Panels* and *Windows and Panels* in Cocoa User Experience Documentation.