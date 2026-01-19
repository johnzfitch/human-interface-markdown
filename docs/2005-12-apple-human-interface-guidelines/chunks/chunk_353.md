<!-- Chunk 353 | Source: 2005-12 Apple Human Interface Guidelines.pdf | Est. Tokens: 187 -->
Use a **relevance indicator**to display the relevance of search results as shown in Figure 14-38. Relevance indicators should be a part of a list view.  
Controls  
<span id="page-256-4"></span><span id="page-256-1"></span>**Figure 14-38** Relevance indicator  
![](images/_page_256_Picture_3.jpeg)  
**Carbon:** Relevance indicators are available in the Controls palette of Interface Builder. To create them programmatically, use CreateRelevanceBarControl in the Control Manager, or DrawThemeTrack in the Appearance Manager.  
**Cocoa:** Relevance indicators are available in Interface Builder in the Controls palette. Start with a discrete level indicator and change its style to Relevancy in the Attributes pane of the NSLevelIndicator Inspector.