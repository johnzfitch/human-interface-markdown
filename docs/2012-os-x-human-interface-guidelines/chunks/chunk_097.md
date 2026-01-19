<!-- Chunk 97 | Source: 2012 OS X Human Interface Guidelines.pdf | Est. Tokens: 756 -->
Traditionally, a document icon looks like a piece of paper with its top-right corner folded down. This distinctive appearance makes it easy for users to distinguish their documents from their apps and other content, even when the icon sizes are small.  
Follow these guidelines as you design document icons for your app.  
**Make it obvious that your app and the documents it produces are related.** In addition to using the familiar folded-corner outline, you can add an image that reminds users of your app. In general, use your app icon for this purpose. For example, it's easy for users to tell which documents they created in Pages.  
![](images/_page_126_Picture_9.jpeg)  
**Present a document icon as if it were hovering on the desktop.** This perspective helps you reproduce the appropriate shadow behind the document.  
**Provide a set of documenticons in the same set of sizes you provide for your app icon.** For the recommended standard- and high-resolution sizes, see [Table](#page-117-0) 5-1 (page 118).  
As you do with your app icons, create an .icns file for your document icons. To learn more about how to create this type of file, see "Tips for [Designing](#page-111-0) Icons" (page 112).  
**Integrate a badge into the document shape (if one is necessary).** If you want to put an identifying badge over a document icon, treat the badge as an integrated element within the icon. Don't spoil the document icon shape by adding a badge that extends beyond the outline and appears to be above the document.  
![](images/_page_127_Picture_3.jpeg)  
**Move the image appropriately to accommodate the badge.** You need to allow enough space at the bottom edge of the document icon to display the badge. As a result, the upper-right corner of your image might be obscured by the folded-corner appearance of the background.  
![](images/_page_127_Picture_5.jpeg)  
**Use the appropriate font and font sizes for the badge.** For all sizes, use Lucida Grande Bold, in color sRGB 0,0,0, and with 66% opacity. If you are using iconutil to generate your .icns files, you don't have to worry about font sizes.  
However, if you create your own .icns files, use the following font sizes to add a badge to all sizes of your document icon:  
- 144 point text for the 512x512@2x pixel document icon
- 72 point text for the 512x512 pixel document icon
- 36 point text for the 256x256 pixel document icon
- 18 point text for the 128x128 pixel document icon
- 9 point text for the 64x64 pixel document icon  
● 6.5 point text for the 32x32 pixel document icon  
Note that you should "Greek" the badge text in the 16x16 pixel version of your document icon.  
If a document badge has a lot of characters, show as many of them as possible in the larger icon sizes, without shrinking the font too much. In the smaller sizes, simply truncate the badge text (don't add an ellipsis). For example, the badge text "Archive" does not fit completely in the 32x32 pixel version of this document icon:  
![](images/_page_128_Picture_4.jpeg)