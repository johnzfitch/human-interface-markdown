<!-- Chunk 259 | Source: 2004-08 Apple Human Interface Guidelines.pdf | Est. Tokens: 343 -->
<span id="page-238-3"></span><span id="page-238-2"></span>The size of the tab views has changed between Mac OS X version 10.2 (Jaguar) and Mac OS X version 10.3 (Panther). This section discuses how that size difference may affect your applications.  
If you are supporting only Mac OS X v10.3 and later, then you do not need to do anything. Follow the guidelines in ["Tab Views"](#page-194-1) (page 195).  
If you need to support Mac OS X v10.2 (or earlier) in addition to Mac OS X v10.3, then you need to consider the differences.  
<span id="page-238-1"></span>The Mac OS X v10.2 tabs were 29 pixels high from the top of the tab to the bottom of the bar under the tab. The Mac OS X v10.3 tabs are only 20 pixels high. This means that if you have designed your user interface elements for Mac OS X v10.2, there will be an additional space of 4 pixels under the tabs when viewed in Mac OS X v10.3 and a space of 5 pixels above.  
**Figure B-1** Tab view differences  
![](images/_page_238_Picture_7.jpeg)  
Considering your users, you must decide whether to redesign your interface so that it does not use tabs, or to allow the new spacing and adhere to the Mac OS X v10.2 specification for spacing around the tab views. If you decide not to use tabs, one option is to use a toolbar for switching panes.  
#### **APPENDIX B**  
Tab View Differences Between Mac OS X Versions