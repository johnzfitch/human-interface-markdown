<!-- Chunk 196 | Source: 2011 iOS Human Interface Guidelines.pdf | Est. Tokens: 672 -->
iOS uses two sizes of document icons for iPad applications: 64 x 64 pixels and 320 x 320 pixels. It's a good idea to create both sizes so that your document icons look good in different contexts.  
For both sizes, the overall dimensions include specific amounts of padding, leaving a smaller "safe zone" for your artwork. It's essential to make sure your artwork fits well in these safe zones, or it may get cropped or scaled up.  
Although your artwork can fill an entire safe zone, the upper-right corner will always be partially obscured by the page curl effect that iOS adds. In addition, iOS adds a gradient that transitions from black (near the top, just below the page curl) to transparent (at the bottom edge).  
**Important:** Be sure to follow the guidelines in this section as you create a custom document icon for your iPad app. If your icon is too large, too small, or improperly padded, the resulting document icon will not look good.  
To create a 64 x 64 pixel document icon:  
- **1.** Create a 64 x 64 pixel image in PNG format.
- **2.** Add the following margins to create the appropriately sized safe zone:
- 1 pixel on top
- 4 pixels on bottom
- 10 pixels on each side  
Your safe zone should look similar to the colored area shown below:  
![](images/_page_145_Picture_17.jpeg)  
**3.** Place your custom artwork within the 44 x 59 pixel safe zone. The artwork can be centered, offset, or it can fill the entire safe zone. (Remember that iOS adds the page curl to the upper-right corner and a gradient that runs from the page curl to the bottom edge.)  
#### Custom Icon and Image Creation Guidelines  
For example, if you supply an icon that looks like the image on the left, iOS creates a document icon that looks like the image on the right.  
![](images/_page_146_Picture_3.jpeg)  
![](images/_page_146_Picture_4.jpeg)  
To create a 320 x 320 pixel document icon:  
- **1.** Create a 320 x 320 pixel image in PNG format.
- **2.** Add the following margins to create the appropriately sized safe zone:
- 5 pixels on top
- 20 pixels on bottom
- 50 pixels on each side  
Your safe zone should look similar to the colored area shown below:  
![](images/_page_146_Picture_12.jpeg)  
**3.** Place your custom artwork within the safe zone, which is 220 x 295 pixels. The artwork can be centered, offset, or it can fill the entire safe zone. (Remember that the page curl will obscure some of the artwork in the upper right corner of the safe zone.)  
For example, if you supply an icon that looks like the image on the left, iOS creates a document icon that looks like the image on the right.  
![](images/_page_147_Picture_2.jpeg)  
![](images/_page_147_Picture_3.jpeg)