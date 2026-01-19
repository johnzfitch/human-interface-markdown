<!-- Chunk 90 | Source: 2014 iOS Human Interface Guidelines.pdf | Est. Tokens: 197 -->
If appropriate, you can design a custom input view to replace the system-provided onscreen keyboard.  
If you provide a custom input view, be sure its function is obvious to people.  
You can also provide a custom input accessory view, which is a separate view that appears above the keyboard (or your custom input view).  
Use the standard keyboard click sound to provide audible feedback when people tap the custom controls in your input view. To learn how to enable this sound in your code, see the documentation for playInputClick in *UIDevice Class Reference* .  
**Note:** The standard click sound is available only for custom input views that are currently onscreen. People can turn off all keyboard clicks—including ones that come from your custom input view—in Settings > Sounds.