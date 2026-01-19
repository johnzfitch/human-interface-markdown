<!-- Chunk 122 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 195 -->
A **network activity indicator** appears in the status bar and shows that network activity is occurring.  
![](images/_page_185_Picture_5.jpeg)  
**APINote:** In your code, use the UIApplication method networkActivityIndicatorVisible to control the indicator's visibility.  
The network activity indicator:  
- Spins in the status bar while network activity proceeds and disappears when network activity stops
- Doesn't allow user interaction  
<span id="page-185-1"></span>Display the network activity indicator to provide feedback when your app accesses the network for more than a couple of seconds. If the operation finishes sooner than that, you don't have to show the network activity indicator, because the indicator is likely to disappear before users notice its presence.