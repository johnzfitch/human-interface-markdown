<!-- Chunk 46 | Source: 2000 Adopting the Aqua Interface.pdf | Est. Tokens: 515 -->
This section describes steps that Carbon developers should take to make their application Aqua-compliant. Cocoa developers do not need to concern themselves with this process if they use Interface Builder to create their applications.  
If you design your Carbon application to be fully compliant with the Appearance Manager, your application should, in most cases, work with Aqua as well. The process of using the Appearance Manager does not involve any additional complexity; as *Programming With the Appearance Manager* states, "The key to making  
#### **CHAPTER 1**  
#### Adopting the Aqua Interface  
your program Appearance-compliant is to allow the system to do as much of your interface work for you as possible." All Appearance Manager calls are Carbon-compliant, as well.  
Here is a quick review of how to work with the Appearance Manager:  
- Register with the Appearance Manager.
- Whenever possible, use the system-defined windows supplied by the Window Manager instead of creating your own.
- Whenever possible, use the system-defined menus supplied by the Menu Manager instead of creating your own.
- Whenever possible, use the wide assortment of system-defined controls available through the Control Manager instead of creating your own. At a minimum, you should revise any custom controls in your application so that they work in control hierarchies.
- Make your dialogs and alerts Appearance-compliant.
- When you absolutely cannot use standard interface elements, use Appearance Manager functions to make your custom elements Appearance-compliant.
- Remove color table resources for windows, controls, menus, dialogs, and alerts from your application.
- Make no assumptions about color values for your interface. Instead of hard-coding color values, use the Appearance Manager constants of type ThemeBrush and ThemeTextColor.
- Make no assumptions about the dimensions of menus, windows, or controls.  
For more information on this process, see *Programming With the Appearance Manager.*  
#### **CHAPTER 1**  
Adopting the Aqua Interface