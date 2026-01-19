<!-- Chunk 405 | Source: 2008-06 Apple Human Interface Guidelines.pdf | Est. Tokens: 284 -->
<span id="page-310-2"></span><span id="page-310-0"></span>A **relevance indicator** is a style of level indicator that displays the relevance of items, such as search results. For example, Preview uses relevance indicators to show users the relevance of search results, as shown in Figure 15-67.  
**Figure 15-67** A relevance indicator shows the relevance of each item in a list  
![](images/_page_310_Picture_10.jpeg)  
<span id="page-311-2"></span>Some of the states a relevance indicator can display are shown in Figure 15-68.  
**Figure 15-68** Relevance indicator states  
![](images/_page_311_Figure_4.jpeg)  
Relevance indicators are especially useful as part of a list or table view. Thisis because relevance as a quantity is easier for users to understand when it is shown in comparison with the relevance of several items.  
Relevance indicators are available in Interface Builder. Start with a discrete level indicator and change its style to Relevancy in the Attributes pane of the inspector. To create one using Application Kit programming interfaces, use the NSLevelIndicator class with style NSRelevancyLevelIndicatorStyle.