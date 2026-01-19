<!-- Chunk 190 | Source: 2014 OS X Human Interface Guidelines.pdf | Est. Tokens: 526 -->
A template image is a streamlined, monochromatic image that can acquire different visual effects, such as selection highlighting and vibrancy. The best template images convey meaning through outline and contour, and include very little internal detail.  
You want to make your template image assolid as possible (that is, with very little transparency or alpha values) so that it will look good when the system applies effects, such as the inactive appearance. An image that uses too much transparency can look disabled when the system applies either the active or inactive appearance to it.  
To create a solid image, you might start by imagining the shadow your object would cast. If the contours of the shadow clearly show what the object is, you don't need to add any transparency.  
As you design a template image to put inside a toolbar control, such as a button or segmented control, follow these guidelines:  
- Create images that measure no more than 19 x 19 pixels.
- Make the outline sharp and clear.
- Use a straight-on perspective.
- Use black (add transparency only as necessary to suggest dimensionality).
- Use anti-aliasing.
- Use the PDF format.
- Make sure the image is visually centered in the control (note that visually centered might not be the same as mathematically centered).  
**Note:** When you're designing a template image for a toolbar control, it's recommended that you use black, which makes it easier to discern details and outlines. However, you can use any color to create your images, because the system ignoresthe color and pays attention only to the alpha values you add.  
When you create a template image to put inside a toolbar control in PDF format, OS X automatically scales the icon for high-resolution display, so you don't need to provide a high-resolution version.  
You might be able to use a system-provided image to represent a common task or a standard interface element in your toolbar controls, such as the connect via Bluetooth icon. To learn about the images that are available and what they mean, see [System-Provided](#page-328-0) Images (page 329).