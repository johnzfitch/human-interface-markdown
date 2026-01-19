<!-- Chunk 189 | Source: 2006-10 Apple Human Interface Guidelines.pdf | Est. Tokens: 579 -->
You need to provide at least the following files:  
- A 128 x 128 image (for Finder icons)
- A mask that defines the image's edges so that the operating system can determine which regions are clickable  
Icons that display in the Finder are viewed at different sizes: They can be magnified in the Dock, they can be previewed at full size, and users can specify a preferred size. For the best-looking icons at all sizes, you should also provide custom image files ("hints") at two other sizes: 32 x 32, and 16 x 16. Although the Dock doesn't use hints (it uses a sophisticated algorithm on the 128 x 128 version), hints are important for preserving crucial details in Finder icons.  
If you are creating an icon that will never change size—on a bevel button, for example—you can supply the image only at actual size.  
Here are the suggested steps for creating an icon:  
#### 1. Sketch the icon.  
Work out the concept and details of your design on paper, not with software. You should be ready to execute the idea by the time you open an application.  
2. Create a software illustration of the icon.  
Although you may want the final icon to look like a photograph, in most cases it's inadvisable to start with an actual photograph. An illustration provides much more flexibility for conveying a concept in a very small space. An illustration also gives you necessary control over details, perspective, light and shadow, texture, and so on.  
3. Add detail and color.  
For each enhancement you make to a larger-version icon, consider whether it is truly adding something to the icon's usability or whether it is just adding complexity or clutter.  
4. Add shadows.  
Shadows give objects dimensionality and realism. They also help tie the elements of an icon together so it doesn't look like a collage. The light source should be above and slightly in front of the object. The resulting shadow should create the sense that the icon is resting on a surface.  
- 5. In an image-editing program, manipulate the image to get precise effects and create the icon mask.
- 6. Convert the icon to a .icns file.You can complete this step with Icon Composer, included with the Xcode Tools, a set of tools for developers that are included in Mac OS X. There are also several third-party tools available for completing this step.