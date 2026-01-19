<!-- Chunk 106 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 199 -->
An **image view** displays one image or an animated series of images.  
**API Note:** To learn more about defining an image view in your code, see "Image Views".  
#### An image view:  
- Has no predefined appearance and it doesn't enable user interaction by default
- Examines properties of both the image and its parent view to determine whether the image should be stretched, scaled, sized to fit, or pinned to a specific location  
In iOS 7, an image view that contains a template image applies the current tint color to the image.  
**As much as possible, ensure that all images in an image view have the same size and use the same scale.** If your images have different sizes, the image view will adjust them separately; if your images use different scale factors, they may render incorrectly.