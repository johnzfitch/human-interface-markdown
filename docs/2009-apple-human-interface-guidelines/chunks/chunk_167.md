<!-- Chunk 167 | Source: 2009 Apple Human Interface Guidelines.pdf | Est. Tokens: 916 -->
If you're designing an application icon for Mac OS X v10.5 and later, you should supply a 512 x 512 pixel version of the image. When you do this, be sure to treat the 512 x 512 pixel version as its own resource; that is, don't create it by blowing up each pixel of the 128 x 128 pixel version of the icon. For example, the 512 x 512 pixel version of the icon should not have thick strokes or look "vectorized." In general, the larger icon should be a higher quality rendition of the 128 x 128 pixel resource, which exhibits:  
- Richer texture
- More details
- Greater realism  
<span id="page-148-1"></span>For example, the 512 x 512 pixel version of the Front Row application icon (shown in Figure 11-20) reveals more detail in the wood grain of the chair frame and the velvet of the upholstery than in the 128 x 128 pixel version, resulting in a more realistic image.  
**Figure 11-20** A 512 x 512 pixel icon should not be a scaled-up 128 x 128 pixel icon  
![](images/_page_148_Picture_9.jpeg)  
Simply enlarging a smaller icon to make a larger icon will not provide the sharpness and detail required.  
You also need to be aware of how the Cover Flow view in Finder displays your application icon. In Cover Flow, icons are displayed against a black background, set above a highly reflective surface. Because of this, you may need to adjust your icon in the following ways:  
- If your icon includes a drop shadow, be sure to make the shadow fully black. If the drop shadow contains any gray tones, the gray will show up against the black background and make the shadow look more like a glow.
- If your icon is very dark or has black edges, consider adding a slight inner glow just inside the edges to make the icon stand out against the black background.  
If you don't add a glow to make the edges of your icon prominent, it might appear to dissolve into the black background of the Cover Flow view.  
● Avoid giving important parts of your icon high alpha levels (that is, lots of transparency), especially in the lower half of the icon. Areas with too much alpha may get clipped.  
In Cover Flow view, the Finder positions icons so that they appear to be on the same plane. To do this, the Finder begins examining an icon at the bottom edge, looking for pixels that are opaque enough to use for alignment. If there is significant transparency in the lower area of your icon, the Finder ignores the transparent pixels in favor of the first opaque pixel it finds. The Finder uses the opaque pixel to determine the icon's alignment with respect to the plane and may clip the transparent pixels below it.  
<span id="page-149-0"></span>To see why some of these adjustments might be necessary, you can examine the standard MacOS X application icons in a computer running Mac OS X v10.5 or later. For example, in Figure 11-21, the Spaces icon includes a subtle glow inside the edge of the black frame, which makes it more visible on the black background.  
**Figure 11-21** An icon with black edges can include an inner glow to look good in Cover Flow  
![](images/_page_149_Picture_7.jpeg)  
The Mail icon, on the other hand, includes a cancellation mark that extends past the bottom edge of the stamp image (you can see this icon in [Figure](#page-139-2) 11-2 (page 140)). Because this area of the icon has high alpha levels, the Finder uses an opaque pixel at the bottom left corner of the stamp image to align the icon, clipping some of the cancellation mark, as shown in Figure 11-22.  
<span id="page-150-1"></span>**Figure 11-22** Areas of high alpha levels at the lower edge of an icon can get clipped in Cover Flow  
![](images/_page_150_Figure_3.jpeg)