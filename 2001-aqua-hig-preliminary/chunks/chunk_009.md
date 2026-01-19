<!-- Chunk 9 | Source: 2001 Aqua Human Interface Guidelines (Preliminary).pdf | Est. Tokens: 562 -->
If you are a Carbon developer and your application uses custom interface elements —elements drawn by your application rather than being defined as system controls—this section describes steps to make your application Aqua-compliant. If you are a Cocoa developer using the Application Kit to create your application interface, you don't need to concern yourself with this process. Cocoa developers who want to customize standard controls or create entirely new ones should subclass existing Application Kit objects.  
<span id="page-16-2"></span>If you design your Carbon application to be fully compliant with the Appearance Manager, your application will work with Aqua, even if Apple makes changes to Aqua after you've finished developing your application. Using the Appearance Manager doesn't involve any additional complexity; as *Programming With the Appearance Manager* states, "The key to making your program Appearance-compliant is to allow the system to do as much of your interface work for you as possible." All Appearance Manager calls are Carbon-compliant, as well.  
<span id="page-16-1"></span>Here is a quick review of how to work with the Appearance Manager:  
- Register with the Appearance Manager.
- Use the system-defined windows supplied by the Window Manager instead of creating your own.
- Use the wide assortment of system-defined controls available through the Control Manager instead of creating your own.
- Make your dialogs and alerts Appearance-compliant.
- When you absolutely cannot use standard interface elements, use Appearance Manager functions to make your custom elements Appearance-compliant.
- Remove color table resources for windows, controls, menus, dialogs, and alerts from your application.
- Make no assumptions about color values for your interface. Instead of hard-coding color values, use the Appearance Manager constants of type ThemeBrush and ThemeTextColor.
- Make no assumptions about the dimensions of menus, windows, or controls, since they could change in the future.  
For more information and code samples, see *Programming With the Appearance Manager* and the source code for the Appearance Sample, available as part of the Appearance Manager SDK available at http://developer.apple.com/sdk.