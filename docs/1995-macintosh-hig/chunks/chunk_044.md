<!-- Chunk 44 | Source: 1995 Macintosh Human Interface Guidelines.pdf | Est. Tokens: 486 -->
When dialog boxes are localized, the text in the dialog box may become longer or shorter. Also, the alignment of controls in the dialog box may vary with localization. For example, Arabic and Hebrew are written from right to left, so the alignment of items in an Arabic or a Hebrew dialog box is generally right to left, just as dialog box items in English or Russian are generally left to right. Figure 2-2 shows examples of English and Arabic dialog boxes.  
**Figure 2-2** English and Arabic dialog boxes  
![](images/_page_43_Picture_5.jpeg)  
![](images/_page_43_Picture_6.jpeg)  
![](images/_page_43_Picture_7.jpeg)  
Find dialog box "English" More Choices dialog box "English"  
![](images/_page_43_Picture_9.jpeg)  
![](images/_page_43_Picture_10.jpeg)  
When the alignment of items is reversed, it's important that the elements appear vertically aligned. Therefore, when you create dialog box items, make sure that their display rectangles are the same size. Figure 2-3 shows examples of the incorrect and correct ways to size display rectangles in a dialog box.  
**Figure 2-3** Dialog boxes with display rectangles that are different sizes and the same size  
![](images/_page_44_Picture_5.jpeg)  
Figure 2-4 shows the same dialog boxes with the alignment of their elements reversed, as they would appear in a right-to-left script system. This figure shows that when the controls are reversed, they don't align properly, which is why it's important to create display rectangles of the same size.  
**Figure 2-4** Right-to-left alignment of dialog box items  
![](images/_page_44_Picture_8.jpeg)  
<span id="page-45-0"></span>Another common problem occurs when dialog box items are longer than the boundaries of the dialog box. In this case, when the text direction is reversed, the text appears outside of the dialog box and isn't visible on the screen. Be sure to make your dialog box items shorter than the width of the dialog box.