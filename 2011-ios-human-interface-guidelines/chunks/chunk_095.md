<!-- Chunk 95 | Source: 2011 iOS Human Interface Guidelines.pdf | Est. Tokens: 318 -->
A custom input view can replace the system-provided onscreen keyboard in apps running in iOS 3.2 and later. For example, Numbers on iPad provides an input view that's designed to make entering dates and times easy and efficient.  
![](images/_page_90_Picture_4.jpeg)  
If you provide a custom input view, be sure its function is obvious to people. Also, be sure to make the controls in your input view look tappable.  
You can also provide a custom input accessory view, which is a separate view that appears above the keyboard (or your custom input view). For example, in some contexts, Numbers displays an input accessory view that allows users to perform standard or custom calculations on spreadsheet values.  
![](images/_page_90_Picture_7.jpeg)  
In iOS 4.2 and later, you can use the standard keyboard click sound to provide audible feedback when people tap the custom controls in your input view. To learn how to enable this sound in your code, see the documentation for playInputClick in *UIDevice Class Reference*.  
<span id="page-90-1"></span>**Note:** The standard click sound is available only for custom input views that are currently onscreen. People can turn off all keyboard clicks(including onesthat come from your custom input view) in Settings > Sounds.