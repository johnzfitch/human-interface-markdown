<!-- Chunk 200 | Source: 2011 iOS Human Interface Guidelines.pdf | Est. Tokens: 963 -->
The Retina display allows you to display high-resolution versions of your art and icons. If you merely scale up your existing artwork, you miss out on the opportunity to provide the beautiful, captivating images users expect. Instead, you should rework your existing image resources to create large, higher quality versions that are:  
● **Richer in texture**. For example, in the high-resolution versions of the Settings and Contacts icons, the metal and paper textures are clearly visible.  
![](images/_page_152_Picture_5.jpeg)  
![](images/_page_152_Picture_6.jpeg)  
![](images/_page_152_Picture_7.jpeg)  
![](images/_page_152_Picture_8.jpeg)  
● **More detailed**. For example, in the high-resolution versions of the Safari and Notes icons, you can see details such as the accurate contours of the continents behind the compass and the torn paper left by the previous note.  
![](images/_page_152_Picture_10.jpeg)  
![](images/_page_152_Picture_11.jpeg)  
![](images/_page_152_Picture_12.jpeg)  
![](images/_page_152_Picture_13.jpeg)  
● **More realistic**. For example, the high-resolution versions of the Compass and Photos icons combine rich texture and fine details to create realistic portrayals of a compass and a photograph.  
![](images/_page_152_Picture_15.jpeg)  
![](images/_page_152_Picture_16.jpeg)  
![](images/_page_152_Picture_17.jpeg)  
![](images/_page_152_Picture_18.jpeg)  
Even though bar icons are simpler than application or document icons, you should consider adding details as you create high-resolution versions of them. For example, the artists tab bar icon in the iPod application is a streamlined silhouette of a singer. The high-resolution version of this icon is recognizably the same icon, but includes greater detail.  
![](images/_page_152_Picture_20.jpeg)  
![](images/_page_152_Picture_21.jpeg)  
The following techniques can help you get great results as you create a high-resolution version of your artwork.  
**Scale up your original artwork to 200%** using the "nearest neighbor" scaling algorithm. This works well if the original artwork was not created with vector shapes and does not include layer effects. The result is a large, pixelated image on top of which you can draw matching high-resolution art. This is a good way to begin because it allows you to preserve the original layout of your design.  
#### **CHAPTER 8**  
Custom Icon and Image Creation Guidelines  
If the original artwork was created with vector shapes, or it includes layer effects, you can use the default scaling algorithm instead of the nearest neighbor algorithm.  
**Add detail and depth**. Don't hesitate to draw very small elements, because the high-resolution version of your artwork allows much more room for fine details. For example, a 1-pixel dot in your original image becomes a 4-pixel dot (that is, 2 x 2 pixels) in the larger version.  
**Consider softening scaled-up elements**. If, for example, you have a sharp, 1-pixel dividing line in your original artwork, it might have the boldness you want when you leave it scaled up to a 2-pixel line. But for some lines and elements, you might want to soften the scaled results by feathering or even leaving the element at the smaller size.  
**Consider adding blur for better results in effects such as engravings and drop shadows**. For example, text engraving istypically done by shifting a duplicate image of the text by 1 pixel. Scaled up, thisshift would result in an engraving width of 2 pixels, which islikely to look very sharp and unrealistic at a higher resolution. To improve this, you can leave the shift as-is (that is, at 1 pixel), but add a 1-pixel blur to soften the engraving. This still results in a 2-pixel wide engraving effect, but the outer pixel now looks more like it is only half a pixel wide, which results in a better sense of dimensionality.