<!-- Chunk 182 | Source: 2004-05 Apple Human Interface Guidelines.pdf | Est. Tokens: 208 -->
Use a **relevance indicator** to display the relevance of search results as shown in Figure 10-36. Relevance indicators should be a part of a list view.  
<span id="page-185-5"></span><span id="page-185-2"></span>**Figure 10-36** Relevance indicator  
![](images/_page_185_Picture_3.jpeg)  
**Carbon:** Relevance indicators are available in the Controls palette of Interface Builder. To create them programmatically, use CreateRelevanceBarControl in the Control Manager, or DrawThemeTrack in the Appearance Manager.  
**Cocoa:** Relevance indicators are not available as a standard control.  
#### <span id="page-185-3"></span>Relevance Indicator Specifications  
**Figure 10-37** Relevance indicator states  
![](images/_page_185_Picture_8.jpeg)  
■ **Height:** The x-height of the font in the list of which the indicator is a part